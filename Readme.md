# Quete Docker 3

## Description

Créer une app Node server et react client et les utiliser avec docker compose

## Prérequis

- Docker doit être installé sur votre machine.

## Comment Démarrer en Mode Développement

1. Clonez le dépôt :

    ```bash
    git clone https://github.com/votre-utilisateur/votre-projet.git
    ```

2. Accédez au répertoire du projet :

    ```bash
    cd votre-projet
    ```

3. Créez un fichier `.env` à la racine du projet et ajoutez les variables d'environnement nécessaires. Consultez le fichier `.env.example` pour les variables requises.

4. Exécutez la commande suivante pour démarrer l'application en mode développement :

    ```bash
    docker-compose -f docker-compose.dev.yml up --build
    ```

    Cela construira les images Docker et démarrera les services nécessaires.

5. Accédez à l'application dans votre navigateur :

    - Client (Front-end): [http://localhost:8080](http://localhost:8080)
    - Server (Back-end): [http://localhost:8081](http://localhost:8081)

6. Pour arrêter l'application, utilisez la combinaison de touches `Ctrl + C` dans le terminal où Docker Compose est en cours d'exécution.


