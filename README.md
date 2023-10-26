# Cours Git EFREI
## GP01
### 05/10/2023

Ceci est notre premier fichier README.md.

## Points vus le 05/10/2023
Nous avons vu les commandes terminal suivantes :

1. pwd : permet de savoir où l'on se trouve au sein de l'arborescence du système de fichiers
2. ls : (options -a, -l, -A) permet d'afficher la liste des dossiers et fichiers ainsi que les droits qui leurs sont liés
3. cd : permet de se déplacer dans l'arborescence du système de fichiers (. = dossier courant, .. = dossier parent)
4. mkdir : permet de créer un dossier
5. touch : permet de créer un fichier
6. rmdir : permet de supprimer un dossier
7. rm : permet de supprimer un fichier / dossier (avec l'option de récursivité -r)
8. cat / less / more <file_name> : afficher le contenu d'un fichier
9. clear : nettoyer le terminal

Nous avons vu les commandes Git suivantes :

1.  git --version (-v) : afficher la version de Git actuellement installée sur votre machine
2.  git init : initialiser un projet Git à l'emplacement où l'on se trouve dans l'arborescence du système de fichiers
3.  git config (user.email, user.name) : configurer les informations relatives à l'auteur
4.  git status : afficher les informations concernant l'état du dépôt Git local
5.  git add [file]... : ajouter un ou plusieurs fichiers / dossiers & l'historique de suivi de Git
6.  git commit -m "[message]" : créer un commit à partir des fichiers ajoutés via la commande "git add" en lui attribuant un message
7.  git commit --amend -m "[message]" : modifier le message du dernier commit
8.  git restore --staged [file]... : retirer un ou plusieurs fichiers / dossiers de la liste des fichiers à commit
9.  git rm --cached [file]... : retirer un ou plusieurs fichiers / dossiers de l'historique de suivi de Git
10. git reset [--soft, --hard] <commit_number> : revenir à un état précédent du code (au niveau du commit mentionné dans <commit_number>)
11. git log [--oneline] : afficher la liste des commits de la branche de travail actuelle
12. git branch -M <nom_actuel> <nouveau_nom> : renommer une branche
13. git restore <file_name> : annuler les modifications apportées sur un fichier depuis le dernier commit
14. git diff [<commit_number>] : afficher la liste des dernières modifications n'ayant pas fait l'objet d'un commit ou les différences entre l'état actuel du code et celui d'un commit précédent
15. git ls-files : affiche la liste des fichiers actuellement suivi par Git pour le projet en cours
16. git update-git-for-windows : met à jour Git vers la dernière version en date
17. git tag : afficher la liste de tous les tags du projet
18. git tag -a <numero_tag> -m "<message_tag>" <commit_number> : ajouter un tag avec un numéro de version et un message sur un commit donné
19. git tag -d <numero_tag> : supprimer un tag donné
20. git show <commit_number> | <numero_tag> : afficher les détails d'un commit à partir de son numéro ou du numéro de tag qui lui est associé
21. git branch <nom_branche> : créer une nouvelle branche à partir de la branche de travail actuelle
21. git branch -d <nom_branche> : supprimer la branche locale spécifiée
22. git checkout <nom_branche> : se positionner sur la branche spécifiée
23. git checkout -b <nom_branche> : créer une nouvelle branche puis se positionner dessus
24. git merge <branche_a_fusionner> : fusionne les modifications de la branche spécifiée dans la branche de travail actuelle
25. git remote add <nom_origine> <url_depot_distant> : ajoute un alias <nom_origine> pour l'url d'un dépôt distant <url_depot_distant>