# ChaigncHackademy Day05
Session donné par [@chaignc][@chaignc].

Contributeur externe: [@SaxX]:https://twitter.com/_saxx_

Date: de 21H52 à 00H45 le XX/XX/2019

## Contenu du cours

* Rappel sur les bases des commandes Linux
* Prise en main OSINT

## Résultat TP Day04
* Réussi: @hbygh, @selom, @3l4un1ck, 
* En Cours: @guyak89, @ken_dji, @notorious.r.a.c, @sancelisso, @3l4un1ck, @sosso, @siegfried, @tisemtine

## Outils présentés
OSINT
binwalk
exiftools
FZF (Fuzzy Finder)

## Commandes présentées
```
openvpn --config ./Chaignc.ovpn
man ssh
ssh mcsysadmin@10.10.71.242
ls
man wc
man ls
echo test | wc -c
\n
retour a la ligne
echo -n test | wc -c
man cat
who | wc -l
cat file1
pipe linux
cat file5 | base64
cat file5 | base64 | base64 -d
grep -r password
man grep
grep --recursive password
grep -rl password
grep -r -l password
pwd
grep -r '[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}'
grep -r '([0-9]{1,3}.){1,3}[0-9]{1,3}'
grep  '([0-9]{1,3}.){1,3}[0-9]{1,3}' *
cat /etc/passwd | grep bash
echo $SHELL
mkdir test
cd test
sha256sum a
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## Liens / Ressources
* [OSINT](https://osintframework.com/)
* [OSINT FRAMEWORK](https://github.com/i3visio/osrframework)
* [REGEXP](https://regexr.com/)
* [MAITRISER LES REGEXP](https://www.lucaswillems.com/fr/articles/25/tutoriel-pour-maitriser-les-expressions-regulieres)
* [FUZZY FINDER](https://github.com/junegunn/fzf)
* [DAY 5 FULL VIDEO](https://www.youtube.com/watch?v=qMJf3nAmcBM)



[@chaignc]:https://twitter.com/chaignc
[hexpresso]:https://hexpresso.github.io
[@Grenadine]:https://twitter.com/Greynardine
[@SaxX]:https://twitter.com/_saxx_
