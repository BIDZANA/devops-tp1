# DevOps TP1

Ce référentiel contient le code source et les ressources du TP1 de DevOps.

## Description

Le projet TP1 de DevOps consiste à mettre en place une architecture en trois niveaux comprenant un serveur HTTP, une API backend et une base de données. Nous utilisons Docker et Docker Compose pour orchestrer ces services. 

## Structure du projet

Le projet est structuré de la manière suivante :

- `backend-api/`: Contient le code source de l'API backend.
- `http-server/`: Contient le code source du serveur HTTP.
- `database/`: Contient les fichiers de configuration et les scripts SQL pour initialiser la base de données.
- `docker-compose.yml`: Fichier de configuration Docker Compose pour l'orchestration des services.

## Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés sur votre système :

- Docker
- Docker Compose
- Maven (pour le backend API)
- Java (pour le backend API)
- Git

## Installation et utilisation

1. Clonez ce référentiel sur votre machine locale.
2. Assurez-vous que les prérequis sont installés.
3. Exécutez `docker-compose up` pour démarrer l'application.

L'application sera accessible à l'adresse [http://localhost:8080](http://localhost:8080).

## Contributions

Les contributions à ce projet sont les bienvenues. Si vous souhaitez contribuer, veuillez suivre ces étapes :

1. Clonez le référentiel sur votre machine.
2. Créez une nouvelle branche pour vos modifications : `git checkout -b feature/nouvelle-fonctionnalite`.
3. Faites vos modifications et testez-les.
4. Commitez vos modifications : `git commit -m "Ajout d'une nouvelle fonctionnalité"`.
5. Poussez vos modifications vers votre fork du référentiel : `git push origin feature/nouvelle-fonctionnalite`.
6. Créez une demande d'extraction (Pull Request) vers la branche principale de ce référentiel.

## Auteur

- [BIDZANA Marvin](marvinbidzana@gmail.com)

## Licence

Ce projet n'est pas sous licence

---
