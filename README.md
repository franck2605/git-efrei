# Exemple pour le cours versioning de code -l'outil Git
## EFREI 03/10/2022

# Gros titre (h1)
## Sous-titre (h2)
### Plus-petit (h3)
#### Encore plus petit (h4)
##### Toujours plus petit (h5)
###### Le plus petit (h6)

_Je suis un super paragraphe en italique_\
_avec retour à la ligne_\
**Je suis un paragraphe en gras**

| Syntax    | Description | Test  |
| :-------- | :---------: | ----: |
| Header    | Title       | Texte |
| Paragraphe exemple aligné à gauche | Texte exemple centré  |Texte exemple aligné à droite |

## Fonctionnement

Afin de pouvoir faire fonctionner ce projet, vous devrez créer, à la racine du dossier parent, un fichier secret.txt contenant les client_secret et client_key.

## Résumé matinée

| Commande | Options | Fonction |
| :------ | :-----: | :------: |
| git init | | Initialiser un projet Git |
| git config user.email | | Définir l'e-mail de l'utilisateur courant pour Git | 
| git config user.name | | Définir le nom de l'utilisateur courant pour Git |
| git status | | Afficher le statut actuel de la branche courante |
| git add | | "Stage" un ou plusieurs fichiers |
| git commit | --amend | Modifier le message du dernier commit |
| git commit | -m | Ajouter un message au commit en ligne de commande |
| git tag | [-a, -m, -d, -f] [commit or tag number] | Ajouter, supprimer ou déplacer un tag sur un commit donné |
| git show | [commit number] | Afficher les informations relatives à un commit donné |
| git diff | [file] | Afficher les changements entre maintenant et le dernier commit sur un ou tous les fichiers |
| git log | | Afficher la liste des commits sur la branche actuelle |
| git reset | --soft, --hard | Revenir à un état précédent de notre code projet |
| git ls-files | | Liste les fichiers suivis par Git |
| git rm | --cached | | Retirer un ou plusieurs fichiers de l'historique de suivi de Git |
| git restore | --staged | | Unstage un ou plusieurs fichiers |
| git branch | -M, -d, -a | Créer ou renommer une branche de travail |
| git checkout | -b | (Créer si l'option -b a été donnéeet) Se positionner sur une branche de travail |
| git merge | | Permet de fusionner l'historique Git de 2 branches |
| git remote add <alias> <branche> | -u
| git remote | -v | Lister lles différentes origines distantes |
| git push <alias> <branche> | -u (--set-upstream) | Envoi le code source et l'historique des versions sur le depôt distant mentionné.

## Création d'un compte Github

Aller sur [github] (https://github.com) et cliquer sur "Sign up" pour lancer le processus de création de compte.

## Génération d'une clé SSH
'''bash
ssh-keygen
'''

Localiser la clé publique (par défaut: C:\Users\username\.ssh\) et copier le contenu du fichier id_rsa.pub.

Aller sur github dans les paramètres du compte (icône du compte en haut à droite de l'écran d'accueil >>setting >> SSH and GPG keys >> New SSH key) et ajouter la clé nouvellement créée et copiée.