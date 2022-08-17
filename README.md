# README

## Contexte

Notre fantastique propriétaire de produit a une idée merveilleuse, étonnante et révolutionnaire... il veut construire une nouvelle application Todo.
Il a une bonne idée du comportement de l'application et vient avec un backlog contenant les user stories suivantes :

## User stories


### 1 : Liste de mes TODOs

#### Description :

En tant qu'utilisateur, je souhaite lister mes todos actuels.

#### Critères d'acceptation :

-   [x] Chaque todo pourrait avoir, au minimum, un état et un titre associés.
-   [ ] Quelques todos codés en dur seront initialisés dans ce contexte pour démontrer l'outil.

#### 2 : Changer l'état d'une TODO

#### Description :

-   [x] En tant qu'utilisateur, je souhaite changer l'état d'un todo en cochant une "case".

### Critères d'acceptation :

-   [x] Lorsqu'une tâche est terminée, elle doit être placée en bas de la liste et doit être barrée.

### 3 : Détailler une TODO

### Description :

En tant qu'utilisateur, je souhaite afficher un de mes todo dans une vue séparée ou dédiée.

-   [x] Cette tâche contiendra son titre et une description (qui est une nouvelle information non affichée dans la vue précédente).

### Critères d'acceptation :

-   [x] On peut cliquer sur un todo (par n'importe quel moyen) pour accéder à la vue détaillée du todo.
-   [x] Le todo est accessible via une URL unique.

### 4 : Ajouter une nouvelle TODO

### Description :

En tant qu'utilisateur, je souhaite ajouter un nouveau todo dans ma liste.

### Critères d'acceptation :

-   [x] Le titre de la todo est obligatoire
-   [x] La description du todo peut être vide
-   [x] La nouvelle tâche doit être en haut de la liste des tâches.
-   [x] Vous êtes libre de choisir le design / l'interaction

# Environnement technique

Vous travaillez dans la WebFactory qui fournit les recommandations techniques suivantes :

- L'application backend doit être basée sur vos langages préférés (Java , JS, PHP, Python, Go, C++, ...) et/ou Framework (Spring Boot, Django, .NetCore , NodeJS, Angular, React, ...).
- Garder l'interface utilisateur simple
- La qualité du code e|sort((a, b) => a.id <=> b.id)|st très importante, donc tout le code doit être couvert par des tests unitaires.
- Chaque user story doit être réalisée dans son propre commit sur master
- Le propriétaire du produit est curieux et aime lire le code de l'application sur Github et le tester via les pages Github.
- L'application doit avoir un backend simulé et y stocker tous les todos (extension de HttpXhrBackend).

# Bonus

Vous pouvez ajouter toute nouvelle fonctionnalité dans ce merveilleux projet si vous le souhaitez, afin de satisfaire votre PO 😉.

# Installer l'application : 

1. Cloner le repo
2. Copier le .env en .env.local
3. Modifier la ligne correspondante à votre gestionnaire de base de données (MySQL, PostGreSQL,...) et renseigner les infos (mdp, utilisateur...).
4. Créer la base de données.
5. Ajouter des données
