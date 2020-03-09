---
layout: "post"  
title:  "Angular"  
categories: "front"  
--- 
Angular est un framework permettant de créer des application web de type "single page".  
## Introduction
Actuellement en train de monter en compétence sur la technologie Angular, j'en profite pour compiler les information qui me semblent intéressantes sur ce framework. Pour ce qui est du ressenti en lui même, je le trouve vraiment pratique et bien documenté, ce qui est primordial pour travailler dans de bonnes conditions.  

## Informations générales 
* Version actuelle : `Angular 9`
* Langage utilisé : `TypeScript`

## Architecture générale d'un projet

📦angular-course  
 ┣ 📂src  
 ┃ ┣ 📂app  
 ┃ ┃ ┣ 📂cart  
 ┃ ┃ ┃ ┣ 📜cart.component.css  
 ┃ ┃ ┃ ┣ 📜cart.component.html  
 ┃ ┃ ┃ ┗ 📜cart.component.ts  
 ┃ ┃ ┣ 📂product-alerts  
 ┃ ┃ ┃ ┣ 📜product-alerts.component.css  
 ┃ ┃ ┃ ┣ 📜product-alerts.component.html  
 ┃ ┃ ┃ ┗ 📜product-alerts.component.ts  
 ┃ ┃ ┣ 📂product-details  
 ┃ ┃ ┃ ┣ 📜product-details.component.css  
 ┃ ┃ ┃ ┣ 📜product-details.component.html  
 ┃ ┃ ┃ ┗ 📜product-details.component.ts  
 ┃ ┃ ┣ 📂product-list  
 ┃ ┃ ┃ ┣ 📜product-list.component.css  
 ┃ ┃ ┃ ┣ 📜product-list.component.html  
 ┃ ┃ ┃ ┗ 📜product-list.component.ts  
 ┃ ┃ ┣ 📂shipping  
 ┃ ┃ ┃ ┣ 📜shipping.component.css  
 ┃ ┃ ┃ ┣ 📜shipping.component.html  
 ┃ ┃ ┃ ┗ 📜shipping.component.ts  
 ┃ ┃ ┣ 📂top-bar  
 ┃ ┃ ┃ ┣ 📜top-bar.component.css  
 ┃ ┃ ┃ ┣ 📜top-bar.component.html  
 ┃ ┃ ┃ ┗ 📜top-bar.component.ts  
 ┃ ┃ ┣ 📜app.component.css  
 ┃ ┃ ┣ 📜app.component.html  
 ┃ ┃ ┣ 📜app.component.ts  
 ┃ ┃ ┣ 📜app.module.ts  
 ┃ ┃ ┣ 📜cart.service.ts  
 ┃ ┃ ┗ 📜products.ts  
 ┃ ┣ 📂assets  
 ┃ ┃ ┗ 📜shipping.json  
 ┃ ┣ 📂environments  
 ┃ ┃ ┣ 📜environment.prod.ts  
 ┃ ┃ ┗ 📜environment.ts  
 ┃ ┣ 📜index.html  
 ┃ ┣ 📜main.ts  
 ┃ ┣ 📜polyfills.ts  
 ┃ ┗ 📜styles.css  
 ┣ 📜angular.json  
 ┣ 📜package.json  
 ┗ 📜README.md  

## Commandes importantes

### Installer Angular 

`npm install -g @angular/cli`

### Créer un projet Angular 

`ng new project-name`

### Déploiement local du projet Angular

`ng serve --open` ou `ng serve -o`

### Créer un composant 
`ng generate component component-name`

### Ajouter la lib Angular Material 
`ng add @angular/material`

### Ajout de dépendence
`ng add _______`

### Deployer et tester
`ng test`

### Déployer en production
`ng build --prod`

