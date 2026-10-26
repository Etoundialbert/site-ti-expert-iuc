# Guide de contribution

Méthode GitHub Flow, la même que celle vue en cours.

1. `main` contient toujours une version qui fonctionne. On n'y pousse jamais directement.
2. Chaque membre travaille sur sa branche : `git switch feature/<prénom>-<page>`.
3. Petits commits, un par idée, au format Conventional Commits :
   - `feat:` nouveau contenu ou nouvelle section ;
   - `style:` mise en forme, sans changement de contenu ;
   - `fix:` correction ;
   - `docs:` documentation ;
   - `chore:` tâche technique.
4. `git push -u origin feature/<prénom>-<page>`, puis ouverture d'une Pull Request vers `main`.
5. Un autre membre relit, commente et approuve. On fusionne ensuite avec « Merge pull request ».
6. `git switch main` puis `git pull` pour récupérer le travail des autres.

## Avant de proposer une Pull Request

- La page s'affiche correctement sur ordinateur et sur téléphone.
- Les liens fonctionnent et la navigation clavier est possible.
- Les textes sont relus et ne contiennent pas d'information inventée.
