# Building and Launching the App

## Initial Setup:

This file describes how to build and launch the app. 

Start by opening two shells; one for running the backend and the other for the frontend.

## Frontend Setup:

Navigate to the frontend directory: ./Project_Anki/Frontend.

Install dependencies: npm install.

Launch the frontend: Execute ng serve.

Access the app: Navigate to http://localhost:4200/. The app will auto-reload on source file changes.

## Backend Setup:

Go to the backend directory: ./Project_Anki/Backend.

Install backend dependencies: npm install.

Start the backend server: Execute node ./server.js.

# Mise en Place d'une Base de Données PostgreSQL


## Étapes de Configuration et de Gestion de la Base de Données PostgreSQL

Ouverture de PGAdmin
PGAdmin est l'interface graphique principale pour la gestion de bases de données PostgreSQL.
Pour démarrer, ouvrez PGAdmin depuis votre ordinateur.

# Vérification de la Connexion à la Base de Données

En cas d'erreur de connexion à la base de données, le problème peut être dû à un service PostgreSQL non démarré.
Le message "le temps de connexion est trop long" indique souvent que le service n'est pas actif.

# Démarrage du Service PostgreSQL

Appuyez sur la touche Windows et tapez Services pour ouvrir l'application Services.
Faites défiler la liste jusqu'à trouver un service nommé semblable à postgresql.
Cliquez sur ce service, puis sélectionnez Démarrer pour activer le service PostgreSQL.

# Contrôle via PowerShell

Il est à noter que la gestion de ce service ne se fait pas idéalement via PowerShell.

# Création et Peuplement de Tables

Une fois la connexion établie avec PGAdmin, vous pouvez procéder à la création des tables user, lecon, et flashcard en utilisant les scripts SQL fournis.
Assurez-vous de suivre les bonnes pratiques de sécurité, notamment en ce qui concerne le stockage des mots de passe.

# Insertion de Données

Insérez des données de démonstration dans chaque table pour tester leur fonctionnement.
Ces données sont essentielles pour valider la structure et l'intégrité de votre base de données.
