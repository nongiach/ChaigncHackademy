# ChaigncHackademy Day04
Session donné par [@chaignc][@chaignc].

Contributeur externe: [@PHA][PHA]

Date: de 22H00 à 00H24 le 19/12/2019

## Contenu du cours

* Concepts de base des Expressions régulières 
* Les commandes de base en Linux

## Résultat TP Day04
* Réussi:Siegfried, Kyb3R, tisemtine, sancelisso, selom, hbygh, ph03nix, Cyr, Rhackelle26, notorious.r.a.c , ,notorious.r.a.c , 
Casper, Rozzario, L4NT3RN_chk🇹🇬, sampay, Juni19, charliepy, Géovanni, Steel Heart
* En Cours: sosso, 3l4un1ck, ken_dji, guyak89, Placide_RED,

## Outils présentés

cd, wc -l, cat, find, grep, regex, home, sha1, /etc/shadow, /etc/shadow, johntheripper

## Commandes présentées
```sh
grep -rn test
echo -e "test\ntutu\ntata\n"
echo -e "test\ntutu\ntata\n" | grep test
echo -e "test\ntutu\ntata\n" | grep "t.*a"
echo -e "test\ntutu\ntata\n" | grep "a$"
echo -e "test\ntutu\naaaa\n" | grep "^t"
grep 'chaignchckademy' fichier1 fichier2 fichier3 fichier3 fichier4 
cat /etc/issue
pwd
tshark -r Evil\ Elf.pcap -Y 'frame.number == 998' -T fields -e ip.dst
echo -e "test\ntutu\n44\n" | grep '[0-9]'
find -iname "metasploit"
find -iname "test"
ssh -p 2222 app-systeme-ch13@challenge02.root-me.org
```

## Liens / Ressources
* [RegExp (Wiki)](https://fr.wikipedia.org/wiki/Expression_r%C3%A9guli%C3%A8re)
* [Test RegExp Online](https://regexr.com/)
* [Linux basics](https://www.pyramidhackers.com/pyramid/linux/co/module_Ubuntu18_4.html)


[@chaignc]:https://twitter.com/chaignc
[hexpresso]:https://hexpresso.github.io
[@Grenadine]:https://twitter.com/Greynardine
[@SaxX]:https://twitter.com/_saxx_
