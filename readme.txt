Premiers Pas

-Lancer GitBash
Aller chercher le lecteur...
$ cd C:
...puis descendre dans les dossiers...
$ cd wamp64
...jusqu'à arriver au fichier souhaité.
$cd www

A la fin j'ai bien mon chemin = /c/wamp64/www

Je peux aussi faire clic-droit sur "Git Bash here" dans mon dossier destination, via l'explorateur windows.

<Astuce>
Appuyer sur TAB pour l'auto-complétion
ls = me montre tout le contenu du dernier fichier demandé
</Astuce>

-Cloner un repository via l'invit de commande
$ git clone [copier l'adresse https du repository]

-Voir les changements entre le repository et mon fichier local
$ git status

-Ajouter des fichiers dans un 'paquet' pour faire un commit
$ git add [nom du fichier.extension]

-Fermer le 'paquet' = Faire le commit
$ git commit -m[inscrire un message pour expliquer le commit]

-Envoyer le 'paquet' = Faire un push
$ git push origin master (master = nom de la branche principale)