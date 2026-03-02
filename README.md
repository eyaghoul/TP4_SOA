# TP4 : Création d’une API Restful avec Express JS

## Description

Ce projet est un exemple d'application backend en **Node.js** utilisant **Keycloak** pour l’authentification et la gestion des utilisateurs.  
Il illustre l’intégration d’un serveur d’authentification OpenID Connect avec des routes sécurisées et la persistance des données dans une base SQLite.

## Fonctionnalités

- Gestion des utilisateurs avec Keycloak (realm, client, mot de passe, rôles)
- Routes Node.js sécurisées par Keycloak
- Base de données SQLite pour stocker des informations spécifiques à l’application
- Documentation OpenAPI pour l’API


## Etape 5 : 
###  Test des Routes

 **GET** : récupérer les données.
 ![Exemple GET](./img/getpersonnes.png)
resultat : 
![response GET](./img/get1.png)

GET Personne par ID : 
![Exemple GET par ID ](./img/getp1.png)

  - **POST** : ajouter de nouvelles données (ajoutez les données dans l’onglet `Body` → `raw` → `JSON`).
![Exemple post  ](./img/post.png)
resultat : 
![response POST](./img/postresult.png)

  - **PUT** : mettre à jour des données existantes (également via `Body` → `raw` → `JSON`).

  ![exemple put](./img/put.png)

  - **DELETE** : supprimer des données.
  ![exemple delete](./img/delete.png)

###  cas de données incorrectes 
![exemple erreur 1](./img/error1.png)
![exemple erreur 2](./img/error.png)
![exemple erreur 3](./img/error3.png)

## Etape 6 : 
 1. Création d' un realm.

 2. configuration d'un client avec les paramètres nécessaires.
 ![creation client](./img/creation_client.png)
3. creation des utilisateurs pour tester.
    ![creation user](./img/user.png)
4. Testez les routes sécurisées avec Postman.
## Etape 7 :
 ![swagger](./img/swagger.png)