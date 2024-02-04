# Projet Site E-Commerce

## Membres

- [Nathan Remond](https://github.com/nathanremond) - Responsable CI/CD et git/github
- [Jilen Sebamalainathan](https://github.com/Jilen5) - Designer et Intégrateur Frontend
- [Kave Thorkghashghaie](https://github.com/Kave2005) - Développeur JavaScript
- [Yvan Guifo Fodjo](https://github.com/YvanGuifo) - Professeur

## Description

§ Créa9on du repository GitHub : Commencez par créer un repository GitHub pour le projet. Choisissez
un nom significa9f et ajoutez une descrip9on détaillée du projet. Assurez-vous que le repository est
ini9alisé avec un fichier README.

## Gestion des branches

Les branches suivantes sont à utiliser :

- **feature/{feature-name}** : Pour les nouvelles fonctionnalités
- **bugfix/{bug-name}** : Pour les corrections de bugs

La branche **main** est protégée des pushs directs. Pour modifier cette branche, il faut créer une pull request.

Le paramétrage de la protection est visible [ici](https://github.com/nathanremond/ProjetSiteE-Commerce/settings/branch_protection_rules/46560820).

## Gestion des commits

ges9on de version avec des commits descrip9fs.
La ges9on efficace du code source est essen9elle pour assurer la collabora9on harmonieuse au sein de l'équipe
de développement. Dans ceTe étape, nous meTrons en place un système de contrôle de version avec
Git/GitHub.
§ Bonnes pra9ques de ges9on de version : Enforcez des bonnes pra9ques de ges9on de version.
Encouragez des messages de commit descrip9fs et informa9fs. U9lisez des branches spécifiques pour
chaque fonc9onnalité ou correc9f.

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