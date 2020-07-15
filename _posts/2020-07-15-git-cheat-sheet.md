--- 
layout: "post"
title: "Git Cheat Sheet"
categories: "versionning"
---

## Commandes importantes 
### Créer et cloner un repo 
Créer un repo  
`git init`  
Cloner un repo  
`git clone <url>`  

### Mise à jour du code en local 

`git pull `

### Pousser les modifications sur le repo 
On ajoute 1 fichier à l'index de modifications  
`git add <filename>`  
**ou** tous les fichiers  
`git add *`  
Supprimer un fichier des modifications à envoyer sur le repo  
`git rm <filename>`


On pousse les modifications sur le repo  
` git push origin <nomBranche> `

### Branches 
Créer une branche 

`git checkout -b <branch>`

Repasser sur la branche master  
`git checkout master`

Supprimer une branche  
`git branch -d <branch>`

Pousser le contenu de la branche sur le repo  
`git push origin <branch>`  

### Merge 

Faire un merge depuis une autre branche  
`git merge <branch>`  

Voir le différences entre 2 branches  
`git diff <branche_source> <branche_cible>`