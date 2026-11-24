| Contexte et version | Ce que je cherche a faire | Commande pour le faire | Message d'erreur | Ce que j'ai essayé | Ce que j'ai compris de mes recherches |
| - | - | - | - | - | - |
| Tout début | Créer le dépôt | git init | Aucun | git init | Tant qu'il n'y a pas de dépôt, je peux réessayer tant que je le souhaite |
| Voir si tout fonctionne | Voir si il n'y a aucune erreur | git status | fatal: detected dubious ownership in repository | Rechercher la solution sur le site de Git | Par sécurité, il bloque le chemin il faut donc qu'on le reconnaisse pour fonctionner |
| Définir le nom et le mail | git config user.name [nom] / git config user.email [email] | Aucun | Rien | le changement de nom se fait dans le terminal |
| Mettre en attente le fichier | Déposer un fichier | git add | Aucun | git add | git add met le fichier "en attente", il permet aussi de commit plusieurs fichiers en même temps |
| Déposer les fichier | Déposer un fichier | git commit | Je sais pas | Je sais pas | git commit répertorie les fichiers mis 'en attente" avec git add |
| système de branches | Découper mon projet en "sous-projets" | git branch [nom de la branche] (-c pour la selectionner directement) | Aucun | git branch -c test | le -c n'est pas obligatoire, c'est pour eviter de faire 2 commandes |
| Changer de branche | Ajouter une version à un projet en perticulier | git switch [nom de lma branche] | Aucun | get switch test | Quand on donne les bons noms on peut vite se retrouver |
| Regroupper les branches | regroupper des projets ensemble | git merge [nom de l'autre branche] | Aucun | git merge test | Merge relie uniquement les branches et crée une nouvelle version |
| Ajouter le commit d'une branche sur une autre | coller 2 branches | git rebase [nom de la branche à rejoindre] | Aucun | git rebase test | Attention à ne pas s'embrouiller dans les noms |
| Supprimer une branche | supprimer une branche | git branch -d [nom de la branche] | Aucun | git branch -d docs/objectifs | Toujours faire un git [commande] --help et aussi chercher dans la documentation pour trouver la solution |
| Ajouter les fichers au dépôt distant | ajouter mes fichiers | git push -u [nom] | Aucun | git push -u origin [nom de la branche] | le git push ajoute nos fichiers comme on l'a fait en local |
| copier le dossier github en local | Recupérer le dossier | git clone [lien] | Aucun | git clone [lien du dossier equipe] | git clone 'telecharge' le dossier, il faut le verifier et surtout ne pas prendre les dossier de n'importe qui et n'importe comment |
