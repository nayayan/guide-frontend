# Guide pratique et outils pour développement UI/UX
## Installations requises
- __[VSCode](https://code.visualstudio.com/)__ - Édition du code
  - __[Swissknife](https://marketplace.visualstudio.com/items?itemName=luisfontes19.vscode-swissknife)__ - Pack de plugins pour VSCode
- __[GIT](https://git-scm.com/downloads)__ - Contrôle des versions
- __[NodeJS](https://nodejs.org/)__ - JavaScript runtime (npm)
## Commencer un nouveau projet
### Création de la fondation du code et accès au dossier du projet dans VSCode
    git clone git@github.com:noreading/bootstrap5-webpack-boilerplate.git nouveau-projet
    cd nouveau-projet
    code .
### Réinitialisation du GIT
    rm -rf .git
### Modification du fichier package.json
```
   {
     "name": "nouveau-projet",
     "description": "Description du nouveau-projet",
     "author": "Votre nom",
     "license": "MIT"
   } 
```
### Installation des 'packs' du projet et démarrage de l'environement de développement
    npm install
### Démarrage de l'environement de développement
    npm start
### Compilation d'une version prête au déploiement dans '/dist'
    npm run build
## Documentations externes
- __[bootstrap5-webpack-boilerplate](https://github.com/noreading/bootstrap5-webpack-boilerplate)__ - Fondation d'un projet HTML5 complet
- - __[Bootstrap 5](https://getbootstrap.com/docs/5.0/customize/overview/)__ - Librairie UI/UX
