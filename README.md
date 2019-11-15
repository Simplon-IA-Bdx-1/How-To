# How-To

*Bonnes pratiques et Tips pour l'utilisation de l'organisation*

## Création de repo

On peut créer un repo directement dans l'oragnisation. Pour s'y retrouver voici une nomenclature de nommage:

- /nom-du-projet-user

## Repos sur compte perso et sur orga

On peut créer un repo en local et le pousser sur deux remotes distantes:

- `git add remote nom-de-la-remote url/compte/perso`
- `git add remote nom-de-l-autre-remote url/de/l/orga`

Par exemple `git add remote origin git@github.com:nicoOkie/mes-notes.git`
et `git add remote orga git@github.com:Simplon-IA-Bdx-1/mes-notes-nicookie.git`

on peut ensuite choisir le remote sur lequel on pousse:

- `git push origin master`
- `git push orga master`

## Un problème ?

On peut utiliser l'onglet issues de ce repo pour poser une question ou signaler un problème
