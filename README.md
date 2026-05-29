# Démonstration de page web Github

Cette page est rédigée en Markdown ; c'est le README d'un tout petit projet jamais terminé. Si vous voulez voir le code de la page et la simplicité du dépôt, cliquez sur le lien mentionné en bas de page.


 Pour tout savoir sur les pages Web Github, c'est [ICI](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)  pour un  « What is » (EN). Et [ICI](https://docs.github.com/fr/pages/quickstart) pour un « quick start »  (FR).

---
### dialog
Small tool to use windows in a shell script.

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
Et voici le [PDF](./Github.io-README.pdf) de cette page WEB
