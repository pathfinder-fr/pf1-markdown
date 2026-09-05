---
Name: Pathfinder-RPG.Moine
Title: Le moine
LastModified: 2024-10-03 11:14
Categories:
- Classe
- Règle officielle
- Src Manuel des joueurs
- Src Manuel des joueurs - Règles avancées
---

{s:MenuClasses}
<div class="fright">***Voir aussi les [voeux](./Voeux.md).***
***Voir la [version unchained](./Moine unchained.md) du moine.***
{s:PM0|moine}**Voir les archétypes du moine**&emsp;
<li ID="moine" CLASS="listecachée" STYLE="display:none">{s:Menuarchétypemoine}</li>
</div>*Pour certains individus réellement exemplaires, l’art du combat ne se limite pas au champ de bataille : il s’agit d’un mode de vie, d’une doctrine, d’un état d’esprit. Ces artistes-combattants recherchent des méthodes de combat qui transcendent les épées et les boucliers. Ils découvrent que la nature les a dotés d’armes tout aussi capables d’affaiblir ou de tuer que les lames. Il s’agit des moines, qu’on appelle ainsi parce qu’ils adhèrent à d’anciennes philosophies et à une discipline martiale stricte. Qu’il s’agisse d’ascètes avec un penchant pour le combat ou de pugilistes qui ont appris sur le tas, ils font de leur corps de véritables armes de guerre. Les moines suivent la voie de la discipline, et ceux qui possèdent suffisamment de volonté pour rester sur ce chemin découvrent en eux non pas qui ils sont, mais ce qu’ils sont destinés à devenir.*

