# Site du département TI Expert de l'IUC

Site web statique (HTML et CSS) qui présente le département TI Expert de l'Institut Universitaire de la Côte (IUC), à Douala.
Travail de groupe du cours **Automatisation et usine logicielle** : le but est autant le site que la qualité du dépôt Git
(branches listées, commits lisibles, Pull Requests relues).

## Pages

| Page | Fichier | Contenu |
|------|---------|---------|
| Accueil | `index.html` | Présentation, cinq domaines, l'IUC en bref, démarche pédagogique |
| Formations | `formations.html` | Niveaux, détail des domaines, outils, modalités |
| Vie étudiante | `vie-etudiante.html` | Projets, outils, débouchés, conseils |
| Contact | `contact.html` | Coordonnées, formulaire, accès |

## Structure du dépôt

```
.
├── index.html, formations.html, vie-etudiante.html, contact.html
├── css/
│   ├── base.css            styles communs (variables, en-tête, pied de page, boutons)
│   └── accueil.css, formations.css, vie-etudiante.css, contact.css
├── img/logo.svg
├── docs/                   répartition du travail, guide de contribution
└── CHANGELOG.md            journal des changements
```

Chaque membre modifie ses propres fichiers (une page et son CSS). Cela évite les conflits de fusion.

## Voir le site

Ouvrir `index.html` dans un navigateur. Pour un serveur local :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

Publication possible avec GitHub Pages : Settings, Pages, branche `main`, dossier `/ (root)`.

## Équipe et branches

| Membre | Branches | Travail |
|--------|----------|---------|
| ETOUNDI Albert (créateur du dépôt) | `feature/albert-accueil` | Page Accueil (le dépôt, les styles communs et les squelettes ont été créés sur `main`) |
| MEMBOU Maxime | `feature/maxime-formations`, `feature/maxime-contact` | Pages Formations et Contact |
| NZOUAPET Lena | `feature/lena-vie-etudiante`, `fix/lena-navigation-active`, `docs/lena-journal-des-changements` | Page Vie étudiante, signalement de la page courante dans le menu, journal des changements |

Le détail se trouve dans [`docs/REPARTITION.md`](docs/REPARTITION.md) et la méthode de travail dans [`docs/CONTRIBUTING.md`](docs/CONTRIBUTING.md).

## Sources du contenu

- Jeune Afrique, fiche de l'IUC : création en 2002, site de Logbessou, établissements du groupe.
- MINESUP, fiche de l'IUC : arrêtés de création, adresse, contacts.
- Les descriptions des domaines de TI Expert sont rédigées par le groupe à partir du cours.

Ce site est un projet pédagogique. Il n'est pas le site officiel de l'IUC.
