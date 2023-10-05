# Cours Git EFREI
## GP01
### 05/10/2023

Ceci est notre premier fichier README.md.

## Points vus le 05/10/2023
Nous avons vu les commandes terminal suivantes :

1. pwd : permet de savoir o� l'on se trouve au sein de l'arborescence du syst�me de fichiers
2. ls : (options -a, -l, -A) permet d'afficher la liste des dossiers et fichiers ainsi que les droits qui leurs sont li�s
3. cd : permet de se d�placer dans l'arborescence du syst�me de fichiers (. = dossier courant, .. = dossier parent)
4. mkdir : permet de cr�er un dossier
5. touch : permet de cr�er un fichier
6. rmdir : permet de supprimer un dossier
7. rm : permet de supprimer un fichier / dossier
8. cat <file_name> : afficher le contenu d'un fichier

Nous avons vu les commandes Git suivantes :

1. git --version : afficher la version de Git actuellement install�e sur votre machine
2. git init : initialiser un projet Git � l'emplacement o� l'on se trouve dans l'arborescence du syst�me de fichiers
3. git config (user.email, user.name) : configurer les informations relatives � l'auteur
4. git status : afficher les informations concernant l'�tat du d�p�t Git local
5. git add [file]... : ajouter un ou plusieurs fichiers / dossiers � l'historique de suivi de Git
6. git commit -m "[message]" : cr�er un commit � partir des fichiers ajout�s via la commande "git add" en lui attribuant un message
7. git  commit --amend -m "[message]" : modifier le message du dernier commit
8. git restore --staged [file]... : retirer un ou plusieurs fichiers / dossiers de la liste des fichiers � commit
9. git rm --cached [file]... : retirer un ou plusieurs fichiers / dossiers de l'historique de suivi de Git
10. git reset [--soft, --hard] <commit_number> : revenir � un �tat pr�c�dent du code (au niveau du commit mentionn� dans <commit_number>)
11. git log [--oneline] : afficher la liste des commits de la branche de travail actuelle
12. git branch -M <nom_actuel> <nouveau_nom> : renommer une branche
13. git restore <file_name> : annuler les modifications apport�es sur un fichier depuis le dernier commit
14. git diff [<commit_number>] : afficher la liste des derni�res modifications n'ayant pas fait l'objet d'un commit ou les diff�rences entre l'�tat actuel du code et celui d'un commit pr�c�dent
15. git ls-files : affiche la liste des fichiers actuellement suivi par Git pour le projet en cours
16. git update-git-for-windows : met � jour Git vers la derni�re version en date

