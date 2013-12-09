Démarrer un nouveau projet Github à partir de ce repository
===========================================================

(version de Symfony : 2.4.0)

1) Créer un nouveau projet sur Github
----------------------------------

2) Dans le terminal
----------------

Naviguer jusqu'au dossier dans lequel on veut créer le projet, et saisir les commandes suivantes :

    > git clone [URL_du_repository] [Nom_du_nouveau_projet]
    > cd [Nom_du_nouveau_projet]
    > git remote remove origin
    > git remote add origin [URL_du_nouveau_projet]
    > git push -u origin master
