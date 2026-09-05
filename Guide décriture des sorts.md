---
Name: Guide décriture des sorts
Title: Guide d'écriture des sorts
LastModified: 2019-09-10 21:03
---

L'écriture des sorts dans le wiki doit respecter autant que possible des règles fixes pour standardiser leur format.

Ce guide a pour but de permettre à quiconque de participer à la rédaction d'un sort dans le Wiki sans faire d'erreur de format.


@@**École** [[nom_école]] ([[branche_école]]) <nowiki>[</nowiki>[[registre]]<nowiki>]</nowiki> qsdqsd @@

Voici tout d'abord un exemple complet, que nous allons ensuite décrire partie par partie :

@@**École** [[nom_école]] ([[branche_école]]) <nowiki>[</nowiki>[[registre]]<nowiki>]</nowiki>; **Niveau** [[classes]] 1, [[sorcière]] 1  

**Temps d’incantation** 1 [[action simple]]  

**Composantes** [[Composantes|V, G]]  

**Portée** courte (7,5 m + 1,5 m/2 [[niveau|niveaux]]) (5 {s:c} + 1 {s:c}/2 [[niveau|niveaux]])  

**Cible** un humanoïde  

**Durée** [[Présentation des sorts#DUREE|concentration]] + 2 [[round|rounds]]  

**Jet de sauvegarde** [[Volonté]] pour [[Présentation des sorts#JETSDESAUVEGARDE|annuler]] ; **Résistance à la magie** oui ([[Présentation des sorts#JETSDESAUVEGARDE|inoffensif]])

Description...@@

### Règles générales

On distingue deux parties : la partie technique et la partie description.

La partie technique correspond au début du sort, jusqu'à la première ligne vide.
La description est constituée de tout ce qui se trouve ensuite.

### École et niveaux

La première ligne de la partie technique contient l'école du sort, suivi des niveaux de classes nécessaires pour pouvoir connaître le sort.

La ligne débute toujours par le texte "École" en gras (à l'aide des 3 apostrophes) : `**École**`.

On donne ensuite un lien vers l'école du sort en utilisant le nom directement comme lien. Le nom de l'école doit rester en **minuscules**. Exemple : `[[enchantement]]`. L'école divination est un cas à part, car la page "divination" correspond au sort du même nom. L'école est accessible via la page "école divination".

Les écoles possibles sont donc les suivantes :
- `[[abjuration]]`
- `[[école divination|divination]]`
- `[[enchantement]]`
- `[[évocation]]`
- `[[illusion]]`
- `[[invocation]]`
- `[[nécromancie]]`
- `[[transmutation]]`
- `[[universelle]]`

#### Branches

Comme décrit dans la [[Pathfinder-RPG.présentation des sorts|présentation des sorts]], les sorts peuvent aussi appartenir à une des branches d'une école.

On indique la branche éventuelle entre parenthèses, après l'école, et dans une lien. Exemple : `[[enchantement]] ([[charme]])`

Comme pour les écoles, certains nom de branches désignent des pages déjà utilisées. On préfixe alors le nom de la branche du mot "branche". La liste des liens de branches est donc la suivante :
- `[[branche scrutation|scrutation]]` (de l'école divination ; la page scrutation renvoie au sort)
- `[[charme]]` (de l'école enchantement)
- `[[coercition]]` (de l'école enchantement)
- `[[branche chimère|chimère]]` (de l'école d'illusion)
- `[[fantasme]]` (de l'école d'illusion)
- `[[hallucination]]` (de l'école d'illusion)
- `[[branche mirage|mirage]]` (de l'école d'illusion)
- `[[branche ombre|ombre]]` (de l'école d'illusion)
- `[[appel]]` (de l'école d'invocation)
- `[[convocation]]` (de l'école d'invocation)
- `[[création]]` (de l'école d'invocation)
- `[[guérison]]` (de l'école d'invocation)
- `[[branche téléportation|téléportation]]` (de l'école d'invocation)
- `[[branche métamorphose|métamorphose]]` (de l'école de nécromancie)


#### Registres

Les registres, enfin, sont décrits après les écoles entre crochets : La liste des registres existants est la suivante : acide, Air, Bien, Chaos, douleur, Eau, Électricité, Émotion, Feu, force, froid, langage, Loi, lumière, Mal, maladie, malédiction, mental, mort, ombre, poison, son, terre et terreur.

Les crochets étant normalement utilisés pour créer des liens, il faut utiliser une syntaxe particulière pour qu'ils apparaissent à l'écran : il faut les entourer de la balise `&lt;nowiki&gt;&lt;/nowiki&gt;`. Ainsi on utilisera `&lt;nowiki&gt;&#91;&lt;/nowiki&gt;` pour afficher un crochet ouvrant, et `&lt;nowiki&gt;&#93;&lt;/nowiki&gt;` pour les crochets fermants.

(((Pour les experts, on peut aussi utiliser les caractères `&amp;#91;` pour les crochets ouverts et `&amp;#93;` pour les crochets fermés.)))

De plus, il faut créer un lien vers la page "registre" qui renvoie sur la règle qui décrit le fonctionnement des registres.

Ainsi, le registre "mental" sera écrit de la manière suivante :

<pre>&lt;nowiki&gt;<nowiki>[</nowiki>&lt;/nowiki&gt;<nowiki>[[</nowiki>registre|mental<nowiki>]]</nowiki>&lt;nowiki&gt;<nowiki>]</nowiki>&lt;/nowiki&gt;</pre>

Lorsqu'un sort appartient à plusieurs registres, on les sépare par une virgule, dans les crochets. Exemple :

<pre>&lt;nowiki&gt;<nowiki>[</nowiki>&lt;/nowiki&gt;<nowiki>[[</nowiki>registre|émotion<nowiki>]], <nowiki>[[</nowiki>registre|mental<nowiki>]]</nowiki>&lt;nowiki&gt;<nowiki>]</nowiki>&lt;/nowiki&gt;</pre>
