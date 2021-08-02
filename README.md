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
   {
     "name": "nouveau-projet",
     "description": "Description du nouveau-projet",
     "author": "Votre nom",
     "license": "MIT"
   } 
### Installation des 'packs' du projet et démarrage de l'environement de développement
    npm install
### Démarrage de l'environement de développement
    npm run dev
### Compilation d'une version prête au déploiement dans le dossier '/dist'
    npm run build
## Documentations externes
- __[html5-boilerplate](https://github.com/h5bp/html5-boilerplate/blob/v8.0.0/dist/doc/TOC.md)__ - Projet de départ HTML5 complet
