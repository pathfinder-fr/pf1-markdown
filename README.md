# pf1-markdown

Référentiel des contenus Markdown, gabarits de mise en page et assets statiques pour le site statique **Pathfinder-FR** (Pathfinder 1ère édition).

Ce dépôt centralise l'ensemble des données sources nécessaires à la génération du site web : le contenu rédactionnel en Markdown, les feuilles de style, les images, ainsi que les gabarits HTML.

Le site web généré et publié est consultable en ligne à l'adresse :

👉 **[https://www.pathfinder-fr.org/srd/pf1/](https://www.pathfinder-fr.org/srd/pf1/)**

---

## 📌 Origine du contenu

Le contenu textuel de ce dépôt est actuellement **généré et synchronisé automatiquement** à partir des sources brutes du wiki historique ScrewTurn hébergées sur le dépôt public :

👉 **[pathfinder-fr/pf1-screwturnwiki](https://github.com/pathfinder-fr/pf1-screwturnwiki)**

> **Note :** Pendant la phase de transition et de migration, les pages Markdown reflètent l'état converti du wiki source. À terme, ce dépôt a vocation à devenir la source de vérité éditable directement en Markdown.

---

## 📂 Structure du dépôt

```text
pf1-markdown/
├── _layouts/               # Gabarits de mise en page HTML (Liquid)
│   ├── default.liquid      # Gabarit principal pour les pages de contenu
│   └── redirection.liquid  # Gabarit pour les pages d'alias et redirections
├── .static/                # Assets statiques distribués avec le site
│   ├── css/                # Feuilles de style (wiki.css, markdown.css, custom.css...)
│   ├── js/                 # Scripts JavaScript côté client
│   ├── images/             # Images, icônes et illustrations
│   └── lib/                # Bibliothèques tierces (Bootstrap, jQuery...)
├── Pathfinder-RPG/         # Règles du jeu, classes, sorts, dons, bestiaire...
├── Golarion/               # Univers, géographie, histoire, panthéon, factions...
├── Aventures/              # Campagnes, modules, scénarios et aides de jeu
├── ADJ/                    # Aides de jeu et fiches pour le Meneur de Jeu
└── ...                     # Autres catégories et pages racine
```

### 1. Contenu Markdown (`*.md`)
Les fichiers Markdown sont organisés par dossiers correspondant aux espaces thématiques du wiki d'origine :
- **`Pathfinder-RPG/`** : Règles complètes du jeu de rôle (classes de base, de prestige, archétypes, dons, sorts, équipement, objets magiques, monstres...).
- **`Golarion/`** : Encyclopédie de l'univers de campagne (continents, divinités, nations, chronologies, organisations).
- **`Aventures/`** : Campagnes officielles (Adventure Paths), modules et conversions.
- **`ADJ/`** : Aides de jeu, tables, feuilles de personnages et ressources.

### 2. Gabarits de mise en page (`_layouts/`)
Les templates utilisent la syntaxe de templating **Liquid** (compatible Fluid) :
- **`default.liquid`** : Définit la structure HTML complète des pages (en-têtes, navigation, conteneur de contenu `{{ content }}`, bas de page avec date de révision et lien vers la source Markdown).
- **`redirection.liquid`** : Génère les pages HTML de redirection automatique pour préserver les anciens alias et URL historiques.

### 3. Assets statiques (`.static/`)
Ce dossier regroupe toutes les ressources nécessaires à la restitution visuelle :
- **`css/markdown.css`** : Règles CSS spécifiques au rendu des éléments Markdown (tableaux GFM, classes de colonnes, typographie).
- **`css/wiki.css`**, **`css/sueetie.css`**, **`css/custom.css`** : Styles thématiques et mise en page globale du site Pathfinder-FR.
- **`images/`** : Logos, bannières et illustrations associées aux articles.

---

## 🎨 Travailler sur le rendu et les styles

Ce dépôt est conçu pour être l'unique point d'entrée pour faire évoluer le rendu visuel et la mise en page du site :
- Pour ajuster le style global ou l'affichage des composants Markdown, modifiez les fichiers sous `.static/css/` (en particulier `.static/css/markdown.css`).
- Pour modifier la structure des pages générées (balises `<head>`, barre de navigation, métadonnées, footer), éditez les fichiers sous `_layouts/`.

---

## ⚖️ Mentions légales

Pathfinder et son logo sont des marques déposées de **Paizo Inc.** Les règles de jeu sont publiées sous la licence **Open Game License (OGL)**. Les textes originaux et traductions communautaires sont la propriété de leurs auteurs respectifs et de l'équipe **Pathfinder-FR**.

