https://git-scm.com/book/fr/v1/Les-bases-de-Git-D%C3%A9marrer-un-d%C3%A9p%C3%B4t-Git


créer un nouveau commit

Gestion des commits

git pull

Met à jour votre dépôt local (à faire avant de commencer à modifier des fichiers pour être sûr de travailler sur leurs dernières versions et avant tout commit pour éviter les éventuels conflits avec des modifications effectuées par d'autres utilisateurs entre temps).

git commit <fichier1> <fichier2>

Crée un commit contenant fichier1 et fichier2. Ces fichiers auront dû être au préalable ajoutés au dépôt avec la commande git add.

("Il s'agit de la validation d'une transaction. Après avoir commis la transaction, les informations traitées par cette transaction seront disponibles pour les autres sessions, c'est-à-dire pour toute autre transaction éventuelle."http://fr.wikipedia.org/wiki/Commit )

git commit -a

Crée un nouveau commit contenant tous les changements effectués sur les fichiers (git add n'est donc pas nécessaire avant un commit -a). 