{| CLASS="tablo centre autoalt"
|+ {s:Reference|TABLEMOINE}Le moine
|- CLASS="titre"
| Niv
| BBA
| Réflexes
| Vigueur
| Volonté
| CLASS="gauche" | Spécial
| Déluge de coups
| Dégâts à mains nues*
| Bonus   
de CA
| Déplacement accéléré
|- CLASS="premier"
| 1
| +0
| +2
| +2
| +2
| CLASS="gauche" | [Combat à mains nues](./Moine.md#COMBATAMAINSNUES), [coup étourdissant](./Moine.md#COUPETOURDISSANT), [déluge de coups](./Moine.md#DELUGEDECOUPS), [don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE)
| STYLE="font-size:90%" | -1/-1
| 1d6
| +0
| +0 m
|-
| 2
| +1
| +3
| +3
| +3
| CLASS="gauche" | [Don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE), [esquive totale](./Moine.md#ESQUIVETOTALE)
| STYLE="font-size:90%" | +0/+0
| 1d6
| +0
| +0 m
|-
| 3
| +2
| +3
| +3
| +3
| CLASS="gauche" | [Déplacement accéléré](./Moine.md#DEPLACEMENTACCELERE), [entraînement aux manœuvres offensives](./Moine.md#ENTRAINEMENTAUXMANOEUVRESOFFENSIVES), [sérénité](./Moine.md#SERENITE)
| STYLE="font-size:90%" | +1/+1
| 1d6
| +0
| +3 m (2 {s:c})
|-
| 4
| +3
| +4
| +4
| +4
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 6 m, [réserve de ki](./Moine.md#RESERVEDEKI) (magique)
| STYLE="font-size:90%" | +2/+2
| 1d8
| +1
| +3 m (2 {s:c})
|-
| 5
| +3
| +4
| +4
| +4
| CLASS="gauche" | [Pureté physique](./Moine.md#PURETEPHYSIQUE), [sauts puissants](./Moine.md#SAUTSPUISSANTS)
| STYLE="font-size:90%" | +3/+3
| 1d8
| +1
| +3 m (2 {s:c})
|-
| 6
| +4
| +5
| +5
| +5
| CLASS="gauche" | [Don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE), [chute ralentie](./Moine.md#CHUTERALENTIE) 9 m
| STYLE="font-size:90%" | +4/+4/-1
| 1d8
| +1
| +6 m (4 {s:c})
|-
| 7
| +5
| +5
| +5
| +5
| CLASS="gauche" | [Plénitude physique](./Moine.md#PLENITUDEPHYSIQUE), [réserve de ki](./Moine.md#RESERVEDEKI) (fer froid/argent)
| STYLE="font-size:90%" | +5/+5/+0
| 1d8
| +1
| +6 m (4 {s:c})
|-
| 8
| +6/+1
| +6
| +6
| +6
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 12 m
| STYLE="font-size:90%" | +6/+6/+1/+1
| 1d10
| +2
| +6 m (4 {s:c})
|-
| 9
| +6/+1
| +6
| +6
| +6
| CLASS="gauche" | [Esquive surnaturelle](./Moine.md#ESQUIVESURNATURELLE)
| STYLE="font-size:90%" | +7/+7/+2/+2
| 1d10
| +2
| +9 m (6 {s:c})
|-
| 10
| +7/+2
| +7
| +7
| +7
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 15 m, [don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE), [réserve de ki](./Moine.md#RESERVEDEKI) (loyale)
| STYLE="font-size:90%" | +8/+8/+3/+3
| 1d10
| +2
| +9 m (6 {s:c})
|-
| 11
| +8/+3
| +7
| +7
| +7
| CLASS="gauche" | [Corps de diamant](./Moine.md#CORPSDEDIAMANT)
| STYLE="font-size:90%" | +9/+9/+4/+4/-1
| 1d10
| +2
| +9 m (6 {s:c})
|-
| 12
| +9/+4
| +8
| +8
| +8
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 18 m, [pas chassé](./Moine.md#PASCHASSE)
| STYLE="font-size:90%" | +10/+10/+5/+5/+0
| 2d6
| +3
| +12 m (8 {s:c})
|-
| 13
| +9/+4
| +8
| +8
| +8
| CLASS="gauche" | [Âme de diamant](./Moine.md#AMEDEDIAMANT)
| STYLE="font-size:90%" | +11/+11/+6/+6/+1
| 2d6
| +3
| +12 m (8 {s:c})
|-
| 14
| +10/+5
| +9
| +9
| +9
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 21 m, [don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE)
| STYLE="font-size:90%" | +12/+12/+7/+7/+2
| 2d6
| +3
| +12 m (8 {s:c})
|-
| 15
| +11/+6/+1
| +9
| +9
| +9
| CLASS="gauche" | [Paume vibratoire](./Moine.md#PAUMEVIBRATOIRE)
| STYLE="font-size:90%" | +13/+13/+8/+8/+3/+3
| 2d6
| +3
| +15 m (10 {s:c})
|-
| 16
| +12/+7/+2
| +10
| +10
| +10
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 24 m, [réserve de ki](./Moine.md#RESERVEDEKI) (adamantium)
| STYLE="font-size:90%" | +14/+14/+9/+9/+4/+4/-1
| 2d8
| +4
| +15 m (10 {s:c})
|-
| 17
| +12/+7/+2
| +10
| +10
| +10
| CLASS="gauche" | [Éternelle jeunesse](./Moine.md#ETERNELLEJEUNESSE), [langue du soleil et de la lune](./Moine.md#LANGUEDUSOLEILETDELALUNE)
| STYLE="font-size:90%" | +15/+15/+10/+10/+5/+5/+0
| 2d8
| +4
| +15 m (10 {s:c})
|-
| 18
| +13/+8/+3
| +11
| +11
| +11
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) 27 m, [don supplémentaire](./Moine.md#DONSUPPLEMENTAIRE)
| STYLE="font-size:90%" | +16/+16/+11/+11/+6/+6/+1
| 2d8
| +4
| +18 m (12 {s:c})
|-
| 19
| +14/+9/+4
| +11
| +11
| +11
| CLASS="gauche" | [Désertion de l'âme](./Moine.md#DESERTIONDELAME)
| STYLE="font-size:90%" | +17/+17/+12/+12/+7/+7/+2
| 2d8
| +4
| +18 m (12 {s:c})
|-
| 20
| +15/+10/+5
| +12
| +12
| +12
| CLASS="gauche" | [Chute ralentie](./Moine.md#CHUTERALENTIE) (n'importe quelle distance), [perfection de l'être](./Moine.md#PERFECTIONDELETRE)
| STYLE="font-size:90%" | +18/+18/+13/+13/+8/+8/+3
| 2d10
| +5
| +18 m (12 {s:c})
|-
| CLASS="note" COLSPAN="10" | (*) Il s'agit de la valeur pour les moines de taille M. Voir le texte pour les moines de taille P ou G.
|}

**Rôle.** Les moines excellent lorsqu’il s’agit de surmonter les dangers les plus périlleux. Ils frappent où on s’y attend le moins et profitent de tous les points faibles de l’ennemi. Rapides et doués au combat, ils peuvent se déplacer facilement sur le champ de bataille pour prêter main-forte à leurs alliés là où on a le plus besoin d’eux.

**Alignement.** N’importe quel alignement loyal.

**Dés de vie.** d8.

**Argent de départ.** 1d6 x 10 po (moyenne 35 po).

### Compétences de classe
Les compétences de classe du moine sont les suivantes : [Acrobaties](./Acrobaties.md) (Dex), [Artisanat](./Artisanat.md) (Int), [Connaissances](./Connaissances.md) (histoire) (Int), [Connaissances](./Connaissances.md) (religion) (Int), [Discrétion](./Discrétion.md) (Dex), [Équitation](./Équitation.md) (Dex), [Escalade](./Escalade.md) (For), [Évasion](./Évasion.md) (Dex), [Intimidation](./Intimidation.md) (Cha), [Natation](./Natation.md) (For), [Perception](./Perception.md) (Sag), [Profession](./Profession.md) (Sag), [Psychologie](./Psychologie.md) (Sag) et [Représentation](./Représentation.md) (Cha).

**Points de compétence par niveau.** 4 + modificateur d’[Intelligence](./Intelligence.md).

### Descriptif de la classe
Les aptitudes du moine sont décrites ci-dessous.

{s:ImageDroite|Illustrations/PNJ/Sajan.jpg|35%}
{s:Reference|ARMESDEMOINE}
#### Armes et armures
Le moine est formé au maniement de l'arbalète légère et lourde, du bâton, du ceste<sup>APG</sup>, du coup de poing américain<sup>APG</sup>, de la dague, de l'épée courte, de l'épée du temple<sup>APG</sup>, de l'épieu, de la fronde, du gourdin, de la hachette, de la javeline, du kama, de la lance, du nunchaku, du sai, du shuriken et du siangham.

Le moine n’est formé ni au port d’armures ni à l’utilisation de boucliers.

Lorsqu’il porte une armure ou utilise un bouclier, ou encore lorsqu’il transporte une [charge lourde](./charge lourde.md) ou [intermédiaire](./charge intermédiaire.md), un moine perd son bonus à la [CA](./CA.md) ainsi que ses aptitudes de [déplacement accéléré](./Moine.md#DEPLACEMENTACCELERE) et de [déluge de coups](./Moine.md#DELUGEDECOUPS).

{s:Reference|BONUSCA}

#### Bonus à la CA (Ext)
Tant qu’il ne porte pas d’armure et qu’il n’est pas encombré, un moine ajoute son bonus de [Sagesse](./Sagesse.md) (s’il en a un) à sa [CA](./CA.md) et à son [DMD](./DMD.md). De plus, il obtient un bonus de +1 à la [CA](./CA.md) et au [DMD](./DMD.md) au niveau 4. Ce bonus augmente de +1 tous les quatre niveaux de moine par la suite, jusqu’à un maximum de +5 au niveau 20.

Ces bonus à la [CA](./CA.md) s’appliquent aussi contre les [attaques de contact](./attaque de contact.md) ou lorsque le moine est [pris au dépourvu](./Pris au dépourvu.md). Il les perd s’il est [immobilisé](./Immobilisé.md), s’il est [sans défense](./Sans défense.md) ou s’il porte une armure ou un bouclier ou transporte une [charge intermédiaire](./charge intermédiaire.md) ou [lourde](./charge lourde.md).

{s:Reference|DELUGEDECOUPS}
#### Déluge de coups (Ext)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#19) Moine, Déluge de coups : Comment le BBA amélioré des moines lorsqu’ils portent un déluge interagit-il avec les dons comme Attaque en puissance et Expertise du combat, qui ont des effets différents selon le BBA du personnage ?***

Le <u>[moine](./Moine.md#DELUGEDECOUPS)</u> utilise le BBA amélioré de son déluge pour déterminer les effets de ces dons.
---
***[→](./FAQ- Manuel des joueurs (Races et classes).md#20) Moine, Déluge de coups : Les règles de moine sur le déluge stipulent : « Pour déterminer les bonus de ces attaques, on considère que le bonus de base à l’attaque du moine est égal à son niveau de moine. » Comment cela interagit-il avec le BBA des niveaux de classe et des Dés de Vie raciaux ? Est-ce qu’un personnage multiclassé guerrier 19/moine 1 porte un déluge comme si son BBA n’était que de +1 ?***

Un moine utilisant son <u>[déluge](./Moine.md#DELUGEDECOUPS)</u> traite le BBA de ses niveaux de moine comme égal à son niveau de moine. Il ajoute toujours le BBA des autres sources (comme celui d’autres classes ou de Dés de Vie raciaux) normalement à ce total.

Donc si un guerrier 19/moine 1 a un BBA normal de +19. Lorsqu’il porte un déluge, il traite son BBA de moine comme +1 (pour 1 niveau de moine) et bénéficie quand même du BBA +19 de ses niveaux de guerrier, pour un BBA de déluge total de +20.
---
***[→](./FAQ- Manuel des joueurs (Races et classes).md#21) Moine, Déluge de coups : Lorsque j’utilise le déluge de coups, puis-je porter toutes les attaques avec une seule arme, ou dois-je en utiliser deux, comme il est sous-entendu que la capacité fonctionne comme Combat à deux armes ?***

Le personnage peut porter toutes ses attaques avec une unique arme de moine. Sinon, il peut remplacer autant d’attaques qu’il le souhaite par des attaques à mains nues. Cette FAQ change expressément une décision antérieure prise sur le blog à propos de ce problème. *(Retour à la <u>[capacité](./Moine.md#DELUGEDECOUPS)</u>)*
---
***[→](./FAQ- Manuel des joueurs (Races et classes).md#22) Moine, Déluge de coups et réserve de ki : Est-ce que l’attaque supplémentaire obtenue par la dépense de ki dans le cadre d’un déluge de coups se cumule avec l’attaque supplémentaire de *rapidité* ?***

Oui. L’attaque supplémentaire décrite dans la capacité [réserve de ki](./Moine.md#RESERVEDEKI) ne dit pas qu’elle fonctionne comme *[rapidité](./Rapidité.md)*, ni qu’elle ne se cumule pas avec *rapidité*, donc le moine obtiendrait deux attaques supplémentaires (une par la dépense de ki dans le cadre d’un <u>[déluge de coups](./Moine.md#DELUGEDECOUPS)</u>, et une par *rapidité*).}Dès le niveau 1, un moine peut faire pleuvoir un déluge de coups lors d’une [attaque à outrance](./attaque à outrance.md). Dans ce cas, il peut porter une attaque supplémentaire à condition d'accepter une pénalité de -2 sur tous ses jets d'attaque, comme s'il utilisait le don [Combat à deux armes](./Combat à deux armes.md). Les attaques en question peuvent être n'importe quelle combinaison d'attaques à mains nues et d'attaques utilisant des [armes de moine](./groupe darmes.md#Armesdemoine) (il n'est pas nécessaire d'utiliser deux armes différentes pour tirer parti de cette capacité). Pour déterminer les bonus de ces attaques, on considère que le [bonus de base à l’attaque](./BBA.md) du moine est égal à son niveau de moine. Pour toutes les autres considérations (comme pour déterminer si le moine remplit les conditions d’un don ou d’une classe de prestige), le moine utilise son [bonus de base à l’attaque](./BBA.md) normal.

Au niveau 8, le moine peut porter deux attaques supplémentaires lorsqu’il fait pleuvoir un déluge de coups, comme s’il utilisait le don [Science du combat à deux armes](./Science du combat à deux armes.md) (même s’il ne remplit pas les conditions de ce don).

Au niveau 15, il peut porter trois attaques supplémentaires lorsqu’il fait pleuvoir un déluge de coups, comme s’il utilisait le don [Combat à deux armes supérieur](./Combat à deux armes supérieur.md) (même s’il ne remplit pas les conditions de ce don).

Le moine ajoute son bonus de [Force](./Force.md) entier aux jets de dégâts pour toutes les attaques du déluge de coups qui touchent, même celles qu’il porte avec une [arme tenue à deux mains](./arme à deux mains.md) ou avec une [arme secondaire](./arme à deux mains.md). Il peut remplacer une des attaques à mains nues d’un déluge de coups par une manœuvre offensive de [désarmement](./désarmement.md), de [destruction](./destruction.md) ou de [croc-en-jambe](./croc-en-jambe.md). Lors d’un déluge de coups, le moine ne peut utiliser que des attaques à mains nues ou des armes spéciales de moines, aucune autre arme. Si le moine dispose d’attaques naturelles, il ne peut les utiliser ni dans un déluge de coups ni en plus d’un déluge de coups.

{s:Reference|COMBATAMAINSNUES}
#### Combat à mains nues
<div style="float:right; background-color: #fff; padding: 0 0 16px 16px">
<div style="border: 1px solid #4b3124; padding: 4px">
{| CLASS="tablo centre autoalt"
|+ Dégâts à mains nues des moines  
de taille P ou G
|- CLASS="titre"
| Niveau
| Dégâts  
 (taille P)
| Dégâts  
 (taille G)
|- CLASS="premier"
| 1–3 || 1d4 || 1d8
|-
| 4–7 || 1d6 || 2d6
|-
| 8–11 || 1d8 || 2d8
|-
| 12–15 || 1d10 || 3d6
|-
| 16–19 || 2d6 || 3d8
|-
| 20 || 2d8 || 4d8
|}
</div></div>Un moine de niveau 1 reçoit le don [Science du combat à mains nues](./Science du combat à mains nues.md) comme don supplémentaire. Ses attaques peuvent venir de ses poings, mais aussi de ses pieds, de ses coudes ou de ses genoux. Cela signifie qu’un moine peut même porter des attaques « à mains nues » alors que ses deux mains sont occupées à porter quelque chose. De plus, la notion d’attaque secondaire n’a pas de sens quand il se bat à mains nues. Un moine bénéficie donc toujours de son bonus de [Force](./Force.md) entier sur les [jets de dégâts](./jet de dégâts.md) à mains nues.

En règle générale, les attaques à mains nues du moine infligent des [dégâts létaux](./Dégâts létaux.md), mais le moine peut choisir d’infliger des [dégâts non létaux](./Dégâts non létaux.md) sans devoir subir un malus au [jet d’attaque](./jet dattaque.md). Ce même choix lui est offert en situation de [lutte](./lutte.md).

L’attaque à mains nues du moine est considérée à la fois comme une arme manufacturée et une arme naturelle pour les sorts et effets qui altèrent ou améliorent l’un ou l’autre de ces deux types d’armes.

Les attaques à mains nues d’un moine infligent plus de dégâts que la normale, comme indiqué dans la Table [Le Moine](./Moine.md#TABLEMOINE). Les dégâts de cette table concernent uniquement les moines de [taille M](./taille M.md). Les moines de [taille P](./taille P.md) infligent des dégâts moins importants, tandis que ceux de [taille G](./taille G.md) infligent des dégâts plus élevés, comme indiqué dans la table suivante.

{s:Reference|DONSUPPLEMENTAIRE}
#### Dons supplémentaires
Aux niveaux 1 et 2 et tous les quatre niveaux suivants, un moine peut choisir un don supplémentaire.

Ces dons doivent être choisis dans la liste suivante : [Attaques réflexes](./Attaques réflexes.md), [École du scorpion](./École du scorpion.md), [Esquive](./Esquive.md), [Lancer improvisé](./Lancer improvisé.md), [Parade de projectiles](./Parade de projectiles.md), [Science de la lutte](./Science de la lutte.md) et [Surprise](./Surprise.md).

Au niveau 6, les dons suivants s’ajoutent à la liste : [Poing de la gorgone](./Poing de la gorgone.md), [Science de la bousculade](./Science de la bousculade.md), [Science de la feinte](./Science de la feinte.md), [Science du croc-en-jambe](./Science du croc-en-jambe.md), [Science du désarmement](./Science du désarmement.md) et [Souplesse du serpent](./Souplesse du serpent.md).

Au niveau 10, les dons suivants s’ajoutent à la liste : [Attaque éclair](./Attaque éclair.md), [Fureur de la méduse](./Fureur de la méduse.md), [Capture de projectiles](./Capture de projectiles.md), [Lancer ki](./Lancer ki.md)<sup>APG</sup> et [Science du critique](./Science du critique.md).

Au niveau 14, le don suivant s'ajoute à cette liste : [Science du lancer ki](./Science du lancer ki.md)<sup>APG</sup>, [Entrave à distance](./Entrave à distance.md)<sup>AdG</sup>

Le moine peut choisir un de ces dons comme don supplémentaire même s’il ne remplit pas les conditions requises.

{s:Reference|COUPETOURDISSANT}
#### Coup étourdissant (Ext)
Au niveau 1, le moine obtient le don [Coup étourdissant](./Coup étourdissant.md) comme don supplémentaire, même s’il n’en remplit pas les conditions. Au niveau 4 et tous les quatre niveaux suivant, le moine acquiert la capacité d’appliquer un nouvel état préjudiciable à la cible de son coup étourdissant. La cible subit l’état choisi pendant un round (au lieu d’être [étourdie](./Étourdi.md)) si son jet de sauvegarde échoue. Au niveau 4, le moine peut choisir de rendre la cible [fatiguée](./Fatigué.md). Au niveau 8, il peut la rendre [fiévreuse](./Fiévreux.md) pendant une minute. Au niveau 12, il peut la rendre [chancelante](./Chancelant.md) pour 1d6+1 rounds. Au niveau 16, il peut l’[aveugler](./Aveuglé.md) ou la rendre [sourde](./sourd.md) de manière permanente. Au niveau 20, il peut la [paralyser](./Paralysé.md) pour 1d6+1 rounds. Le moine choisit l’état préjudiciable qu’il désire infliger avant de faire son jet d’attaque. Ces effets ne se cumulent pas (une créature rendue [fiévreuse](./Fiévreux.md) par cette capacité ne deviendra ainsi pas [nauséeuse](./Nauséeux.md) si elle est affectée par un nouveau Coup étourdissant), mais les coups supplémentaires augmentent la durée de l'état préjudiciable initial.

{s:Reference|ESQUIVETOTALE}
#### Esquive totale (Ext)
À partir du niveau 2, le moine peut esquiver de nombreuses attaques de zone. S’il réussit son jet de [Réflexes](./Réflexes.md) contre une attaque dont les dégâts sont normalement réduits de moitié, il ne subit pas le moindre dégât. Un moine portant une armure ou une [charge intermédiaire](./charge intermédiaire.md) ou [lourde](./charge lourde.md) ou qui se trouve [sans défense](./Sans défense.md) perd les avantages de l’esquive totale.

{s:Reference|DEPLACEMENTACCELERE}
#### Déplacement accéléré (Ext)
À partir du niveau 3, un moine obtient un bonus d’altération à sa [vitesse de déplacement](./vitesse de déplacement.md) au sol, comme indiqué dans la Table "[Le Moine](./Moine.md#TABLEMOINE)". Il perd ce bonus s’il porte une armure ou une [charge intermédiaire](./charge intermédiaire.md) ou [lourde](./charge lourde.md).

{s:Reference|ENTRAINEMENTAUXMANOEUVRESOFFENSIVES}
#### Entraînement aux manœuvres offensives (Ext)
Au niveau 3, le moine utilise son niveau de moine au lieu de son [bonus de base à l’attaque](./BBA.md) lorsqu’il calcule son [bonus de manœuvre offensive](./BMO.md). Les [bonus de base à l’attaque](./BBA.md) provenant d’autres classes ne sont pas modifiés et se cumulent normalement.

{s:Reference|SERENITE}
#### Sérénité (Ext)
Un moine de niveau 3 bénéficie d’un bonus de +2 aux [jets de sauvegarde](./jet de sauvegarde.md) contre les sorts et effets de type [enchantement](./Enchantement.md).

{s:Reference|POINTDEKI}{s:Reference|RESERVEDEKI}
#### Réserve de ki (Sur)
{s:FAQ|**'<u>Ce texte a été modifié suite à la FAQ suivante :</u>

[→](./FAQ- Manuel des joueurs (Races et classes).md#32) Réserve de ki du moine : Quels types de réduction de dégâts un moine peut-il ignorer grâce à cette capacité ?**'

Les moines ont souvent des problèmes à ignorer les [RD](./RD.md) avec leurs attaques à mains nues, ce qui les force à dépendre d’armes pour gérer plusieurs sortes de RD. Nous avons décider d’ajouter un nouveau pouvoir à la capacité de classe <u>[réserve de ki](./Moine.md#RESERVEDEKI)</u> du moine. Au niveau 7, les attaques à mains nues du moine sont considérées comme des armes en fer froid et en argent pour ce qui est d'ignorer la réduction de dégâts des créatures, et ce tant qu’il lui reste au moins 1 point dans sa réserve de ki.
Cette réponse est d’abord apparue dans le [Paizo blog du 4/12/2012](http://paizo.com/paizo/blog/v5748dyo5le61?Monkeying-Around).}À partir du niveau 4, le moine dispose d’une réserve de points ki, une énergie surnaturelle qu’il peut utiliser pour accomplir des exploits étonnants. Cette réserve contient un nombre de points égal à la moitié du niveau du moine + son modificateur de [Sagesse](./Sagesse.md). Tant qu’il reste au moins 1 point ki dans la réserve du moine, celui-ci peut effectuer une frappe ki.
Au niveau 4, les attaques à mains nues lors d’une frappe ki sont considérées comme des [armes magiques](./Armes magiques.md) pour ce qui est d’ignorer la [réduction de dégâts des créatures](./RD.md).
Au niveau 7, les attaques à mains nues du moine sont considérées comme des armes en fer froid et en argent pour ce qui est d'ignorer la [réduction de dégâts des créatures](./RD.md).
Au niveau 10, ses attaques à mains nues sont également considérées comme des armes Loyales pour déterminer si elles ignorent les [réductions de dégâts](./RD.md).
Au niveau 16, elles sont considérées comme des armes en [adamantium](./../Golarion/adamantium.md) pour déterminer si elles ignorent les [réductions de dégâts](./RD.md) ou la [solidité](./solidité.md) des objets.

En dépensant 1 point de sa réserve de ki, le moine peut ajouter une attaque supplémentaire à un déluge de coups (cette attaque supplémentaire utilise son bonus d’attaque le plus élevé). Il peut également dépenser 1 point pour augmenter sa vitesse de déplacement de 6 m pendant 1 round. Finalement, le moine peut dépenser 1 point de sa réserve de ki pour gagner un bonus d’esquive de +4 à sa [CA](./CA.md) pendant 1 round. Chacune de ces options requiert une [action rapide](./Action rapide.md). D’autres manières d’utiliser les points ki s’offrent au moine lorsqu’il progresse en niveau.

La réserve de ki du moine se renouvelle chaque matin après huit heures de repos ou de méditation (qui ne doivent pas forcément être consécutives).

**Les vœux.** {s:um}Un moine peut discipliner son corps pour stocker plus de ki en respectant scrupuleusement un [vœu](./Voeux.md). Tant qu’il s’y tient, sa réserve de ki augmente du montant indiqué dans la description du vœu. Tous les [vœux](./vœux.md) comportent un inconvénient ou une limite pour contrebalancer cette hausse. Un moine peut prononcer un vœu à n’importe quel niveau mais il ne peut pas l’appliquer à sa réserve de ki tant qu’il n’a pas gagné une réserve de ki comme pouvoir de classe. Un moine qui prononce un vœu ne peut plus jamais bénéficier du pouvoir de classe sérénité, même s’il brise son vœu.

Si un moine brise volontairement et sciemment un vœu, sa réserve de ki tombe à 0 (comme s’il avait dépensé tous ses points) et il ne peut plus la remplir ni utiliser de pouvoirs qui exigent du ki tant qu’il ne s’est pas racheté. Cette rédemption exige qu’il reprenne ses vœux et subisse un sort de pénitence. Une fois que le moine s’est racheté, sa réserve de ki revient à la normale (sans le bonus du vœu). S’il respecte le vœu brisé pendant un mois complet, il récupère aussi les points de ki supplémentaires dus au vœu et peut alors choisir de vivre à nouveau en accord avec ce vœu ou d’y renoncer sans malus. Quand un moine renonce ainsi à un vœu, il ne peut plus jamais bénéficier de points de ki supplémentaires grâce à ce vœu précis.

Un moine peut prononcer plusieurs vœux. Leurs effets et leur augmentation de réserve de ki se cumulent. Si un moine viole un vœu, la rédemption lui permet de se servir à nouveau de l’amélioration due aux autres vœux mais le ki supplémentaire issu du vœu brisé ne reviendra pas avant un mois de dévotion (en effet, une fois que le moine s’est racheté, la violation du vœu n’a plus aucun effet sur les autres).

{s:Reference|CHUTERALENTIE}
#### Chute ralentie (Ext)
À partir du niveau 4, lorsque le moine se trouve assez près d’une paroi pour pouvoir la toucher, il peut l’utiliser pour freiner sa [chute](./chute.md). Au début, cette aptitude permet de réduire les dégâts résultant de la [chute](./chute.md) en considérant que celle-ci s’effectuait sur une hauteur de 6 m de moins que sa hauteur réelle. La capacité du moine à ralentir sa chute (c’est-à-dire à en réduire les dégâts en ignorant une partie de la distance parcourue) s’améliore lorsque son niveau augmente et, finalement, au niveau 20, le moine ne subit plus aucun dégât en cas de [chute](./chute.md) à proximité d’une paroi.

{s:Reference|SAUTSPUISSANTS}
#### Sauts puissants (Ext)
Au niveau 5, le moine ajoute son niveau à tous les tests d’[Acrobaties](./Acrobaties.md) relatifs à des sauts (verticaux ou horizontaux). De plus, on considère qu’il dispose toujours d’un élan (même si ce n’est pas le cas en pratique). En dépensant 1 point de sa [réserve de ki](./Moine.md#RESERVEDEKI) (ce qui nécessite une [action rapide](./Action rapide.md)) le moine gagne pendant 1 round un bonus de +20 à tous les tests d’[Acrobaties](./Acrobaties.md) relatifs à des sauts.

{s:Reference|PURETEPHYSIQUE}
#### Pureté physique (Ext)
Au niveau 5, le moine développe une immunité à toutes les [maladies](./maladie.md), même celles qui sont d’origine surnaturelle ou magique.

{s:Reference|PLENITUDEPHYSIQUE}
#### Plénitude physique (Sur)
Dès le niveau 7, le moine est capable de se soigner par une [action simple](./Action simple.md). Il peut récupérer un nombre de [points de vie](./points de vie.md) égal à son niveau de moine en utilisant 2 points de sa [réserve de ki](./Moine.md#RESERVEDEKI).

{s:Reference|ESQUIVESURNATURELLE}
#### Esquive surnaturelle (Ext)
Au niveau 9, l’[esquive totale](./Moine.md#ESQUIVETOTALE) du moine s’améliore. Face aux attaques permettant un jet de [Réflexes](./Réflexes.md) pour réduire les dégâts de moitié, il continue à ne subir aucun dégât en cas de jet de sauvegarde réussi mais, en plus, il ne subit que la moitié des dégâts en cas d’échec du jet de sauvegarde. Le moine ne bénéficie pas de cette capacité s’il est [sans défense](./Sans défense.md).

{s:Reference|CORPSDEDIAMANT}
#### Corps de diamant (Sur)
Au niveau 11, le moine développe une immunité à tous les types de [poisons](./poison.md).

{s:Reference|PASCHASSE}
#### Pas chassé (Sur)
À partir du niveau 12, le moine peut se déplacer instantanément d’un endroit à un autre comme à l’aide du sort *[porte dimensionnelle](./Porte dimensionnelle.md)*. Chaque utilisation de cette capacité nécessite une [action de mouvement](./Action de mouvement.md) et coûte 2 points de [ki](./Moine.md#RESERVEDEKI). Le [niveau de lanceur de sorts](./NLS.md) du moine pour cet effet est égal à son niveau de moine. Seul le moine peut se déplacer ainsi : il ne peut amener personne avec lui.

{s:Reference|AMEDEDIAMANT}
#### Âme de diamant (Ext)
Au niveau 13, le moine acquiert une [résistance à la magie](./RM.md) égale à son niveau de moine actuel + 10. Pour pouvoir l’affecter à l’aide d’un sort, son adversaire doit effectuer un test de niveau de lanceur de sorts (1d20 + son [niveau de lanceur de sorts](./NLS.md)) et obtenir un résultat égal ou supérieur à la [RM](./RM.md) du moine.

{s:Reference|PAUMEVIBRATOIRE}
#### Paume vibratoire (Sur)
Dès le niveau 15, le moine peut utiliser cette redoutable attaque lui permettant de transmettre des vibrations dangereuses à sa cible, qui peuvent devenir fatales quand il le désire. Le personnage peut se servir de la paume vibratoire une fois par jour et doit l’annoncer avant d’effectuer son [jet d’attaque](./jet dattaque.md). Les créatures immunisées aux coups critiques ne sont pas affectées par ce pouvoir. Si le coup porte et si l’adversaire est blessé, les vibrations sont transmises avec succès au corps de la victime. À partir de ce moment, le moine peut décider de la tuer à tout instant (les vibrations persistent pendant un jour par niveau du moine). Dès qu’il prend cette décision (ce qui lui demande une [action libre](./Action libre.md)), la cible doit effectuer un jet de [Vigueur](./Vigueur.md) (DD 10 + la moitié du niveau du moine + le modificateur de [Sagesse](./Sagesse.md) du moine). En cas d’échec, elle meurt. Si elle réussit, les vibrations cessent et elle ne risque plus rien (mais elle peut subir une nouvelle attaque de paume vibratoire). Le moine ne peut activer plus d’un effet de paume vibratoire à la fois : si une victime est encore affectée par la paume vibratoire du moine et que celui-ci utilise cette capacité à nouveau, l’effet le plus ancien prend fin immédiatement.

{s:Reference|ETERNELLEJEUNESSE}
#### Éternelle jeunesse (Ext)
À partir du niveau 17, les affaiblissements de caractéristiques dus au [vieillissement](./vieillissement.md) n’affectent plus le moine, pas plus que les attaques provoquant un [vieillissement](./vieillissement.md) accéléré. Les affaiblissements qu’il aurait pu subir avant d’atteindre ce niveau ne sont pas annulés pour autant. Le moine continue de vieillir et bénéficie des bonus qui en découlent. Il meurt toujours de vieillesse lorsque son heure est venue.

{s:Reference|LANGUEDUSOLEILETDELALUNE}
#### Langues du soleil et de la lune (Ext)
À partir du niveau 17, le moine peut communiquer avec toutes les créatures vivantes.

{s:Reference|DESERTIONDELAME}
#### Désertion de l’âme (Sur)
Au niveau 19, le personnage peut devenir [éthéré](./Éthéré.md) pendant une minute comme s’il utilisait le sort *[passage dans l’éther](./Passage dans léther.md)*. Cette capacité s’active par une [action de mouvement](./Action de mouvement.md) et coûte 3 points de [ki](./Moine.md#RESERVEDEKI). Seul le moine est affecté : il ne peut pas utiliser désertion de l’âme pour appliquer le même effet à d’autres créatures.

{s:Reference|PERFECTIONDELETRE}
#### Perfection de l’être
Au niveau 20, le moine devient une entité magique. À partir de cet instant, il n’est plus considéré comme un humanoïde mais comme un [Extérieur](./type Extérieur.md) pour ce qui est des sorts et des effets magiques. De plus, le moine acquiert une [réduction de dégâts](./RD.md) de 10/chaotique, ce qui signifie qu’il ignore les 10 premiers points de dégâts infligés par chaque attaque portée avec une arme non-chaotique ou avec une arme naturelle d’une créature qui ne dispose pas d’une [réduction de dégâts](./RD.md) similaire. Contrairement aux autres [Extérieurs](./type Extérieur.md), le moine peut être ramené à la vie, comme si son type de créature n’avait pas changé.

### Anciens moines
Un moine cessant d’être Loyal ne peut plus gagner de niveau de moine mais conserve les pouvoirs acquis jusque-là.
