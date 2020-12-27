# PFE (HealthyFood)

Des milliers de personnes sont à la recherche de recettes basées sur des caractéristiques nutritionnelles positives.

Mon objectif serait celui de concevoir un réseau social dans lequel plusieurs personnes pourraient se voir proposer des plats sains grace à des personnes étant dans le milieu du domaine de la santé en tenant compte des caractéristiques nutritives d'un utilisateur. 

A l'inscription, les personnes devront fournir une série d’informations personnelles (taille, âge,…) afin de permettre une inscription correcte et ensuite profiter de l'application à son maximum.


## Le public cible

Le public ciblé pour cette application est assez vaste, je dirais que ce seront les sportifs en général (amateurs et haut niveau) et les personnes voulant garder une alimentation correcte.


## Context

Je pratique du sport depuis plusieurs années, notamment de la course, et au fur et à mesure du temps, je me suis rendu compte que la nourriture représentait plus de 80% des sacrifices permettant d’atteindre nos objectifs caloriques. 

C’est pour cette raison, que j’ai décidé de concevoir une application basée sur la nourriture et non sur les mouvements. 

L’idée principale est de d’abord créer son propre profil (poids, taille, âge,…) pour ensuite permettre à chacun de voir les plats alimentaires les plus adaptés et surtout ne pas dépasser un certain poids calorique hebdomadaire.


## L'utilisateur peut avoir :

- Compte normal
- Compte professionnel (domaine de la santé, cuisinier,...)


## L'utilisateur **normal** doit pouvoir :

Connexion / inscription ;

    - Se connecter (email - mot de passe) 
    - Se souvenir du compte
    - S'inscrire et fournir une série d’informations personnelles 
    
    Etape 1 : Choix entre - perdre du poids
                          - se muscler
    Etape 2 : Quel poids atteindre ?
    Etape 3 : Poids actuel
    Etape 4 : Age actuel
    Etape 5 : Sexe (2 pictogrammes)
    Etape 6 : Taille (Picker) 
    Etape 7 :(pseudo, email, mot de passe (8 caractères,1 majuscule)
    - Mot de passe oublié ? / Compte professionnel ?


Paramètres ;

    - Gérer son compte :
                      - Changer son mot de passe (vérification via mail) 
                      - Son email
                      - Son avatar éventuel
                      - Son progrès avec graphique 
                      - Ses objectifs : 
                      
                      - (se muscler / perdre du poids)
                      - Calories necessaire hebdomadairement (déjà calculés)
                      MOYEN D'EDITER LES OBJECTIFS
    
  
Accueil ;

    - Filtrer si (déjeuner, diner, souper) -> filtrer les recettes avec des aliments désirer (carottes, brocolis, ...)
    - Pouvoir mettre un like et mettre en favoris la recette auto
    - Pouvoir mettre la recette dans "la nourriture à manger"(picto nourriture) -> 2h après -> envoyer une notification -> "N'oublie pas de manger le plat Blablabla pour ton alimentation !"
    
Voir les plats sur le fil d'actualité à la manière de Pinterest avec comme informations (la photo du plat, le nom, le poids calorique, les j'aimes) 
 -> au clique de la recette avoir comme informations
  
    - Photo du plat
    - Rapport calorique du plat
    - Nombre de j'aimes (coeur et chiffre)
    - Le temps de preparation
    - Mettre une description dans laquelles se trouve les étapes
    - Lister les ingredients avec la quantité de ceux-ci
   
    - Regarder si la recette ne dépasse pas le rapport caloriques de l'utilisateur, si oui -> message, si non -> ca ajoute au rapport calorique
    - Pouvoir mettre la recette dans "la nourriture à manger"(picto nourriture) -> 2h après -> envoyer une notification -> "N'oublie de manger le plat Blablabla pour ton alimentation !"
    - Partager par BlaBlaBla avec sa photo de profil -> Au clique sur la photo de profil, 
    vois son nom, photo de profil, description, année(s) de pratique(s) dans le domaine de la santé, job en question, un site web
 


## Menu 

- Accueil (voir toutes les recettes)
- Recette(s) sauvegardée(s)
- Paramètres 
---
---
---




## L'utilisateur __professionnel__ doit pouvoir :

Connexion / inscription ;


    - Se connecter 
    - Se souvenir du compte
    - S'inscrire et fournir une série d’informations personnelles (email, mot de passe (8 caractères,1 majuscule)), nom, (un site web), dans quel domaine de santé travaillez-vous ? ,combien de temps est pratiqué le domaine de santé) 
    - Mot de passe oublié ? / Un compte personnel ?

D'abord choisir s'il souhaite ;
 
    - Directement créer des recettes
    - Personnaliser son profil
    - Aller sur la page d'accueil

### Partager des recettes

Partage (obligatoire);
       
    - Il pourra intégrer une photo principale
    - Mettre le rapport calorique
    - Voir le nombre de j'aimes (coeur et chiffre)
    - Le temps de préparation
    - Mettre une description dans laquelles se trouve les étapes
    - Lister les ingredients avec le nombre de ceux-ci
    - Si facile à préparer 


### Personnaliser son profil

Modifier le profil ;

    - Photo de profil
    - Nom affiché
    - Nom d'utilisateur
    - Description
    - Url du site web
    - Numéro de téléphone
    
Paramètres du compte ;

    - Adresse mail
    - Modifier le mot de passe
    - Pays / langues
    - Identité du genre
    - Domaine de santé
    
## Accueil

    - Filtrer si (déjeuner, diner, souper) -> accés aux aliments -> filtrer les recettes avec des aliments désirer
    - Pouvoir mettre un like et sauvegarder la recette auto
    - Pouvoir mettre un(des) exemple(s) de recette(s)
    
## Menu 

- Accueil (voir toutes les recettes)
- Ajouter de(s) recette(s)
- Paramètres 

---
---
---

# Base de données

## Informations basique

Y integrer ;

- Une dizaine de recettes
- Une dizaine d'utilisateurs
- Une vingtaines d'aliments avec leur rapports


## Notifications

- Pour chaque inscription, une notification sera envoyée à l'adresse mail.
- Chaque changement de statut sera également soumis à une notification. 
- Chaque like reçu sera également soumis à une notification. 

## Badges / récompenses

À 10 j'aimes d'une recette -> accumulation (50,100,...)

À 10 recettes sauvegardés -> accumulation (50,100,...)

À 10 recettes réalisés -> accumulation (50,100,...)

À la personnalisation de son profil

À l'inscription

---

SI COMPTE PROFESSIONNEL

À l'ajout d'une recette -> accumulation (5,10,...) -> si 10 recettes ajoutées -> possibilité d'intégrer une annonce


### Annonces -> professionnel

Le professionnel a une possibilité de se "vendre" via une description - un lien - numéro de téléphone# pfe# HealthyFood
