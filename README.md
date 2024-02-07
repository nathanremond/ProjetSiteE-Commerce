# Projet Site E-Commerce

## Membres

- [Nathan Remond](https://github.com/nathanremond) - Responsable CI/CD et git/github
- [Jilen Sebamalainathan](https://github.com/Jilen5) - Designer et Intégrateur Frontend
- [Kave Thorkghashghaie](https://github.com/Kave2005) - Développeur JavaScript
- [Yvan Guifo Fodjo](https://github.com/YvanGuifo) - Professeur

## Description

Notre site Web est une plateforme de location en ligne pour des voitures d'occasion. Notre site contiendra une page d'accueil et une barre de recherches pour permettre aux internautes de naviguer facilement sur le site web, une page catalogue pour regarder les voitures disponibles et une page panier pour louer une voiture.

## Gestion des branches

Les branches suivantes sont à utiliser :

- **feature/{feature-name}** : Pour les nouvelles fonctionnalités
- **bugfix/{bug-name}** : Pour les corrections de bugs

La branche **main** est protégée des pushs directs. Pour modifier cette branche, il faut créer une pull request.

Le paramétrage de la protection est visible [ici](https://github.com/nathanremond/ProjetSiteE-Commerce/settings/branch_protection_rules/46560820).

## Gestion des commits

Création d'un fichier **CODEOWNERS** pour protéger les dossiers et fichiers de répertoire .github. 

S'il y a des changements sur des dossiers ou fichiers appartenant au répertoire .github, l'utilisateur notifié dans le fichier CODEOWNERS sera ajouté à la review de la pull request.

Les commits suivants sont à utiliser :

- **feat:{commit-name}** : Pour les nouvelles fonctionnalités.
- **fix:{commit-name}** : Pour les corrections de bugs.
- **docs:{commit-name}** : Pour les ajouts dans la documentation.

D'autres formes de commits [ici](https://www.conventionalcommits.org/en/v1.0.0/).

## Gestion des issues

Chaque tâche doit être décrite dans une issue et doit être assignée à un membre de l'équipe lorsqu'elle est prise en charge.

Une branche doit être créée à partir de l'issue pour savoir quelle tâche est assignée à cette branche.

Lorsque l'issue est résolue, elle doit être fermée.

Pour créer une nouvelle fonctionnalité, mettre le label **enhancement**.
Pour créer un bug, mettre le label **bug**.

## Revue de code

Lorsque le développement sur la branche est terminé, il faut faire une pull request avec un titre et une description des changements.

Celle-ci devra être vérifiée par quelqu'un pour être mergée.

## Organisation du code source

- app: Contient les fichiers de l'application.
- docs: Contient la documentation utilisateur.

## Intégration continue

Un workflow **ci** pour executer les tests unitaires. Il se déclenche lorsqu'il y a une demande de pull request. Il faut utiliser une commande pour déclencher les tests.

## Déploiement continu

Un workflow **cd** pour le déploiement. Il se déclenche lorsqu'il y a un push sur la branche main.
Il faut utiliser une commande pour déclencher le déploiement.

## Documentation utilisateur

[Documentation utilisateur](/docs/home.md)