# Répartition du travail

ETOUNDI Albert a créé le dépôt sur `main` (structure, styles communs, squelettes des pages), puis une branche a été créée pour chaque travail.
Chaque membre modifie uniquement ses propres fichiers.

| Membre | Branche | Fichiers | Commits |
|--------|---------|----------|---------|
| ETOUNDI Albert | `feature/albert-accueil` | `index.html`, `css/accueil.css` | héros, domaines, l'IUC en bref, démarche, appel à l'action |
| MEMBOU Maxime | `feature/maxime-formations` | `formations.html`, `css/formations.css` | niveaux, domaines, tableau des outils, modalités |
| MEMBOU Maxime | `feature/maxime-contact` | `contact.html`, `css/contact.css` | coordonnées, formulaire, accès |
| NZOUAPET Lena | `feature/lena-vie-etudiante` | `vie-etudiante.html`, `css/vie-etudiante.css` | projets, outils, débouchés, conseils |
| NZOUAPET Lena | `fix/lena-navigation-active` | les quatre pages, `css/base.css` | page courante signalée dans le menu |
| NZOUAPET Lena | `docs/lena-journal-des-changements` | `CHANGELOG.md` | journal de la version 1.0.0 |

## Éléments communs

- `css/base.css` : modifié uniquement par une branche dédiée, après accord du groupe.
- En-tête et pied de page : identiques dans les quatre pages. Toute modification doit être reportée dans chacune.

## Chaque membre peut compléter sa branche

Idées de commits supplémentaires, à faire avec son propre compte GitHub :

- relire et corriger les textes de sa page (`docs:` ou `fix:`) ;
- vérifier l'affichage sur téléphone et ajuster le CSS (`style:`) ;
- compléter le contenu avec des informations validées auprès du département (`feat:`).
