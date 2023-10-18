# Mon Application React

Ce projet est une application React comprenant un serveur Node.js et une base de données MongoDB. Vous pouvez le démarrer en mode de développement en suivant les étapes ci-dessous.

## Prérequis

- Node.js (https://nodejs.org/) doit être installé sur votre machine.
- Docker (https://www.docker.com/) doit être installé pour exécuter la base de données MongoDB dans un conteneur.

## Installation

1. Clonez ce référentiel sur votre ordinateur :

```bash
git clone https://github.com/isnardynicolas/quest3.git
cd quest3

Installez les dépendances du serveur et du client :

cd server
npm install
cd ../client
npm install

Démarrage du serveur (dans un terminal séparé) :

cd server
npm run dev

Démarrage de l'application client (dans un autre terminal) :

cd client
npm start

Le front-end React sera accessible à l'adresse : http://localhost:8080

