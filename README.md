# Projet Symfony

Ce projet est une application Symfony qui fonctionne avec Docker. Voici comment le mettre en marche pour les environnements de développement et de préproduction.

---

## Pour commencer

## Initialisation du projet

1. **A la racine du projet** executer la commande suivante :

   ```sh
   docker-compose run composer install

   ```

## Environnement de développement (environement_dev)

### Démarrage

1. **Naviguez** vers le dossier `environement_dev` :

   ```sh
   cd environement_dev
   ```

2. **Démarrez** les containers avec Docker Compose :
   ```sh
   docker-compose up
   ```

### Accès

- L'application est accessible à l'adresse : [http://localhost:8000](http://localhost:8000)

---

## Environnement de préproduction (environement_preprod)

### Démarrage

1. **Naviguez** vers le dossier `environement_preprod` :

   ```sh
   cd environement_preprod
   ```

2. **Démarrez** les containers avec Docker Compose :
   ```sh
   docker-compose up
   ```

### Accès

- L'application est accessible à l'adresse : [http://localhost:80](http://localhost:80)

---
