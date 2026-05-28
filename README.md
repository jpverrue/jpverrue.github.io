# Essai de page web
Rédigée en MD

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
