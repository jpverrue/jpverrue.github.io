# Démonstration de page web Github

Ceet page Rédigée en Markdown.
C'est le README d'un tout petit projet jamais terminé. 
---
### dialog
Small tool to use windows in a shell script

With Dialog it is possible to create shell scripts using windowing system.
For example:
```
#!/bin/bash
if dialog --yesno Do you want to display the time \? ; then
 date
else
 echo sorry
fi
```
There is no man page for instance. Only help option :
```
./dialog --help
./dialog :
        --menu
        --yesno
        --list
        --caption=<caption-string>
        --title=<title-string>
        --theme=<css-file>
        --position=<x-value>x<y-value>
        --size=<x-value>x<y-value>
        --help
        --version
```
There are still some bugs; not everything is working properly.
---
Pour tout savoir sur les pages Wieb Github,
c'est [ICI (EN)](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)  poue un  « What is »
et [ICI (FR)](https://docs.github.com/fr/pages/quickstart) pour un « quick start »
