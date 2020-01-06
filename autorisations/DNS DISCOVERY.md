# CHAIGNC HACKADEMY

## RECON STEP

### DNS DISCOVERY

 - Purpose :  
   - find subdomains using commons tools
   - thoses subdomains are based on bruteforce
   - here is some common tools do help


- We will present tonite <strong>aquatone</strong> and <strong>sublist3r</strong>

#### DNS KEZACO

- Sur Internet, quand vous voulez accéder à un site web depuis votre navigateur, on utilise ce que l’on appelle un nom de domaine, par exemple <strong>pyramidhackers.com</strong>, <strong>hexpresso.fr</strong>, <strong>youtube.fr</strong>, …

- C’est en gros l’adresse du site web que vous tapez dans votre navigateur.

- En réalité, votre navigateur va avoir besoin de l’adresse IP du serveur sur lequel est hebergé votre site web; i.e: 87.98.242.65

- L’adresse IP est un numéro d’identification qui est attribué à chaque appareil connecté à un réseau informatique utilisant l’Internet Protocol (d’ailleurs le IP c’est pour Internet Protocol). En gros, ca veut dire que chaque ordinateur connecté à internet possède une adresse IP.

- Sauf que vous l’avez bien compris ce serait un peu compliqué pour nous de retenir ces adresses IP. Et c’est là qu’intervient le DNS (Domain Name System) qui va "traduire" ces noms de domaines en adresses IP. La résolution de noms de domaines, c’est la corrélation entre les adresses IP et le nom de domaine associé; une sorte de table de correspondance.

- Les serveur DNS sont tout simplement des serveurs qui font la correspondance entre les adresses IP et les noms de domaine associés.

- Maintenant, voyons comment tout ça marche un peu plus dans le détail. On va expliquer maintenant la notion de Hiérarchie DNS.

- Le système des noms de domaine est en fait une hiérarchie dont le sommet est appelé la racine. On représente cette dernière par un point “.” pour info ce point n’apparait pas dans les addresses de site web qu’on utilise sur Internet mais c’est bien le plus haut niveau.

- Les domaines se trouvant immédiatement sous la racine sont appelés domaine de premier niveau .fr, .com, .org, .bzh, etc (ou top domain level)

- Dans un nom de domaine, les domaines successifs sont séparés par un point, les noms de domaines supérieurs étant à droite. Le domaine wikipedia.org. est un sous-domaine de .org. et vous l’avez compris fr.wikipedia.org est un sous domaine de fr.wikipedia.org

- Il est possible d’avoir plusieurs sous-domaines ainsi qu’une délégation, c’est-à-dire une indication que les informations de ce sous-domaine sont enregistrées sur un autre serveur.

- On peut voir fr.wikipedia.org comme un sous domaine hébergé sur un serveur spécifique par exemple et de.wikipedia.com sur un autre serveur spécifique.

- La résolution des noms de domaines est réalisée en parcourant la hiérarchie depuis le sommet et en suivant les délégations successives.

- Voyons maintenant comment se passe la résolution du nom de domaine avec un navigateur

- Imaginez que vous entrez fr.wikipedia.org dans votre navigateur. Votre navigateur doit commencer par le résoudre en une adresse IP. tous simplement Parce qu’il faut qu’il sache à quel serveur se connecter.

Par exemple si l'on tape fr.wikipedia.org dans notre navigateur, il va s’adresser à un serveur dit “récursif”. Pour information, les FAI mettent à disposition de leurs clients ces serveurs récursifs par défaut quand il se connecte à Internet. Mais Il existe également des serveurs récursifs ouverts comme ceux de Google Public DNS ou OpenDNS ou Cloudfare.

- Quand un serveur DNS récursif doit trouver l’adresse IP de fr.wikipedia.org, un processus itératif commence pour consulter la hiérarchie DNS du nom de domaine :

    - Ce serveur demande aux serveurs DNS de nom racine quels serveurs peuvent lui répondre pour la partie org.
    - Le serveur va indiquer quels serveurs connaissent l’information pour la zone wikipedia.org.
    - Ensuite, ce serveur donnera à son tour l’information pour avoir l’adresse IP du serveur hébergeant fr.wikipedia.org. car il connait déjà l’adresse IP du serveur hébergeant le sous domaine fr de wikipedia.org
    - Et une fois que vous avez l’adresse IP de ce domaine, le navigateur y accède est affiche la page demandée

#### RECAP

<pre>
      verysecret.secret.site.tld
      *.site.tld
</pre>

|Tool|Link|
|--|--|
|Sublist3r|https://github.com/aboul3la/Sublist3r|
|massdns|https://github.com/blechschmidt/massdns
|altdns |https://github.com/infosec-au/altdns
|Knockpy |https://github.com/guelfoweb/knock|
|aquatone|https://github.com/michenriksen/aquatone|

#### AQUATONE
 <pre>
 aquatone-discover --domain yahoo.com
 </pre>

#### SUBLIST3R
 <pre>
 python sublist3r.py -d yahoo.com -b -t 50 -p 80,443,21,22
 </pre>
