# ChaigncHackademy Day12
Session donné par [@chaignc][@chaignc].

Date: de 21H45 à 22H56 le 18/02/2020

## Contenu du cours

* Presentation du TP par: 

* @ph03nix 

## Résultat TP Day12
* Réussi:@Rhackelle, @A69, @binwalk, @Gb2000, @GimDivad, , @Kyb3R, @ph03nix, @Rozzario, @tisemtine, @ken_dji, @GimDivad, @ken_dji, @sampay
         @sancelisso, @lo_chk, @mugiwara👒G.f, @Casper, @Dele, @Kantogame94 ,@Giyu ,@maurishio
## Outils présentés

* Symmetric Encryption
* Asymmetric Encryption

## Autres outils présentés
* md5 hashsum

## Commandes présentées
```
gpg -c data.txt 
data.txt.gpg
md5sum data.txt
openssl genrsa -aes256 -out private.key 8912
openssl rsa -in private.key -pubout -out public.key
openssl rsautl -encrypt -pubin -inkey public.key -in plaintext.txt -out encrypted.txt
openssl rsautl -decrypt -inkey private.key -in encrypted.txt -out plaintext.txt
```

## Liens / Ressources

* [Encryption](https://www.cloudflare.com/learning/ssl/what-is-encryption/)
* [AES](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard)

[@chaignc]:https://twitter.com/chaignc
[hexpresso]:https://hexpresso.github.io
[@Grenadine]:https://twitter.com/Greynardine
[@SaxX]:https://twitter.com/_saxx_
