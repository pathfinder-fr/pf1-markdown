---
Name: Pathfinder-RPG.Déplacements
Title: Les déplacements
LastModified: 2024-08-29 15:32
Categories:
- Règle officielle
- Src Manuel des joueurs
---

<div style="float: right; padding: 0 0 8px 8px"><nav class="wiki-toc"></nav></div>On distingue trois types de déplacement :
- Tactique, pour le combat, mesuré en mètres (ou en cases) par round.
- Sur courte distance, pour explorer un secteur, en mètres par minute.
- Sur longue distance, pour se rendre d’un endroit à un autre, en kilomètres par heure ou par jour.

{s:ClearRight}
<div style="float:right; background-color: #fff; padding: 0 0 16px 16px">
<div style="border: 1px solid #4b3124; padding: 4px">
{| CLASS="tablo centre"
|+ Déplacements et distance
|- CLASS="titre"
| [VD](./vitesse de déplacement.md) || 4,50 m (3 cases) || 6 m (4 cases) || 9 m (6 cases) || 12 m (8 cases)
|- CLASS="premier"
| COLSPAN="5" | **UN ROUND (TACTIQUE)***
|-
| &emsp;[Marche](./Déplacements.md#MARCHE) || 4,50 m || 6 m || 9 m || 12 m
|- CLASS="alt"
| &emsp;[Footing](./Déplacements.md#FOOTING) || 9 m || 12 m || 18 m || 24 m
|-
| &emsp;[Course](./Déplacements.md#COURSE) (x3) || 13,50 m || 18 m || 27 m || 36 m
|- CLASS="alt"
| &emsp;[Course](./Déplacements.md#COURSE) (x4) || 18 m || 24 m || 36 m || 48 m
|- CLASS="premier"
| COLSPAN="5" | **UNE MINUTE (COURTE DISTANCE)**
|-
| &emsp;[Marche](./Déplacements.md#COURTEMARCHE) || 45 m || 60 m || 90 m || 120 m
|- CLASS="alt"
| &emsp;[Footing](./Déplacements.md#COURTEFOOTING) || 90 m || 120 m || 180 m || 240 m
|-
| &emsp;[Course](./Déplacements.md#COURTECOURSE) (x3) || 135 m || 180 m || 270 m || 360 m
|- CLASS="alt"
| &emsp;[Course](./Déplacements.md#COURTECOURSE) (x4) || 180 m || 240 m || 360 m || 480 m
|- CLASS="premier"
| COLSPAN="5" | **UNE HEURE / UN JOUR (LONGUE DISTANCE)**
|-
| &emsp;[Marche](./Déplacements.md#LONGUEMARCHE) || 2,25 km / 18 km || 3 km / 24 km || 4,5 km / 36 km || 6 km / 48 km
|- CLASS="alt"
| &emsp;[Footing](./Déplacements.md#LONGUEFOOTING) || 4,5 km / — || 6 km / — || 9 km / — || 12 km / —
|-
| &emsp;[Course](./Déplacements.md#LONGUECOURSE) || — / — || — / — || — / — || — / —
|- CLASS="note"
| COLSPAN="5" | *(*) Les mouvements tactiques sont souvent mesurés en cases plutôt qu’en mètres. Une case fait 1,50 mètre de côté.*
|}
</div></div>
**Modes de déplacement.** La marche, le footing et la course représentent les trois cadences de mouvement le plus communément adoptées.

{s:Reference|MARCHE}*Marche.* En se déplaçant normalement et sans s’arrêter, un [humain](./Humain.md) non chargé parcourt généralement 4,5 km en une heure.

{s:Reference|FOOTING}*Footing.* Le footing est un déplacement en petites foulées qui permet à un [humain](./Humain.md) de parcourir de 9 km/h quand il n’est pas chargé. Il équivaut à un personnage se déplaçant deux fois dans le même [round](./round.md), ou effectuant une autre [action](./Types dactions.md) (attaque, incantation ou autre action de mouvement), puis se déplaçant dans le même [round](./round.md).

{s:Reference|COURSE}*Course (x3).* Se déplacer à trois fois sa vitesse de déplacement est le rythme de course pour un personnage en [armure lourde](./armure lourde.md). Cela correspond environ à 10,5 km/h pour un [humain](./Humain.md) en [harnois](./Tableau récapitulatif des armures.md).

*Course (x4).* Cette cadence plus rapide est réservée aux personnages sans armure ou en [armure légère](./armure légère.md) ou [intermédiaire](./armure intermédiaire.md). Elle correspond environ à 18 km/h pour un [humain](./Humain.md) non chargé, et à 13,5 km/h pour un [humain](./Humain.md) en [cotte de mailles](./Tableau récapitulatif des armures.md). Référez-vous à la table ci-contre pour plus de détails.

### Déplacement tactique
On utilise ce déplacement lors d’un combat. Dans cette situation, il est évident que les personnages ne marchent pas, ils courent ou se déplacent en petites foulées. Un personnage qui se déplace normalement avant d’accomplir une autre [action](./Types dactions.md) trottine pendant la première moitié du [round](./round.md) puis fait autre chose pendant l’autre moitié.

<div style="float:right; background-color: #fff; padding: 0 0 16px 16px">
<div style="border: 1px solid #4b3124; padding: 4px">
{| CLASS="tablo centre"
|+  Déplacements contrariés
|- CLASS="titre"
| Condition || Coût supplémentaire   
du déplacement
|- CLASS="premier"
| Terrain difficile || ×2
|- CLASS="alt"
| Obstacle* || ×2
|-
| Mauvaise visibilité || ×2
|- CLASS="alt"
| Infranchissable || —
|- CLASS="note"
| COLSPAN="2" | *(*) Peut nécessiter un test de compétence.*
|}
</div></div>
{s:Reference|TERRAINDIFFICILE}**Déplacements contrariés.** Un terrain difficile, des obstacles ou une mauvaise visibilité ralentissent les déplacements (voir le tableau ci-contre). Dans ce cas, chaque case de mouvement compte généralement comme deux cases de déplacement, ce qui réduit de moitié la [vitesse](./Valeurs de combat.md#VITESSEDEDEPLACEMENT) des personnages.

Lorsque plusieurs conditions s’appliquent, il faut multiplier entre eux les différents coûts de déplacement (c’est une exception à la règle générale sur les multiplicateurs multiples).

Il arrive que le terrain soit si encombré et si difficile qu’une [action de mouvement](./Action de mouvement.md) ne suffit pas à avancer de 1,50 mètre (une seule case). Dans ce cas, il faut faire une [action complexe](./Action complexe.md) pour parcourir 1,50 mètre (une case) dans n’importe quelle direction, même en diagonale. Bien que cela ressemble à un [pas de placement](./Pas de placement.md), ce n’est pas le cas et ce mouvement provoque les [attaques d’opportunité](./attaque dopportunité.md) habituelles. (Le personnage ne peut pas utiliser cette règle pour traverser un espace infranchissable ou de se déplacer alors que tout mouvement lui est interdit).

Il est impossible de courir ou de [charger](./charge.md) à travers une case où les mouvements du personnage sont contrariés.

### Déplacement sur courte distance
Les personnages explorant un secteur utilisent le déplacement sur courte distance, qui s’exprime en mètres par minute.

{s:Reference|COURTEMARCHE}**Marche.** Le personnage peut marcher sans difficulté sur courte distance.

{s:Reference|COURTEFOOTING}**Footing.** Le personnage peut courir sans problème en petites foulées sur une courte distance. Voir Déplacement sur longue distance, ci-dessous, pour les déplacements exprimés en heures.

{s:Reference|COURTECOURSE}**Course.** Un personnage peut courir pendant un nombre de [rounds](./round.md) égal à son score de [Constitution](./Constitution.md) sans avoir besoin de faire une pause. (Voir aussi les [règles](./Actions complexes.md#COURIR) concernant les longues périodes de course).

{s:Reference|LONGUEDISTANCE}
### Déplacement sur longue distance
Les personnages utilisent ce type de déplacement pour parcourir la campagne. Les déplacements sur longue distance s’expriment en kilomètres par heure ou en kilomètres par jour. Une journée correspond à 8 heures de trajet effectif. La journée passe à 10 heures pour une embarcation à rames et à vingt-quatre pour un navire à voiles.

{s:Reference|LONGUEMARCHE}**Marche.** Un personnage peut sans problème marcher huit heures par jour. Il peut continuer plus longtemps mais il risque de s’épuiser (voir Marche forcée, ci-dessous).

{s:Reference|LONGUEFOOTING}**Footing.** Trottiner une heure durant ne constitue pas une difficulté, en revanche, poursuivre son effort sans dormir entre-temps inflige 1 point de [dégâts non-létaux](./Dégâts non-létaux.md) lors de la deuxième heure. Pendant les heures suivantes, le personnage subit le double des dégâts reçus pendant l’heure précédente. Un personnage qui subit des [dégâts non-létaux](./Dégâts non-létaux.md) à cause d’un footing devient aussitôt [fatigué](./Fatigué.md).

Un personnage [fatigué](./Fatigué.md) ne peut ni [courir](./courir.md) ni [charger](./charge.md) et subit un malus de -2 à la [Force](./Force.md) et à la [Dextérité](./Dextérité.md). Éliminer les [dégâts non-létaux](./Dégâts non-létaux.md) élimine aussi la [fatigue](./Fatigue.md).

{s:Reference|LONGUECOURSE}**Course.** Il est impossible de courir sur une longue période. Un personnage qui alterne course et temps de repos progresse comme s’il faisait un [footing](./Déplacements.md#FOOTING).

**Terrain.** La nature du terrain traversé affecte la distance que l’on peut parcourir en une heure ou une journée (voir le tableau ci-dessous). Une grand-route est une artère principale droite et pavée, une route est en général une piste de terre battue et un sentier ressemble à une route qui permet seulement de voyager en file indienne, sans véhicule. Enfin, un terrain vierge n’offre pas la moindre piste.

{| CLASS="tablo centre autoalt"
|+ Terrain et déplacements sur longue distance
|- CLASS="titre"
| Terrain || Grande route || Chemin ou route || Terrain vierge
|- CLASS="premier"
| Broussailles || ×1 || ×1 || ×3/4
|-
| Collines || ×1 || ×3/4 || ×1/2
|-
| Désert de sable || ×1 || ×1/2 || ×1/2
|-
| Forêt || ×1 || ×1 || ×1/2
|-
| Jungle || ×1 || ×3/4 || ×1/4
|-
| Marais || ×1 || ×3/4 || ×1/2
|-
| Montagnes || ×3/4 || ×3/4 || ×1/2
|-
| Plaine || ×1 || ×1 || ×3/4
|-
| Toundra gelée || ×1 || ×3/4 || ×3/4
|}

{s:Reference|MARCHEFORCEE}**Marche forcée.** Au cours d’une journée normale, le personnage marche 8 heures durant. Le reste du temps, il monte le campement pour la nuit (ou replie les tentes le matin venu), se repose et mange.

Mais il est possible de continuer son chemin en ayant recours à la marche forcée. Pour chaque heure de marche au-delà des 8 heures de base, le personnage doit effectuer un [test](./../Golarion/Test.md) de [Constitution](./Constitution.md) ([DD](./DD.md) 10 + 2 par heure supplémentaire). Un échec se traduit par 1d6 points de [dégâts non-létaux](./Dégâts non-létaux.md). Un personnage qui subit des [dégâts non-létaux](./Dégâts non-létaux.md) à cause d’une marche forcée devient aussitôt [fatigué](./Fatigué.md). Éliminer les [dégâts non-létaux](./Dégâts non-létaux.md) élimine aussi la [fatigue](./Fatigue.md). On peut sombrer dans l’[inconscience](./États préjudiciables.md#Inconscient) à force de marcher trop longtemps.

**Déplacement à cheval.** Un cheval portant un cavalier peut avancer au trot (équivalent du [footing](./Déplacements.md#FOOTING)) mais, dans ce cas, les dégâts qu’il subit sont [létaux](./Dégâts létaux.md), plutôt que [non-létaux](./Dégâts non-létaux.md). De même, on peut le pousser en permanence, ce qui correspond à une marche forcée, mais il rate automatiquement ses [tests](./../Golarion/Test.md) de [Constitution](./Constitution.md) et, là encore, il encaisse des [dégâts létaux](./Dégâts létaux.md). Les montures deviennent elles aussi fatiguées si elles subissent des [dégâts non-létaux](./Dégâts non-létaux.md) à cause d’un [footing](./Déplacements.md#FOOTING) ou d’une marche forcée. La vitesse des chevaux et des véhicules tirés par des animaux de trait est présentée dans le tableau ci-dessous.

**Déplacement en bateau.** Voir la table ci-dessous pour la vitesse des diverses embarcations.

{| CLASS="tablo centre"
|+ Montures et véhicules
|- CLASS="titre"
| Monture/véhicule || Par heure || Par jour
|- CLASS="premier"
| COLSPAN="3" | **MONTURE (CHARGE)**
|-
| &emsp;Cheval léger || 7,5 km || 60 km
|- CLASS="alt"
| &emsp;Cheval léger (87,5–262,5 kg)<sup>[1](./Déplacements.md#NOTE1)</sup> || 5,25 km || 42 km
|-
| &emsp;Cheval lourd || 7,5 km || 60 km
|- CLASS="alt"
| &emsp;Cheval lourd (114,5–345 kg)<sup>[1](./Déplacements.md#NOTE1)</sup> || 5,25 km || 42 km
|-
| &emsp;Poney || 6 km || 48 km
|- CLASS="alt"
| &emsp;Poney (75,5–225 kg)<sup>[1](./Déplacements.md#NOTE1)</sup> || 4,5 km || 36 km
|-
| &emsp;Chien de selle || 6 km || 48 km
|- CLASS="alt"
| &emsp;Chien de selle (50,5–150 kg)<sup>[1](./Déplacements.md#NOTE1)</sup> || 4,5 km || 36 km
|-
| &emsp;Chariot ou charrette || 3 km || 24 km
|- CLASS="premier"
| COLSPAN="3" | **BATEAU (MODE DE LOCOMOTION)**
|-
| &emsp;Radeau ou barge (perche ou tracté)<sup>[2](./Déplacements.md#NOTE2)</sup> || 750 m || 7,5 km
|- CLASS="alt"
| &emsp;Bateau à fond plat (rames)<sup>[2](./Déplacements.md#NOTE2)</sup> || 1,5 km || 15 km
|-
| &emsp;Barque (rames)<sup>[2](./Déplacements.md#NOTE2)</sup> || 2,25 km || 22,5 km
|- CLASS="alt"
| &emsp;Navire de haute mer (voiles) || 3 km || 72 km
|-
| &emsp;Vaisseau de guerre (voiles ou rames) || 3,75 km || 90 km
|- CLASS="alt"
| &emsp;Drakkar (voiles ou rames) || 4,5 km || 108 km
|-
| &emsp;Trirème (voiles ou rames) || 6 km || 144 km
|}

{s:Reference|NOTE1}*(1) Les quadrupèdes, comme les chevaux, peuvent transporter une charge plus importante qu’un personnage. Voir les règles sur les [charges transportables](./Poids transportable.md).*

{s:Reference|NOTE1}*(2) Radeaux, barges, bateaux à fond plat et barques ne s’utilisent que sur les lacs et les cours d’eau. S’ils descendent le courant, on ajoute la vitesse de ce dernier (généralement 5 km/h). Un personnage peut ramer dix heures durant mais il peut laisser dériver l’embarcation pendant les quatorze heures restantes si quelqu’un la guide. Ce système permet d’augmenter la distance parcourue de soixante-trois kilomètres par jour. Ces frêles esquifs ne permettent pas de remonter le courant, par contre, des animaux de trait peuvent les hâler depuis la berge.*

### Évasion et poursuite
Dans un déplacement au [round](./round.md) par [round](./round.md), quand on se contente de compter les cases, un personnage lent ne peut pas échapper à un personnage rapide et déterminé sans recourir à un concours de circonstances. De même, un personnage rapide n’a aucun mal à échapper à un personnage plus lent.

Quand les deux personnages se déplacent à la même [vitesse](./vitesse de déplacement.md), la chasse est très simple : si une créature en poursuit une autre et qu’elles se déplacent toutes deux à la même [vitesse](./vitesse de déplacement.md), la poursuite continue sur quelques [rounds](./round.md) avant qu’elles fassent des [tests](./../Golarion/Test.md) de [Dextérité](./Dextérité.md) opposés pour savoir laquelle s’est déplacée le plus rapidement pendant ces quelques [rounds](./round.md). Si la créature pourchassée gagne, elle parvient à s’enfuir, sinon, son poursuivant la rattrape.

Il arrive que la poursuite se déroule sur une [longue distance](./Déplacements.md#LONGUEDISTANCE) et dure toute la journée, les deux créatures s’apercevant de temps à autre dans le lointain. Dans ce cas, c’est un [test](./../Golarion/Test.md) de [Constitution](./Constitution.md) qui décidera laquelle maintient son allure le plus longtemps. Si la créature pourchassée gagne, elle parvient à s’enfuir, sinon, son poursuivant, plus résistant, finit par la rattraper.
