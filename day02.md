# ChaigncHackademy Day02
Session donné par [@chaignc][@chaignc].

Contributeur externe: [@SaxX][@SaxX]

Date: de 22h à 1H00 le 17/12/2019

## Contenu du cours

* TP du Day1 présenté par Guillaume ( @guyak89 )
  Utilisationll
* Explication des sessions et des cookies.
* Explication du protocol HTTP, codes d'erreurs, path, URI, URL.
* Explication de l'OSINT, github, linkedin et google dork.
* Explication d'outil d'énumération de chemin web avec wfuzz et gobuster.

## Résultat TP Day01
* Réussi:     Placide_RED, ken_dji, sancelisso, Emiya, Siegfried, Rhackelle26, guyak89, PH03N1X, Lolhack, hbygh, notorious.r.a.c, selom, 3l4un1ck,sosso, Cyr, Ahouefa, tisemtine, Ambroise, L4NT3RN_chk🇹🇬, lo_chk, sampay, Géovanni,
Steel Heart, charliepy, H4CK3D, Rozzario, Mr_John, papi, mugiwara,
* En Cours: agretsuko_susanoo66, geth1s_One$,Théo, yolande

## Outils présentés

man, ipython, Burp, wfuzz, gobuester, openvpn, curl, switchyomega, autojump

## Commandes présentées
```sh
ss -tln
netstat -tln
curl ifconfig.co
openvpn --config fichier_de_config
alias gobusterdir='gobuster dir -w /usr/share/dirb/wordlists/common.txt -o gobuster.txt -u'
gobuster dir -w VOTRE_WORDLIST -o gobuster.txt -u VOTRE_URL_ICI
wfuzz -c -w /usr/share/wordlists/dirb/common.txt http://challenge01.root-me.org/web-serveur/ch15/FUZZ
wfuzz -c --hc 404 -w /usr/share/wordlists/dirb/common.txt http://challenge01.root-me.org/web-serveur/ch15/FUZZ
wfuzz -c --hc 404,403 -w /usr/share/wordlists/dirb/common.txt http://challenge01.root-me.org/web-serveur/ch15/FUZZ
man wfuzz
j dossier
```

## Liens / Ressources
* [OSINT](https://fr.wikipedia.org/wiki/Renseignement_d%27origine_source_ouverte)
* [SwitchyOmega](https://addons.mozilla.org/fr/firefox/addon/switchyomega/)
* [SecLists](https://github.com/danielmiessler/SecLists)
* [autojump](https://github.com/wting/autojump)

[@chaignc]:https://twitter.com/chaignc
[hexpresso]:https://hexpresso.github.io
[@Grenadine]:https://twitter.com/Greynardine
[@SaxX]:https://twitter.com/_saxx_
