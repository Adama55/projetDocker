# FastAPI & MySQL Containerized Application

## Description

Ce projet présente une application containerisée utilisant FastAPI pour le backend et MySQL pour la base de données, orchestrée avec Docker. L'objectif est de créer une API REST simple avec des endpoints pour gérer des éléments, et de containeriser l'ensemble de l'application pour faciliter le déploiement et le développement.

## Fonctionnalités

- **Endpoints API :**
  - `GET /items/` : Récupérer une liste d'éléments.
  - `POST /items/` : Créer un nouvel élément.
  - `GET /items/{item_id}` : Récupérer les détails d'un élément spécifique par son ID.

- **Base de données :**
  - Base de données MySQL pour stocker et gérer les données des éléments.

- **Containerisation :**
  - Application Docker avec des conteneurs FastAPI et MySQL.
  - Adminer pour la gestion de la base de données.

## Technologies Utilisées

- **FastAPI** : Framework web moderne et rapide pour la construction d'API avec Python 3.6+.
- **MySQL** : Système de gestion de base de données relationnelles open-source.
- **Docker** : Plateforme pour développer, déployer et exécuter des applications dans des conteneurs.
- **Docker Compose** : Outil pour définir et gérer des applications multi-conteneurs Docker.
- **Adminer** : Outil de gestion de base de données en ligne.

## Prérequis

- Docker installé sur votre machine.
- Docker Compose installé sur votre machine.

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/Adama55/projetDocker.git
   cd nom-de-votre-projet
