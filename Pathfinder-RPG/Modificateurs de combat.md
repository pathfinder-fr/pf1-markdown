---
Name: Pathfinder-RPG.Modificateurs de combat
Title: Modificateurs de combat
LastModified: 2024-08-27 21:50
Categories:
- Combat
---

{s:MenuCombat}<div style="float: right; padding: 0 0 8px 8px"><nav class="wiki-toc"></nav></div>Un certain nombre de facteurs et de conditions peuvent influencer un [jet d’attaque](./jet dattaque.md). La majorité de ces situations fournissent un bonus ou un malus au jet en lui-même ou bien à la [CA](./CA.md) de la cible.

{s:ClearRight}
<table width="100%"><tr style="vertical-align: top"><td width="50%">
{| CLASS="tablo centre autoalt" WIDTH="96%"
|+ Modificateurs au jet d’attaque
|- CLASS="titre"
| L’attaquant… || Corps à corps || À distance
|- CLASS="premier"
| … est [à terre](./À terre.md) ou à plat ventre || –4 || —<sup>[1](./Modificateurs de combat.md#NOTE1)</sup>
|-
| … est [ébloui](./Ébloui.md) || -1 || -1
|-
| … est en position surélevée || +1 || +0
|-
| … est [enchevêtré](./Enchevêtré.md) || –2<sup>[2](./Modificateurs de combat.md#NOTE2)</sup> || –2<sup>[2](./Modificateurs de combat.md#NOTE2)</sup>
|-
| … est [invisible](./Invisible.md) || +2<sup>[3](./Modificateurs de combat.md#NOTE3)</sup> || +2<sup>[3](./Modificateurs de combat.md#NOTE3)</sup>
|-
| … est [secoué](./Secoué.md) ou [effrayé](./Effrayé.md) || -2 || -2
|-
| … [prend le défenseur en tenaille](./Pris en tenaille.md) || +2 || —
|-
| … [se serre dans un espace étroit](./Déplacement et position.md#SESERRER) || -4 || -4
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE1}*(1) La plupart des armes à distance ne peuvent être utilisées par un personnage [à terre](./À terre.md), sauf les arbalètes et les shuriken qui sont utilisables sans aucun malus.*
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE2}*(2) Un personnage [enchevêtré](./Enchevêtré.md) subit également un malus de -4 en [Dextérité](./Dextérité.md), ce qui peut affecter son [jet d’attaque](./jet dattaque.md).*
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE3}*(3) Le défenseur perd son éventuel bonus de [Dextérité](./Dextérité.md) à la [CA](./CA.md).*
|}
</td><td width="50%">
{| CLASS="tablo centre autoalt" WIDTH="96%"
|+ Modificateurs à la CA
|- CLASS="titre"
| Le défenseur… || Corps à corps || À distance
|- CLASS="premier"
| … est [à couvert](./abri.md) || +4 || +4
|-
| … est assis ou agenouillé || -2 || +2
|-
| … est [à terre](./À terre.md) || -4 || +4
|-
| … est [aveugle](./Aveuglé.md) || –2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup> || –2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup>
|-
| … est [camouflé](./camouflage.md) ou [invisible](./Invisible.md)
| COLSPAN="2" | Voir [Camouflage](./Modificateurs de combat.md#CAMOUFLAGE)
|-
| … est enchevêtré || +0<sup>[5](./Modificateurs de combat.md#NOTE5)</sup> || +0<sup>[5](./Modificateurs de combat.md#NOTE5)</sup>
|-
| … est en situation de [lutte](./lutte.md) (pas l’attaquant) || +0 || +0
|-
| … est [étourdi](./Étourdi.md) || -2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup> || –2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup>
|-
| … est [immobilisé](./Immobilisé.md) en situation de [lutte](./lutte.md) || -4<sup>[6](./Modificateurs de combat.md#NOTE6)</sup> || +0<sup>[6](./Modificateurs de combat.md#NOTE6)</sup>
|-
| … est [pris au dépourvu](./Pris au dépourvu.md) || +0<sup>[4](./Modificateurs de combat.md#NOTE4)</sup> || +0<sup>[4](./Modificateurs de combat.md#NOTE4)</sup>
|-
| … est [recroquevillé](./Recroquevillé.md) || -2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup> || -2<sup>[4](./Modificateurs de combat.md#NOTE4)</sup>
|-
| … est [sans défense](./Sans défense.md) || -4<sup>[6](./Modificateurs de combat.md#NOTE6)</sup> || +0<sup>[6](./Modificateurs de combat.md#NOTE6)</sup>
|-
| … [se serre dans un espace étroit](./Déplacement et position.md#SESERRER) || -4 || -4
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE4}*(4) Le défenseur perd son bonus de [Dextérité](./Dextérité.md) à la [CA](./CA.md).*
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE5}*(5) Un personnage [enchevêtré](./Enchevêtré.md) subit également un malus de -4 en [Dextérité](./Dextérité.md).*
|- CLASS="note"
| COLSPAN="3" | {s:Reference|NOTE6}*(6) Le défenseur perd son éventuel bonus de [Dextérité](./Dextérité.md) à la [CA](./CA.md).*
|}
</td></tr></table>

{s:Reference|ABRI}
### Abri
{s:Desambi|Abri est également le nom d'un [sort](./sort Abri.md).}
Pour déterminer si une cible bénéficie d’un abri lorsque le personnage l’attaque à distance, il doit choisir un des coins de la case qu’il occupe. Si au moins une des lignes qui mènent de cet angle à l’un des angles de la case occupée par la cible passe par une case ou une bordure qui bloque la ligne d’effet ou fournit un abri, ou si elle traverse une case occupée par une créature, la cible bénéficie d’un abri (bonus de +4 à la [CA](./CA.md)).

Lorsqu’un personnage frappe au corps à corps une cible adjacente, elle bénéficie d’un abri si n’importe quelle ligne située entre la case du personnage et la sienne traverse un mur (y compris un muret). Lorsqu’un personnage attaque au corps à corps une cible qui n’est pas adjacente (avec une arme à allonge par exemple), on utilise la règle des armes à distance pour savoir si la cible bénéficie d’un abri.

**Abri et obstacles bas.** Un obstacle bas (comme un muret arrivant à la ceinture du personnage) fournit un abri, mais uniquement aux créatures distantes de moins de 9 m (6 cases) de cet obstacle. L’attaquant peut ignorer l’abri s’il est plus près de l’obstacle que sa cible.

**Abri et attaques d’opportunité.** Un personnage ne peut pas porter d’[attaque d’opportunité](./attaque dopportunité.md) contre une cible qui bénéficie d’un abri.

**Abri et bonus aux jets de [Réflexes](./Réflexes.md).** Un abri confère un bonus de +2 aux jets de [Réflexes](./Réflexes.md) contre les attaques dont le point d’origine ou le centre de rayonnement se situe de l’autre côté de l’abri par rapport au personnage. Les effets de type « étendue » peuvent contourner les coins et ne tiennent donc pas compte de l’abri.

**Abri et tests de [Discrétion](./Discrétion.md).** Un personnage peut utiliser un abri pour faire un test de [Discrétion](./Discrétion.md). Sans abri, il a généralement besoin d’un [camouflage](./camouflage.md) (voir ci-dessous).

**Abri mou.** Une créature, même ennemie, peut fournir un abri contre les attaques à distance, ce qui offre un bonus de +4 à la [CA](./CA.md). Cependant, un abri mou n’offre aucun bonus aux jets de [Réflexes](./Réflexes.md) et ne permet pas de test de [Discrétion](./Discrétion.md).

**Abri et créatures de taille supérieure à la moyenne.** Au corps à corps, on détermine la présence d’un abri de manière légèrement différente pour les créatures qui occupent un espace supérieur 1,50 mètre (1 case) que pour les créatures plus petites. Ces créatures peuvent choisir n’importe laquelle des cases qu’elles occupent pour déterminer si leur adversaire bénéficie d’un abri. Inversement, lorsqu’un personnage attaque une de ces créatures, il peut choisir n’importe laquelle des cases qu’elle occupe pour déterminer si elle bénéficie d’un abri.

{s:Reference|abri partiel}
**Abri partiel.** Si une créature bénéficie d’un abri mais que son adversaire voit tout de même plus de la moitié de son corps, le bonus d’abri est réduit à +2 à la [CA](./CA.md) et +1 au jet de [Réflexes](./Réflexes.md). Cet abri partiel est laissé à l’appréciation du [MJ](./MJ.md).

{s:Reference|abri total}
**Abri total.** Lorsqu’un personnage ne peut tracer de ligne d’effet entre une créature et lui (c’est à dire s’il ne peut pas tirer une ligne entre sa case et celle de sa cible sans traverser une barrière solide), la créature bénéficie d’un abri total par rapport au personnage. Il ne peut pas attaquer une créature qui bénéficie d’un abri total.

{s:Reference|abri amélioré}
**Abri amélioré.** Dans certains cas, comme quand un personnage attaque une créature cachée derrière une meurtrière, l’abri peut offrir un bonus plus important à la [CA](./CA.md) et aux jets de [Réflexes](./Réflexes.md). Dans ce cas, le bonus habituel à la [CA](./CA.md) et aux [Réflexes](./Réflexes.md) est doublé (passant respectivement à +8 et à +4). Une créature qui dispose de ce type d’abri gagne une [esquive surnaturelle](./esquive surnaturelle.md) contre toutes les attaques contre lesquelles elle peut faire un jet de [Réflexes](./Réflexes.md). De plus, un abri amélioré offre un bonus de +10 aux tests de [Discrétion](./Discrétion.md).

<table><tr style="vertical-align: top">
<td><img src="http://www.pathfinder-fr.org/images/pathfinder/wiki/PRPG/Abri.jpg"></td><td>
<div style="background-color: #f3efe2; padding: 6px; margin: 0 0 0 2px">
Cas #1 : Le [guerrier](./Guerrier.md) est adjacent à l’[ogre](./Ogre.md) et rien ne l’empêche de l’atteindre. L’[ogre](./Ogre.md) n’a donc pas d’abri contre le [guerrier](./Guerrier.md).

Cas #2 : Le [roublard](./Roublard.md) est adjacent à l’[ogre](./Ogre.md) mais les lignes qui relient les angles de sa case à ceux de celle de l’[ogre](./Ogre.md) traversent un mur. L’[ogre](./Ogre.md) bénéficie donc d’un abri au corps à corps mais, s’il veut l’attaquer, le [roublard](./Roublard.md) n’aura pas d’abri à cause de l’allonge du monstre (il attaque comme s’il disposait d’une arme à distance).

Cas #3 : Le [prêtre](./Prêtre.md) attaque à distance et il doit donc se servir de l’un des angles de sa case pour déterminer les abris. L’une des lignes qui partent de cet angle traverse une surface solide : l’[ogre](./Ogre.md) bénéficie donc d’un abri.

Cas #4 : L'[ensorceleur](./Ensorceleur.md) attaque aussi à distance mais ses lignes indiquent qu’il voit clairement plus de la moitié de l’[ogre](./Ogre.md). L’[ogre](./Ogre.md) bénéficie donc seulement un abri partiel.
</div></td></tr></table>

{s:Reference|CAMOUFLAGE}
### Camouflage
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Combat).md#17) Camouflage et dégâts de précision : Le camouflage (celui de 20 %, pas le camouflage total) annule-t-il toute forme de dégâts de précision ? Il y a quelques zones floues sur les différents textes où des dégâts de précision apparaissent.***

Oui, le <u>[camouflage](./Modificateurs de combat.md#CAMOUFLAGE)</u> en général annule toute forme de dégâts de précision, sauf si le personnage possède une capacité spéciale qui contredit explicitement cette règle comme le don [Coup dans l’ombre](./Coup dans lombre.md) ou l’[attaque sournoise](./Roublard unchained.md#ATTAQUESOURNOISE) du roublard unchained.}Pour déterminer si une cible bénéficie d’un camouflage vis à vis d’une attaque à distance, le personnage doit choisir un des coins de sa case. Si au moins une des lignes qui mènent de cet angle à l’un des angles de la case de la cible passe par une case ou une bordure qui fournit un camouflage, la cible est camouflée.

Lorsqu’un personnage attaque une cible adjacente au corps à corps, elle bénéficie d’un camouflage si sa case est entièrement contenue dans un effet qui offre un camouflage. Lorsqu’un personnage frappe une cible qui n’est pas adjacente, le personnage utilise la règle des armes à distance pour déterminer si sa cible est camouflée.

De plus, certains effets magiques confèrent un camouflage contre toutes les attaques, que le personnage bénéficie d’un camouflage réel ou non.

**Chance de rater.** Le camouflage offre à la cible d’une attaque réussie 20% de chances que cette attaque la rate à cause du camouflage. Le personnage porte son attaque comme à l’accoutumée, si elle touche, sa cible lance un d% pour savoir si le personnage l’a finalement ratée à cause de son camouflage. Les divers types de camouflage ne se cumulent pas.

**Camouflage et tests de [Discrétion](./Discrétion.md).** Un personnage peut utiliser un camouflage pour faire un test de [Discrétion](./Discrétion.md). Sinon, il a besoin d’un [abri](./abri.md).

{s:Reference|CAMOUFLAGETOTAL}**Camouflage total.** Lorsqu’un personnage peut tracer une ligne d’effet jusqu’à sa cible mais qu’elle est pourtant hors de vue, elle bénéficie d’un camouflage total. Il ne peut attaquer une créature qui bénéficie d’un camouflage total mais il peut attaquer la case où la cible se trouve d’après lui. S’il réussit son attaque réussie contre une case où se trouve effectivement un ennemi bénéficiant d’un camouflage total, le personnage a 50% de risques d’échec (au lieu des 20% habituels).

Un personnage ne peut pas faire d’[attaque d’opportunité](./attaque dopportunité.md) contre un adversaire bénéficiant d’un camouflage total, même s’il sait quelle(s) case(s) il occupe.

**Ignorer le camouflage.** Un camouflage n’est pas toujours efficace. Par exemple, une zone faiblement éclairée ou sombre ne fournit aucun camouflage contre un adversaire qui voit dans le noir. Rappelez-vous aussi que les personnages doués de [vision nocturne](./vision nocturne.md) voient plus loin que les autres dans des conditions d’éclairage identiques.

Bien que l’invisibilité procure un camouflage total, le personnage peut tout de même déceler la position d’une créature [invisible](./Invisible.md) à l’aide d’un test de [Perception](./Perception.md). Un personnage invisible bénéficie d’un bonus de +20 aux tests de [Discrétion](./Discrétion.md) s’il se déplace et de +40 s’il reste immobile (bien que ses adversaires ne puissent le voir, ils peuvent le repérer grâce aux indices qu’il laisse dans l’environnement).

**Degrés de camouflage.** Dans certaines situations, le camouflage habituel peut être plus ou moins efficace, il faut donc modifier les chances de rater une cible en conséquence.

{s:REFERENCE|PRISEENTENAILLE}
### Prise en tenaille
Lors d'une attaque de corps à corps, un personnage bénéficie d’un bonus de prise en tenaille de +2 au [jet d’attaque](./jet dattaque.md) contre un adversaire donné si une personne ou une créature alliée se trouve sur un bord ou un coin opposé de la case de l’adversaire et contrôle l’espace de cet adversaire.

En cas de doute sur une prise en tenaille, il faut tracer une ligne imaginaire entre le centre des cases des deux alliés. Si cette ligne traverse deux bords opposés de l’espace occupé par l’adversaire (y compris les coins de ses bords), l’adversaire est pris en tenaille.

**Exception.** Si une créature occupe plusieurs cases, elle peut choisir n’importe laquelle de ces cases pour déterminer si elle prend un adversaire en tenaille.

Seul un allié qui menace un adversaire peut aider un allié à le prendre en tenaille.

Les créatures ayant une allonge de 0 m ne peuvent prendre un adversaire en tenaille.

<table><tr style="vertical-align: top">
<td><img src="http://www.pathfinder-fr.org/images/pathfinder/wiki/PRPG/Tenaille.jpg"></td><td>
<div style="background-color: #f3efe2; padding: 6px; margin: 0 0 0 2px">
Cas #1 : Le [guerrier](./Guerrier.md) et le [prêtre](./Prêtre.md) prennent l’[ogre](./Ogre.md) en tenaille car si on trace une ligne entre eux, celle-ci traverse deux bords opposés de l’espace occupé par l’[ogre](./Ogre.md). Le [guerrier](./Guerrier.md) et le [prêtre](./Prêtre.md) bénéficient donc tous deux d’un bonus de +2 aux [jets d’attaque](./jet dattaque.md) contre l’[ogre](./Ogre.md).

Cas #2 : Le [roublard](./Roublard.md) ne prend pas l’[ogre](./Ogre.md) en tenaille car si on trace une ligne entre lui et le [guerrier](./Guerrier.md) ou lui et le [prêtre](./Prêtre.md), cette ligne ne traverse pas deux bords opposés de l’espace occupé par l’[ogre](./Ogre.md). Le [roublard](./Roublard.md) ne peut pas tracer une ligne avec l'[ensorceleur](./Ensorceleur.md) car ce dernier n’est pas adjacent à l’[ogre](./Ogre.md) et ne le menace pas.

Cas #3 : Le [gobelin](./Gobelin.md) et l’[ogre](./Ogre.md) prennent l'[ensorceleur](./Ensorceleur.md) en tenaille car si on trace une ligne entre eux, celle-ci traverse deux bords opposés de l’espace occupé par l'[ensorceleur](./Ensorceleur.md). En revanche, si l’[ogre](./Ogre.md) n’avait pas d’allonge, il ne pourrait pas prendre l'[ensorceleur](./Ensorceleur.md) en tenaille avec le [gobelin](./Gobelin.md).
</div></td></tr></table>

{s:Reference|SANSDEFENSE}
### Cible sans défense
{s:Desambi|Voir aussi l'état préjudiciable [sans défense](./Sans défense.md).}
Un adversaire peut être sans défense parce qu’il est [ligoté](./Immobilisé.md), endormi, [paralysé](./Paralysé.md), [inconscient](./Inconscient.md) ou à la merci du personnage pour une autre raison.

**Attaque normale.** Un personnage sans défense subit un malus de -4 à la [CA](./CA.md) contre les attaques de corps à corps. De plus, on considère que sa valeur de [Dextérité](./Dextérité.md) est égale à 0, ce qui lui inflige un malus de -5 à la [CA](./CA.md) contre les attaques au corps à corps et à distance (pour un total de -9 contre les attaques de corps à corps et de -5 contre les attaques à distance). Un personnage sans défense est également [pris au dépourvu](./Pris au dépourvu.md).

{s:Reference|COUPDEGRACE}
**Coup de grâce.** Par une [action complexe](./Action complexe.md), un personnage peut tenter d’achever un adversaire sans défense en lui donnant un coup de grâce à l’aide d’une arme de corps à corps. Cette attaque peut également être portée avec un arc ou une arbalète, à condition que le personnage soit adjacent à sa cible.

L’attaque touche automatiquement et inflige un [coup critique](./coup critique.md). Même si la cible survit aux dégâts, elle meurt si elle rate un jet de [Vigueur](./Vigueur.md) [DD](./DD.md)  10 + dégâts infligés. Un [roublard](./Roublard.md) peut également ajouter ses dégâts d’[attaque sournoise](./Roublard.md#ATTAQUESOURNOISE) à ceux du [coup critique](./coup critique.md) quand il donne un coup de grâce à un adversaire sans défense.

Un coup de grâce provoque une [attaque d’opportunité](./attaque dopportunité.md) de la part des adversaires adjacents.

Il est impossible d’asséner un coup de grâce aux créatures immunisées contre les [coups critiques](./coup critique.md). On peut donner le coup de grâce à une créature qui bénéficie d’un [camouflage total](./Modificateurs de combat.md#CAMOUFLAGETOTAL), mais cela nécessite deux [actions complexes](./Action complexe.md) consécutives, une pour trouver sa cible et la seconde pour porter le coup de grace.
