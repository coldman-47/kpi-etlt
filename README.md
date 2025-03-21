# Projet Grafana, MySQL et Docker

Ce projet permet de visualiser des données stockées dans une base de données MySQL à l'aide de Grafana. Tout est conteneurisé avec Docker pour une prise en main facile.

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Installation et démarrage

1. **Clonez le dépôt** sur votre machine locale :

   ```bash
   git clone https://github.com/votre-utilisateur/votre-repo.git
   cd votre-repo

2. Démarrez les conteneurs avec Docker Compose :
   ```bash
   docker-compose up -d

  Cette commande va :

    Créer les images Docker nécessaires.

    Démarrer un conteneur MySQL et charger les données initiales.

    Démarrer un conteneur Grafana.

    
3. Accédez à Grafana :

  Ouvrez votre navigateur et rendez-vous à l'adresse suivante : http://localhost:3000


4. Connectez-vous à Grafana :

    Nom d'utilisateur : admin

    Mot de passe : admin

5. Importez le tableau de bord :

    Une fois connecté, allez dans l'interface de Grafana.

    Cliquez sur le bouton "+" dans le menu de gauche, puis sélectionnez "Import".

    Importez le fichier de tableau de bord fourni dans ce projet (fichier JSON).
