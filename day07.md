# ChaigncHackademy DayXX
Session donné par [@chaignc][@chaignc].

Contributeur externe: [@SaxX]:https://twitter.com/_saxx_

Date: de 21H43 à 23H54 le 06/01/2020

## Contenu du cours

* Presentation du TP par: 
* Rhackelle26

## Résultat TP Day06
* Réussi: tisemtine, sancelisso, ph03nix, Placide_RED, hbygh, Rhackelle26, Kyb3R, selom, ken_dji, Siegfried, Cyr, Emiya, notorious.r.a.c, lo_chk, Rozzario, sampay, Casper, ahouefa, Juni19, charliepy
* En Cours:

## Outils présentés

* gobusterdir : Outils permettant de lister des sous - Domaine, faire du bruteforcing et lister les fichiers ou dossier cachés depuis une source
* SUID
* NMAP


## Commandes présentées
```
fcrackzip -b --method 2 -D -p /usr/share/wordlists/rockyou.txt -v ./file.zip   pour extraire un fichier zip par brute force
steghide extract -sf ./<file to extract>.jpg
pour extraire un fichier image

alias ipa='ip --color --brief addr'
man find
find -iname test.md
find -iname "te*md" 2>/dev/null
find -iname "*.txt" -ls
find -iname "*.txt" -exec base64 {} ';'
find -iname "*.txt"  -perm -u=r -ls
vagrant
sudo tcpdump icmp
steghide
steghide extract -sf ./<file to extract>.jpg

groupadd mynewgroup
usermod -a -G sudo geek
cat /etc/passwd | grep cc

cat /etc/group | grep cc
id > test
ls -la
su test
chmod 777 test
chmod u=r,g=r,o=r test
chmod u=rwx,g=,o= test
setuid and setgid (short for "set user ID" and "set group ID")
which id
chown
sudo chown test B
sudo chown test:test B

```

## Liens / Ressources
* [Sharkdp](https://github.com/sharkdp/bat)
* [Sudo_inject by Chaignc](https://github.com/nongiach/sudo_inject)



[@chaignc]:https://twitter.com/chaignc
[hexpresso]:https://hexpresso.github.io
[@Grenadine]:https://twitter.com/Greynardine
[@SaxX]:https://twitter.com/_saxx_
