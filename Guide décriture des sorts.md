---
Name: Guide décriture des sorts
Title: Guide d'écriture des sorts
LastModified: 2019-09-10 21:03
---

L'écriture des sorts dans le wiki doit respecter autant que possible des règles fixes pour standardiser leur format.

Ce guide a pour but de permettre à quiconque de participer à la rédaction d'un sort dans le Wiki sans faire d'erreur de format.


@@**École** [nom_école](./nom_école.md) ([branche_école](./branche_école.md)) <nowiki>[</nowiki>[registre](./Pathfinder-RPG/Registre.md)<nowiki>]</nowiki> qsdqsd @@

Voici tout d'abord un exemple complet, que nous allons ensuite décrire partie par partie :

@@**École** [nom_école](./nom_école.md) ([branche_école](./branche_école.md)) <nowiki>[</nowiki>[registre](./Pathfinder-RPG/Registre.md)<nowiki>]</nowiki>; **Niveau** [classes](./Pathfinder-RPG/Classes.md) 1, [sorcière](./Pathfinder-RPG/Sorcière.md) 1  

**Temps d’incantation** 1 [action simple](./Pathfinder-RPG/Action simple.md)  

**Composantes** [V, G](./Pathfinder-RPG/composantes.md)  

**Portée** courte (7,5 m + 1,5 m/2 [niveaux](./Pathfinder-RPG/niveau.md)) (5 {s:c} + 1 {s:c}/2 [niveaux](./Pathfinder-RPG/niveau.md))  

**Cible** un humanoïde  

**Durée** [concentration](./Pathfinder-RPG/Présentation des sorts.md#DUREE) + 2 [rounds](./Pathfinder-RPG/round.md)  

**Jet de sauvegarde** [Volonté](./Pathfinder-RPG/Volonté.md) pour [annuler](./Pathfinder-RPG/Présentation des sorts.md#JETSDESAUVEGARDE) ; **Résistance à la magie** oui ([inoffensif](./Pathfinder-RPG/Présentation des sorts.md#JETSDESAUVEGARDE))

Description...@@

### Règles générales

On distingue deux parties : la partie technique et la partie description.

La partie technique correspond au début du sort, jusqu'à la première ligne vide.
La description est constituée de tout ce qui se trouve ensuite.

### École et niveaux

La première ligne de la partie technique contient l'école du sort, suivi des niveaux de classes nécessaires pour pouvoir connaître le sort.

La ligne débute toujours par le texte "École" en gras (à l'aide des 3 apostrophes) : `**École**`.

On donne ensuite un lien vers l'école du sort en utilisant le nom directement comme lien. Le nom de l'école doit rester en **minuscules**. Exemple : `[enchantement](./Pathfinder-RPG/Enchantement.md)`. L'école divination est un cas à part, car la page "divination" correspond au sort du même nom. L'école est accessible via la page "école divination".

Les écoles possibles sont donc les suivantes :
- `[abjuration](./Pathfinder-RPG/Abjuration.md)`
- `[divination](./Pathfinder-RPG/école divination.md)`
- `[enchantement](./Pathfinder-RPG/Enchantement.md)`
- `[évocation](./Pathfinder-RPG/Évocation.md)`
- `[illusion](./Pathfinder-RPG/Illusion.md)`
- `[invocation](./Pathfinder-RPG/Invocation.md)`
- `[nécromancie](./Pathfinder-RPG/Nécromancie.md)`
- `[transmutation](./Pathfinder-RPG/Transmutation.md)`
- `[universelle](./Pathfinder-RPG/Universelle.md)`

#### Branches

Comme décrit dans la [présentation des sorts](./Pathfinder-RPG/Présentation des sorts.md), les sorts peuvent aussi appartenir à une des branches d'une école.

On indique la branche éventuelle entre parenthèses, après l'école, et dans une lien. Exemple : `[enchantement](./Pathfinder-RPG/Enchantement.md) ([charme](./Pathfinder-RPG/charme.md))`

Comme pour les écoles, certains nom de branches désignent des pages déjà utilisées. On préfixe alors le nom de la branche du mot "branche". La liste des liens de branches est donc la suivante :
- `[scrutation](./Pathfinder-RPG/branche scrutation.md)` (de l'école divination ; la page scrutation renvoie au sort)
- `[charme](./Pathfinder-RPG/charme.md)` (de l'école enchantement)
- `[coercition](./Pathfinder-RPG/coercition.md)` (de l'école enchantement)
- `[chimère](./Pathfinder-RPG/branche chimère.md)` (de l'école d'illusion)
- `[fantasme](./Pathfinder-RPG/fantasme.md)` (de l'école d'illusion)
- `[hallucination](./Pathfinder-RPG/hallucination.md)` (de l'école d'illusion)
- `[mirage](./Pathfinder-RPG/branche mirage.md)` (de l'école d'illusion)
- `[ombre](./Pathfinder-RPG/branche ombre.md)` (de l'école d'illusion)
- `[appel](./Pathfinder-RPG/appel.md)` (de l'école d'invocation)
- `[convocation](./Pathfinder-RPG/convocation.md)` (de l'école d'invocation)
- `[création](./Création.md)` (de l'école d'invocation)
- `[guérison](./Pathfinder-RPG/guérison.md)` (de l'école d'invocation)
- `[téléportation](./Pathfinder-RPG/branche téléportation.md)` (de l'école d'invocation)
- `[métamorphose](./Pathfinder-RPG/branche métamorphose.md)` (de l'école de nécromancie)


#### Registres

Les registres, enfin, sont décrits après les écoles entre crochets : La liste des registres existants est la suivante : acide, Air, Bien, Chaos, douleur, Eau, Électricité, Émotion, Feu, force, froid, langage, Loi, lumière, Mal, maladie, malédiction, mental, mort, ombre, poison, son, terre et terreur.

Les crochets étant normalement utilisés pour créer des liens, il faut utiliser une syntaxe particulière pour qu'ils apparaissent à l'écran : il faut les entourer de la balise `&lt;nowiki&gt;&lt;/nowiki&gt;`. Ainsi on utilisera `&lt;nowiki&gt;&#91;&lt;/nowiki&gt;` pour afficher un crochet ouvrant, et `&lt;nowiki&gt;&#93;&lt;/nowiki&gt;` pour les crochets fermants.

(((Pour les experts, on peut aussi utiliser les caractères `&amp;#91;` pour les crochets ouverts et `&amp;#93;` pour les crochets fermés.)))

De plus, il faut créer un lien vers la page "registre" qui renvoie sur la règle qui décrit le fonctionnement des registres.

Ainsi, le registre "mental" sera écrit de la manière suivante :

<pre>&lt;nowiki&gt;<nowiki>[</nowiki>&lt;/nowiki&gt;<nowiki>[mental<nowiki>](./</nowiki>registre.md)</nowiki>&lt;nowiki&gt;<nowiki>]</nowiki>&lt;/nowiki&gt;</pre>

Lorsqu'un sort appartient à plusieurs registres, on les sépare par une virgule, dans les crochets. Exemple :

<pre>&lt;nowiki&gt;<nowiki>[</nowiki>&lt;/nowiki&gt;<nowiki>[émotion<nowiki>](./</nowiki>registre.md), <nowiki>[mental<nowiki>](./</nowiki>registre.md)</nowiki>&lt;nowiki&gt;<nowiki>]</nowiki>&lt;/nowiki&gt;</pre>
