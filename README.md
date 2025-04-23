# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).
Ressource-Relationnelle (Frontend)

Ce projet est la partie front du système **Ressource-Relationnelle** (RR-back), une application permettant la gestion et l’échange de services entre utilisateurs. Ce dépôt contient l’interface utilisateur développée avec **React** et **Redux** pour la gestion de l'état global.

Prérequis

Avant de commencer, assurez-vous d’avoir les éléments suivants installés sur votre machine :

- **Node.js** (version 16 ou supérieure)
- **npm** (ou **yarn**, si vous préférez)

Installation

Clonez ce dépôt et installez les dépendances :

- git clone https://github.com/Erik-9999/Ressource-Relationnelle.git
- cd Ressource-Relationnelle
- npm install

 Démarrage
Pour démarrer l'application en mode développement, utilisez la commande suivante :
 - npm start
 - L'application sera accessible à l'adresse suivante :
 - http://localhost:3000

Technologies utilisées
 - React : Librairie JavaScript pour construire des interfaces utilisateurs.

 - Redux : Pour la gestion de l'état global de l'application.

 - React Router : Pour la gestion des routes.

 - Axios : Pour effectuer des appels HTTP vers le backend (RR-back).

- CSS/SCSS : Pour la gestion des styles de l'application.

- Collaboration avec le Backend (RR-back)
  - Cette application communique avec le backend RR-back via des API RESTful. Assurez-vous que le backend fonctionne et que l'API est correctement configurée avant d'utiliser l'application frontend.

API Endpoints
Voici quelques exemples d’API avec lesquelles l’application frontend interagit :

 - GET /api/ressources : Récupérer la liste des ressources disponibles.

 - POST /api/connexion : Se connecter à un utilisateur.

Pour plus de détails sur les endpoints, veuillez consulter le README du backend.

Fonctionnalités
 - Inscription / Connexion : Permet aux utilisateurs de s'inscrire et de se connecter au système.

 - Gestion des ressources : Affichage et gestion des ressources échangées.

 - Interface utilisateur réactive : Adaptation aux différents types d'appareils grâce au design réactif.

 - Recherche et filtrage : Permet de rechercher et filtrer les services disponibles.
