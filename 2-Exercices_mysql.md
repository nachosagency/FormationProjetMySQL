# Exercices Conception Mysql

## Exercice 1

Soit les Entités suivantes :

* Film (id, titre, realisateur)
* Acteur (id, prenom, nom)
* Cinéma (id, ville, nb_salles)
* Séance (id, horaire, salle)

### 1/ Créer les tables sous phpMyAdmin

Créer les 4 tables avec leurs colonnes et trouver les bons types

### 2 / Remplir avec quelques données de test

Ex : 2 ou 3 films, 2 acteurs par films...

### 3/ Trouver les cardinalités entre :

* Film et Acteur
* Séance et Film
* Séance et Cinéma

Et dessiner le schéma entité/association


### 4/ Créer les colonnes et/ou les tables de liens

### 5/ Créer les liens

Ajouter les valeurs dans les nouvelles colonnes ou tables.


## TP Conception SQL : Gestion d’une billetterie

En s’inspirant d’un site type Fnac Spectacles

### 1 / Créer les tables concernant les entités suivantes : Artistes, Spectacles, Lieu, Client, Compte, Commande

### 2 / Ajouter et typer les champs de votre choix (2 ou plus par table) (ex : nom, prénom, dateHeureSpectacle 2013-09-25 16:39:45, etc…)

### 3 / Créer les liens permettant les fonctionnalités suivantes

Fonctionnalités : 

*	CRUD (Create, Read, Update, Delete) Artiste (Chanteur, Humoriste, etc…)
*	CRUD Lieu (Salle, Stade, etc..)
*	CRUD Spectacle (Lien avec Artiste et Lieu)
*	Lister des spectacles par artiste et par lieu
*	Client peut commander des places de spectacles.
*	Client peut créer un compte client.

### 4 / Faire le schéma entité/association

### 5 / Remplir avec des données de test
