---
Name: Db.MainPage
Title: Mise à disposition des données du site
LastModified: 2020-05-05 14:25
---

Dans un but d'ouverture communautaire, Pathfinder-fr met à disposition les données extraites du wiki des règles Pathfinder dans des formats adaptés à la réutilisation.

Ces données restent soumises à la licence d'origine des informations, à savoir la [Licence OGL](./../OGL.md) ainsi que la licence de contribution Pathfinder-Fr (voir le paragraphe "licence" ci-dessous).

Pour tout commentaire ou discussion, je vous invite à vous rendre sur [le sujet dédié du forum](http://www.pathfinder-fr.org/Forum/yaf_postsm160358_Export-du-wiki.aspx).

<nav class="wiki-toc"></nav>

Il existe trois grands formats pour ces données :
1. Un export brut des pages du wiki.
1. Un format brut XML des pages du wiki.
1. Un format travaillé et normé (xml et csv) basé une analyse des données brutes XML.

Elles sont mise à jour de manière hebdomadaire chaque dimanche soir, à l'aide de trois outils (MigratorWiki, WikiXmlExport et WikiExportParser).

[image||{UP(Db.MainPage)}WikiDbWorkflow.png]

### Wiki au format brut
Les pages du wiki sont tout d'abord extraites au format Wiki, brut, avec un fichier par page, dans un repository Git : [https://gitlab.com/pathfinder-fr/pf1-screwturnwiki](https://gitlab.com/pathfinder-fr/pf1-screwturnwiki).

Ce format d'export est à privilégier, il vous permet simplement d'avoir une copie locale des fichiers du wiki, en utilisant Git, qui sera simple de synchroniser avec les mises à jour publiées.

Les formats qui suivent seront remplacés et/ou supprimés.

### Wiki au format HTML
Les pages du wiki sont aussi extraites au format HTML dans deux formats.
Ces fichiers sont à l'attention de ceux qui souhaitent avoir le wiki dans un format compatible avec un navigateur mais disponible hors-ligne. Certaines fonctionnalités ne seront pas disponibles cependant.

Un premier format pour [le DRP Français](http://regles-pathfinder.fr/) avec les CSS corrects : [Static.7z](http://db.pathfinder-fr.org/raw/Static.7z)

Un second format brut HTML sans aucune transformation : [RawHtml.7z](http://db.pathfinder-fr.org/raw/RawHtml.7z).

**Ce format sera à terme abandonné et ne devrait plus être utilisé.**

### Wiki au format brut XML
Les données au format brut correspondent à l'ensemble des pages du wiki Pathfinder-RPG enregistrées au format XML.

Ces données s'adressent à ceux qui souhaiteraient analyser l'ensemble des pages du wiki Pathfinder-RPG.

Elles peuvent être directement téléchargées dans [une archive WikiXml.7z (format 7zip)](http://db.pathfinder-fr.org/raw/WikiXml.7z).

Les pages sont nommées à partir du titre de la page, en supprimant les apostrophes. Les fichiers sont nommés en se basant sur le nom de la page, en remplaçant les espaces par des tirets et en mettant en majuscule la première lettre de chaque mot.

Chaque page est représenté par un élément xml `wikiPage`, contenant plusieurs éléments :

- `title` avec le titre de la page du wiki
- `categories` contenant la liste des catégories de la page du wiki. Chaque catégorie est au format `Namespace.Name` où `Namespace` vaudra la plupart du temps `Pathfinder-RPG`.
- `lastModified` avec la date de dernière modification de la page.
- `version` numéro de révision de la page du wiki
- `inLinks` liste des pages ayant des liens entrants vers cette page.
- `outLinks` liste des pages liées par cette page.
- `body` contenu de la page, au format HTML tel qu'affiché
- `raw` contenu de la page au format brut, c'est à dire utilisant la syntaxe du wiki
- `fullName` nom complet de la page

La génération du contenu body au format HTML est légèrement différente de la méthode utilisée sur le site : certains snippets sont ignorés et les liens sont remplacés par le nom de la page au format standardisé, avec une extension .html.

**[Télécharger la dernière archive WikiXml.7z](http://db.pathfinder-fr.org/raw/WikiXml.7z).**

**Ce format sera à terme abandonné, vous êtes invité à privilégier l'export GIT mentionné au-dessus.**

### Base de données Wiki
La base de données OGL se base sur une analyse du wiki brut XML pour extraire certaines données dans un format normé.

Ces données s'adressent à ceux qui souhaitent travailler sur certaines données précises du wiki (sorts, dons, monstres, etc.) dans un format normalisé.

L'outil chargé d'analyser les données brutes pour lire les éléments s'appelle WikiExportParser et le projet est hébergé sur [github](https://github.com/Pathfinder-Fr/WikiExportParser).

Cet outil évolue petit à petit pour améliorer les données extraites.

Pour l'instant, il exporte deux données depuis le wiki :
- Les sorts
- Les dons
- Les monstres

Il exporte ces données dans trois formats :
- Format XML [standardisé](https://github.com/Pathfinder-Fr/PathfinderDb.Schema)
- Format CSV, utilisable dans tout tableur (excel par exemple).
- Format JSON, utilisable surtout pour les navigateurs.

Il peut arriver que l'outil n'arrive pas à lire, comprendre et générer les données pour certaines pages du wiki, notamment si la syntaxe wiki est un peu différente des règles admises, ou si des fautes de frappes sont rencontrées.
Les utilisateurs peuvent participer à l'amélioration de l'export en modifiant les pages.

Le détail des dernières génération peut être consulté librement en ligne :
- [journal de la dernière génération des sorts](http://db.pathfinder-fr.org/Raw/spells.txt)
- [journal de la dernière génération des dons](http://db.pathfinder-fr.org/Raw/feats.txt)
- [journal de la dernière génération des monstres](http://db.pathfinder-fr.org/Raw/monsters.txt)

Pour toute question ou remarque, utilisez [le sujet dédié à ce projet](http://www.pathfinder-fr.org/Forum/yaf_postsm160358_Export-du-wiki.aspx) dans le forum ou rendez-vous sur [le site du projet](https://github.com/Pathfinder-Fr/WikiExportParser) pour proposer des améliorations ou remonter les problèmes.

#### Liens

- **[Dernière archive Db.zip](http://db.pathfinder-fr.org/raw/DbXml.zip)** contenant tous les fichiers.
- **[Site du projet](https://github.com/Pathfinder-Fr/WikiExportParser)** de l'outil WikiExportParser.
- Dernière version des **[sorts (XML)](http://db.pathfinder-fr.org/raw/spells.xml).**
- Dernière version des **[sorts (CSV)](http://db.pathfinder-fr.org/raw/spells.csv).**
- Dernière version des **[sorts (JSON)](http://db.pathfinder-fr.org/raw/spells.json).**
- Dernière version des **[dons (XML)](http://db.pathfinder-fr.org/raw/feats.xml).**
- Dernière version des **[dons (CSV)](http://db.pathfinder-fr.org/raw/feats.csv).**
- Dernière version des **[dons (JSON)](http://db.pathfinder-fr.org/raw/feats.json).**
- Dernière version des **[monstres (XML)](http://db.pathfinder-fr.org/raw/monsters.xml).**
- Dernière version des **[monstres (CSV)](http://db.pathfinder-fr.org/raw/monsters.csv).**
- Dernière version des **[monstres (JSON)](http://db.pathfinder-fr.org/raw/monsters.json).**


### Site de démonstration
Un site de démonstration a été mis en place pour avoir un aperçu de ce qu'il est possible de faire à partir des données.

Les fonctionnalités sont assez basiques, mais le but est uniquement de démontrer que c'est réalisable.

Il permet pour l'instant uniquement de parcourir dons et sorts.

**[Aller sur le site db.pathfinder-fr.org](http://db.pathfinder-fr.org/)**.

### Licence
La reprise gratuite et à but non lucratif des présents textes est autorisée pourvu qu'il soit fait expressément mention des logos et adresses web de Black Book Editions, Paizo Publishing et Pathfinder-fr.org.

Pathfinder JdR est publié selon les principes de l'[Open Game License](./../OGL.md).
