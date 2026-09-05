---
Name: Pathfinder-RPG.Poisons
Title: Les poisons
LastModified: 2025-01-19 21:47
Categories:
- Src Armes et équipement
---

{s:MenuEquipement}
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Maîtrise).md#7) Poison : Comment est-ce que le poison se cumule avec lui-même exactement ? Quand et comment les jets de sauvegarde sont fait ? Comment déterminer le DD du prochain jet quand la cible est exposée à plus d'une dose du poison à la fois ?***

Un personnage a droit à un jet de sauvegarde contre un <u>[poison](./Poisons.md)</u> dès qu'il y est exposé (par exemple quand il est touché par une attaque qui utilise du poison). Le DD du jet de sauvegarde de ce poison est indiqué dans la description dudit poison, mais est augmenté de 2 pour chaque dose de poison qui affecte actuellement la cible (sans compter la dose contre laquelle le jet est effectué). Les poisons dont le personnage a guéri ou qui ont expiré ne comptent pas. De plus, une créature empoisonnée doit effectuer un jet de sauvegarde contre le poison une fois à son tour, mais cela peut être fait n'importe quand pendant son tour. Le jet ne peut pas être retardé en préparant ou en retardant une action. Pour plus d'informations sur les poisons et leur cumul, voir la [FAQ sur le poison](./../Ressources/Concepteur004.md).}{s:Desambi|Il peut aussi s'agir d'une [capacité de monstre](./Poison (capacité).md).}
{s:AE}*Le poison est une substance qui interfère avec les fonctions physiques naturelles des créatures vivantes, entraînant des lésions et la mort. En général, il suffit d’utiliser une dose infime.*

<div style="background-color: #fff; float: right; padding: 0 0 12px 12px"><nav class="wiki-toc"></nav></div>La cible d’un poison peut lui résister en réussissant un jet de sauvegarde. On peut ralentir ou soigner les effets du poison avec des sorts comme *[ralentissement du poison](./Ralentissement du poison.md)* ou *[neutralisation du poison](./Neutralisation du poison.md)*.

Les poisons sont répartis en quatre catégories en fonction de la manière dont ils atteignent la cible : contact, ingestion, inhalation ou blessure.
- **Blessure.** Ces poisons agissent essentiellement lorsque certaines créatures réussissent une attaque ou par l’intermédiaire d’armes enduites de la toxine. En général, les poisons de blessure n’ont pas de *temps d’incubation* et ont une *fréquence* de 1 minute.
- **Contact.** Ces poisons agissent au moment où ils entrent en contact avec la peau de la créature. Ils s’utilisent aussi comme des poisons de blessure. Les poisons de contact ont généralement un *temps d’incubation* de 1 minute et une *fréquence* de 1 minute.
- **Ingestion.** Ces poisons agissent au moment où la créature les ingère ou les boit. Les poisons d’ingestion ont généralement un *temps d’incubation* de 10 minutes et une *fréquence* de 1 minute.
- **Inhalation.** Ces poisons agissent au moment où la créature pénètre dans une zone contaminée et, en général, n’ont pas de temps d’incubation. Pour la plupart des poisons inhalés, 1 dose permet de remplir un cube de 3 mètres de côté. La créature peut tenter de retenir son souffle lorsqu’elle est dans la zone, pour éviter de respirer la toxine. Une créature retenant son souffle a 50% de chances de ne pas avoir à faire de jet de [Vigueur](./Vigueur.md) tous les [rounds](./round.md). Reportez-vous aux règles concernant le fait de [retenir son souffle](./Dangers naturels.md#ASPHYXIE) et la [suffocation](./Dangers naturels.md#ASPHYXIE). Si une créature retient son souffle et rate un test de [Constitution](./Constitution.md) pour continuer, plutôt que de suffoquer, elle reprend son souffle normalement (et subit les effets du poison inhalé s’il emplit toujours la zone).

#### Application du poison
Une dose de poison appliquée sur une arme ou sur un autre objet n’affecte qu’une seule cible. Une arme ou un objet empoisonné conserve le poison jusqu’à ce que l’arme touche une cible ou jusqu’à ce que l’objet soit touché (à moins que le poison ne soit nettoyé avant que la cible n’entre en contact avec). L’application de poison sur une arme ou sur une munition coûte une [action simple](./Action simple.md). Que le personnage applique ou prépare le poison pour utilisation, il a 5% de chances de s’y exposer et doit réussir un [jet de sauvegarde](./JDS.md) normal contre le poison. Ceci ne consomme pas la dose de poison. Lorsque le personnage attaque avec une arme empoisonnée, il s’expose lui-même au poison s’il fait un 1 naturel à son [jet d’attaque](./jet dattaque.md). Ceci consomme le poison de l’arme. Si le personnage a la capacité de classe [utilisation des poisons](./Alchimiste.md#UTILISATIONDUPOISON) (issue, par exemple, de la classe de prestige [assassin](./Assassin.md) ou de la classe de base [alchimiste](./Alchimiste.md)), il ne risque pas de s’empoisonner accidentellement lorsqu’il applique le poison sur une arme.

#### Doses multiples de poison
Contrairement aux autres afflictions, les poisons « cumulent » leurs effets, ce qui signifie que l’application de plusieurs doses d’un même poison augmente son [DD](./DD.md) et sa durée. Si la victime réussit son premier [jet de sauvegarde](./JDS.md) contre un poison, ses effets ne se cumulent pas : le poison n’affecte pas le personnage et toutes les autres doses sont traitées indépendamment. De même, si un poison a été neutralisé ou s’il ne fait plus effet (que ce soit parce que le personnage a réussi ses jets de sauvegarde ou s’il a survécu à sa durée du poison), les effets ne se cumulent pas. Néanmoins, s’il y a encore du poison actif dans l’organisme du personnage au moment où il est de nouveau affecté par le même poison, les effets se cumulent s’il rate son premier [jet de sauvegarde](./JDS.md) contre la nouvelle dose. Ceci a deux effets qui durent jusqu’à ce que les poisons se dissipent.
- **Durée augmentée.** Augmentez la durée du poison de la moitié de la *fréquence* indiquée.
- **DD augmenté.** Augmentez le [DD](./DD.md) du poison de +2.
Ces augmentations sont cumulables (une troisième dose rajoute la moitié de la *fréquence* à la durée et encore +2 au [DD](./DD.md) etc.) Lorsque le personnage est affecté par plusieurs doses d’un même poison, il ne fait qu’un seul [jet de sauvegarde](./JDS.md) contre le [DD](./DD.md) le plus élevé à chaque fois que l’exige la *fréquence* indiquée et non un [jet de sauvegarde](./JDS.md) pour chaque dose de poison.
Les multiples doses de poison n’altèrent pas la condition de *guérison* du poison. Si elle est remplie, elle neutralise toutes les doses reçues.
Les poisons de contact et de blessure infligent seulement une dose de poison par arme (le poison de l’arme disparaissant après la première attaque réussie). Les poisons inhalés et ingérés peuvent infliger les effets de plusieurs doses à la fois.
Les doses de poisons différents (si un [assassin](./Assassin.md) combine l’extrait de sanvert de sa dague avec le venin d’araignée de taille M de son épée courte) ne se cumulent pas : les effets de chacun sont traités indépendamment.
- **Exemples.** Un guerrier fait face à trois araignées de taille M (qui inoculent du venin d’araignée de taille M sur une morsure réussie). Le venin de l’araignée de taille M a normalement une *fréquence* de 4 [rounds](./round.md) et un [DD](./DD.md) de 14. Lors du premier [round](./round.md), les trois araignées mordent le guerrier qui rate ses trois [jets de sauvegarde](./JDS.md). Les deuxième et troisième doses augmentent chacune la durée totale du poison de 2 [rounds](./round.md) (la moitié des 4 [rounds](./round.md) de *fréquence*) et son [DD](./DD.md) de +2, pour une durée totale de 8 [rounds](./round.md) (4+2+2) et un [DD](./DD.md) de 18 (14+2+2). Heureusement, le venin d’araignée de taille M se soigne avec un seul [jet de sauvegarde](./JDS.md) réussi, même si le guerrier lutte contre trois doses à la fois.
Cette fois, le guerrier réussit deux de ses premiers [jets de sauvegarde](./JDS.md) contre le venin d’araignée : il n’a donc qu’une dose de poison dans l’organisme. Il rate son [jet de sauvegarde](./JDS.md) lors de son tour. Au tour des araignées, deux d’entre elles le mordent et il rate ses deux [jets de sauvegarde](./JDS.md), ce qui fait passer la durée du poison à 8 [rounds](./round.md) et son [DD](./DD.md) à 18, comme s’il avait raté ses trois jets dans le même [round](./round.md).

#### Fabrication du poison
Le personnage ayant la compétence [Artisanat](./Artisanat.md) (alchimie) peut fabriquer du poison. Le [DD](./DD.md) de fabrication d’un poison est égal au [DD](./DD.md) de son jet de [Vigueur](./Vigueur.md). S’il fait un 1 naturel à son test d’[Artisanat](./Artisanat.md) pour fabriquer un poison, le personnage s’expose au poison. Ceci ne consomme pas la dose. S’il a la capacité de classe [utilisation des poisons](./Alchimiste.md#UTILISATIONDUPOISON), le personnage ne risque pas de s’empoisonner accidentellement lorsqu’il fabrique du poison.

#### Exemples de poisons
Les exemples de poisons présentés ci-dessous ne constituent qu’une partie des poisons les plus courants que l’on trouve en ville. Bien entendu, la plupart des villes ont leurs propres lois concernant l’achat, la vente ou la fabrication du poison. Pour plus d'informations sur le format des descriptions, voir [les afflictions](./Afflictions.md). Sauf indication contraire, les modifications de caractéristiques sont des [affaiblissements temporaires](./affaiblissement temporaire.md).

<center>
{| CLASS="tablo autoalt" WIDTH="100%"
|+ Exemples de poisons{s:Reference|TABLEAUPOISONS}
|- CLASS="titre"
| Nom || Type || DD Vig || Incubation || Fréquence || Effet || Coût
|- CLASS="premier"
| [Ajonc à feuilles bleues](./Poisons.md#Ajonc à feuilles bleues) || Blessure || 14 || — || 1/rd pdt 2 rds || 1 [Con](./Constitution.md)/[Inconscience](./Inconscient.md) 1d3 h || 120 po
|-
| [Bave de dhabba](./Poisons.md#Bavededhabba) || Blessure || 12 || — || — || 1d6 dégâts d’acide, [nausée](./Nauséeux.md)/1d4 [Dex](./Dex.md) || 50 po
|-
| [Brûle-sorts](./Poisons.md#Brûle-sorts) || Blessure || 14 || – || 1/rd pdt 4 rds || <abbr title="La cible doit réussir un test de concentration DD 10 + niveau du sort pour parvenir à lancer un sort, et subit un malus de -5 à tous ses autres tests de concentration.">voir texte</abbr> || 200 po
|-
| [Essence d’ombre](./Poisons.md#Essencedombre) || Blessure || 17 || — || 1/rd pdt 6 rds || [Dim](./diminution permanente.md) 1 [For](./Force.md)/1d2 [For](./Force.md) || 250 po
|-
| [Extrait de sanvert](./Poisons.md#Extraitdesanvert) || Blessure || 13 || — || 1/rd pdt 4 rds || 1 [Con](./Constitution.md) || 100 po
|-
| [Mortelame](./Poisons.md#Mortelame) || Blessure || 20 || — || 1/rd pdt 6 rds || 1d3 [Con](./Constitution.md) || 1 800 po
|-
| [Poison d'araignée noire des marais](./Poisons.md#Poisondaraignéenoiredesmarais) || Blessure || 14 || — || 1/rd pdt 6 rds || 1d4 [Dex](./Dextérité.md), [confusion](./Confus.md) 1 rd || 800 po
|-
| [Poison de vouivre](./Poisons.md#Poisondevouivre) || Blessure || 17 || — || 1/rd pdt 6 rds || 1d4 [Con](./Constitution.md) || 3 000 po
|-
| [Poison drow](./Poisons.md#Poisondrow) || Blessure || 13 || — || 1/min pdt 2 min || [Inconscience](./Inconscient.md) 1 min/2d4 h || 75 po
|-
| [Préserve-plaie](./Poisons.md#Préserve-plaie) || Blessure || 18 || 1 rd || 1/jour || <abbr titre="Les tests de Premiers soins effectués sur la victime subissent un malus de -10. Les soins magiques nécessitent de réussir un test de niveau de lanceur de sorts DD 25 pour fonctionner.">voir texte</abbr> || 75 po
|-
| [Tormentille](./Poisons.md#Tormentille) || Blessure || 12 || 1 rd || 1/rd pdt 4 rds || 1 [Con](./Constitution.md), 1 [Sag](./Sagesse.md), [confusion](./Confus.md) 1 rd || 100 po
|-
| [Venin d’araignée de taille M](./Poisons.md#VenindaraignéedetailleM) || Blessure || 14 || — || 1/rd pdt 4 rds || 1d2 [For](./Force.md) || 150 po
|-
| [Venin d’araignée écorchefeuille](./Poisons.md#Venindaraignéeécorchefeuille) || Blessure || 11 || — || — || 1d3 [Con](./Con.md)/1d3 [Con](./Con.md) || 100 po
|-
| [Venin de guêpe géante](./Poisons.md#Venindeguêpegéante) || Blessure || 18 || — || 1/rd pdt 6 rds || 1d2 [Dex](./Dextérité.md) || 210 po
|-
| [Venin de mille-pattes de taille P](./Poisons.md#Venindemille-pattesdetailleP) || Blessure || 11 || — || 1/rd pdt 4 rds || 1 [Dex](./Dextérité.md) || 90 po
|-
| [Venin de scorpion géant](./Poisons.md#Venindescorpiongéant) || Blessure || 17 || — || 1/rd pdt 6 rds || 1d2 [For](./Force.md) || 200 po
|-
| [Venin de ver pourpre](./Poisons.md#Venindeverpourpre) || Blessure || 24 || — || 1/rd pdt 6 rds || 1d3 [For](./Force.md) || 700 po
|-
| [Venin de vipère à tête noire](./Poisons.md#Venindevipèreàtêtenoire) || Blessure || 11 || — || 1/rd pdt 6 rds || 1d2 [Con](./Constitution.md) || 120 po
|-
| [Toxine de méduse arc-en-ciel](./Poisons.md#Toxinedemédusearc-en-ciel) || Blessure,  
contact || 14 || — || 1/rd pdt 2 rds || [chancelement](./Chancelant.md) 1d6 rds/  
[paralysie](./Paralysé.md) 1d6 min || 400 po
|-
| [Bave de cockatrice](./Poisons.md#Bavedecockatrice) || Blessure,  
contact,  
ingestion || 12 || — || 1/rd pdt 4 rds || 1d2 [Dex](./Dextérité.md), <abbr title="Un affaiblissement égal à la valeur de Dex prétrifie la victime, avec un jet de sauvegarde quotidien pour revenir à 1 point de Dex.">voir texte</abbr> || 1 000 po
|-
| [Baie tueuse](./Poisons.md#Baietueuse) || Blessure,  
ingestion || 15 || 1 rd/  
30 min || 1/min pdt 5 min || 1d3 [For](./For.md), 1 [Con](./Con.md), [paralysie](./Paralysé.md) 1d3 rds || 90 po
|-
| [Bave de guenaude](./Poisons.md#Bavedeguenaude) || Blessure,  
ingestion || 16 || — || 1/rd pdt 6 rds || [cécité](./Aveuglé.md) 1d10 rds/1d4 [Sag](./Sagesse.md) || 1 500 po
|-
| [Venin d’araignée violoniste](./Poisons.md#Venindaraignéevioloniste) || Blessure,  
ingestion || 13 || 1 min || 1/min pdt 6 min || [nausée](./Nauséeux.md) 1d4 rds/1d3 [For](./Force.md), 1d4 [Con](./Constitution.md) || 500 po
|-
| [Bile de dragon](./Poisons.md#Bilededragon) || Contact || 26 || — || 1/rd pdt 6 rds || 1d3 [For](./Force.md) || 1 500 po
|-
| [Extrait de lotus noir](./Poisons.md#Extraitdelotusnoir) || Contact || 20 || 1 min || 1/rd pdt 6 rds || 1d6 [Con](./Constitution.md) || 4 500 po
|-
| [Fléau du mage](./Poisons.md#Fléaudumage) || Contact || 20 || — || — || <abbr title="+10 au DD des tests de concentration pendant 1 heure.">voir texte</abbr> || 500 po
|-
| [Herbe factice](./Poisons.md#Herbefactice) || Contact || 18 || <abbr title="immédiate et 1 semaine">voir texte</abbr> || variable || <abbr title="+1 Con/jour pendant 7 jours, puis disparition des bonus et 1d6 Con/jour pendant 7 jours.">voir texte</abbr> || 6 500 po
|-
| [Larmes de la mort](./Poisons.md#Larmesdelamort) || Contact || 22 || 1 min || 1/min pdt 6 min || 1d6 [Con](./Constitution.md), [paralysie](./Paralysé.md) 1 min || 6 500 po
|-
| [Nitharite](./Poisons.md#Nitharite) || Contact || 13 || 1 min || 1/min pdt 6 min || 1d3 [Con](./Constitution.md) || 650 po
|-
| [Pomme d’épine](./Poisons.md#Pommedépine) || Contact || 11 || 10 min || 1/min pdt 6 min || 1 [Int](./Int.md), [Sag](./Sag.md) et [Con](./Con.md), [cécité](./Aveuglé.md) pdt 1 min || 90 po
|-
| [Poudre d’assonne](./Poisons.md#Poudredassonne) || Contact || 16 || 1 min || 1/min pdt 6 min || 2d12 [pv](./pv.md)/1 [Con](./Constitution.md) || 300 po
|-
| [Racine de malyasse](./Poisons.md#Racinedemalyasse) || Contact || 16 || 1 min || 1/min pdt 6 min || 1d2 [Dex](./Dextérité.md) || 250 po
|-
| [Terrinave](./Poisons.md#Terrinave) || Contact || 16 || 1 min || 1/min pdt 6 min || 1d3 [Dex](./Dextérité.md) || 400 po
|-
| [Aconit](./Poisons.md#Aconit) || Ingestion || 16 || 10 min || 1/min pdt 6 min || 1d3 [Con](./Constitution.md) || 500 po
|-
| [Amnésite](./Poisons.md#Amnésite) || Ingestion || 14 || 10 min || 1/min pdt 6 min || 1d3 [Int](./Intelligence.md) || 125 po
|-
| [Arsenic](./Poisons.md#Arsenic) || Ingestion || 13 || 10 min || 1/min pdt 4 min || 1d2 [Con](./Constitution.md) || 120 po
|-
| [Belladone](./Poisons.md#Belladone) || Ingestion || 14 || 10 min || 1/min pdt 6 min || 1d2 [For](./Force.md), <abbr title="La cible peut tenter un jet de sauvegarde pour guérir une malédiction lycanthropique contractée dans l’heure précédente">voir texte</abbr> || 100 po
|-
| [Calotropis](./Poisons.md#Calotropis) || Ingestion || 14 || 1 heure || 1/min pdt 6 min || 1 [Sag](./Sag.md), 1d3 [Dex](./Dex.md) || 120 po
|-
| [Cendres de liche](./Poisons.md#Cendresdeliche) || Ingestion || 17 || 10 min || 1/min pdt 6 min || 1d3 [For](./Force.md) || 400 po
|-
| [Cigüe](./Poisons.md#Cigüe) || Ingestion || 18 || 10 min || 1/min pdt 6 min || 1d6 [Dex](./Dextérité.md), <abbr title="Asphyxie la cible si elle tombe à 0 en Dextérité">voir texte</abbr> || 2 500 po
|-
| [Entolome zébré](./Poisons.md#Entolomezébré) || Ingestion || 11 || 10 min || 1/min pdt 4 min || 1d3 [Sag](./Sagesse.md), 1 [Int](./Intelligence.md) || 180 po
|-
| [Huile de taggit](./Poisons.md#Huiledetaggit) || Ingestion || 15 || 1 min || — || [Inconscience](./Inconscient.md) 1d3 h || 90 po
|-
| [Pesh pourpre](./Poisons.md#Peshpourpre) || Ingestion || 18 || — || — || 1d2 [Con](./Con.md) et [For](./For.md)/[inconscience](./Inconscient.md) pdt 1 heure || 200 po
|-
| [Pilule de folie](./Poisons.md#Piluledefolie) || Ingestion || 14 || — || — || *[confusion](./Confusion.md)* pdt 1 min || 1 500 po
|-
| [Poison de devin des marais](./Poisons.md#Poisondedevindesmarais) || Ingestion || 18 || 10 min || 1/min pdt 3 min || 1d4 [Sag](./Sagesse.md)/1d2 [Sag](./Sagesse.md), [confusion](./Confus.md) 1 min || 400 po
|-
| [Racine d’aconit](./Poisons.md#Racinedaconit) || Ingestion || 25 || 1 min || 1/rd pdt 5 rds || 1d3 [Dex](./Dex.md), 1 [Con](./Con.md), [nausée](./Nauséeux.md) pdt 1 rd || 1 800 po
|-
| [Rêves indigo](./Poisons.md#Rêvesindigo) || Ingestion || 13 || 10 min || 1/min pdt 6 min || 1d3 [Sag](./Sagesse.md) || 150 po
|-
| [Sommeil du roi](./Poisons.md#Sommeilduroi) || Ingestion || 19 || 1 jour || 1/jour || [Dim](./diminution permanente.md) 1 [Con](./Constitution.md) || 5 000 po
|-
| [Ténébreux vireux](./Poisons.md#Ténébreuxvireux) || Ingestion || 18 || 10 min || 1/min pdt 6 min || 1d3 [Con](./Constitution.md), 1 [For](./Force.md) || 800 po
|-
| [Brume de folie](./Poisons.md#Brumedefolie) || Inhalation || 15 || — || 1/rd pdt 6 rds || 1d3 [Sag](./Sagesse.md) || 1 500 po
|-
| [Cendres d’ungol](./Poisons.md#Cendresdungol) || Inhalation || 15 || — || 1/rd pdt 4 rds || [Dim](./diminution permanente.md) 1 [Cha](./Charisme.md)/1d2 [Cha](./Charisme.md) || 1 000 po
|-
| [Pollen de lys azur](./Poisons.md#Pollendelysazur) || Inhalation || 15 || — || 1/min pdt 2 min || [Nausée](./Nauséeux.md) 1 min/[paralysie](./Paralysé.md) 2d4 h || 1 500 po
|-
| [Vapeur de cauchemar](./Poisons.md#Vapeurdecauchemar) || Inhalation || 20 || — || 1/rd pdt 6 rds || 1 [Sag](./Sagesse.md), [confusion](./Confus.md) 1 rd || 1 800 po
|-
| [Vapeurs d’othur brûlé](./Poisons.md#Vapeurdothurbrûlé) || Inhalation || 18 || — || 1/rd pdt 6 rds || [Dim](./diminution permanente.md) 1 [Con](./Constitution.md)/1d3 [Con](./Constitution.md) || 2 100 po
|}
</center>

### Descriptions des poisons
<table width="100%"><tr><td width="49%">
<div class="BD">
{s:BDTitre|Aconit|{s:Reference|Aconit}}
- **Type** ingestion ; **JDS** Vigueur (DD 16)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 500 po

</div>

<div class="BD">
{s:BDTitre|Ajonc à feuilles bleues|{s:Reference|Ajonc à feuilles bleues}}
- **Type** blessure ; **JDS** Vigueur (DD 14)  
- **Fréquence**  1/round pendant 2 rounds   
- **Effet initial** 1 [Constitution](./Constitution.md) ; **Effet secondaire** [Inconscient](./Inconscient.md) 1d3h ; **Guérison** 1 réussite
- **Prix** 120 po

</div>

<div class="BD">
{s:BDTitre|Amnésite|{s:Reference|Amnésite}}
- **Type** ingestion ; **JDS** Vigueur (DD 14)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Intelligence](./Intelligence.md) ; **Guérison** 1 réussite   
- **Prix** 125 po

</div>

<div class="BD">
{s:BDTitre|Arsenic|{s:Reference|Arsenic}}
- **Type** ingestion ; **JDS** Vigueur (DD 13)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 4 minutes   
- **Effet** 1d2 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 120 po

</div>

<div class="BD">
{s:BDTitre|Baie tueuse|{s:CSU|7}{s:Reference|Baietueuse}}
- **Type** blessure ou ingestion ; **JDS** Vigueur (DD 15)
- **Incubation** 1 round (blessure), 30 minutes (ingestion) ; **Fréquence** 1/minute pendant 5 minutes
- **Effet** 1d3 [Force](./Force.md), 1 [Constitution](./Constitution.md) et [paralysie](./Paralysé.md) pendant 1d3 rounds ; **Guérison** 2 réussites
- **Prix** 90 po

Grâce aux efforts combinés de la guilde des assassins et de celle des empoisonneurs, la grande métropole des Royaumes indépendants est connue pour ses poisons uniques.
</div>

<div class="BD">
{s:BDTitre|Bave de cockatrice|{s:MPNJ}{s:Reference|Bavedecockatrice}}
- **Type** blessure, contact, ingestion ; **JDS** Vigueur (DD 12)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet** 1d2 points de [Dextérité](./Dextérité.md) (une créature qui subit un affaiblissement temporaire égal à son score de Dextérité à cause de ce poison est [pétrifiée](./Pétrifié.md) ; elle peut chaque jour tenter un nouveau jet de [Vigueur](./Vigueur.md) [DD](./DD.md) 12 pour se remettre du venin et retrouver son état normal avec un nombre de points de dégât en Dextérité égal à son score de Dextérité moins 1 point) ; **Guérison** 1 réussite   
- **Prix** 1 000 po

</div>

<div class="BD">
{s:BDTitre|Bave de dhabba|{s:CSU|8}{s:Reference|Bavededhabba}}
<u>***Contenu issu d'un supplément 3.5***</u>
- **Type** blessure ; **JDS** Vigueur (DD 12)
- **Effet initial** 1d6 points de dégâts d'acide et [nauséeux](./Nauséeux.md) ; **Effet secondaire** 1d4 [Dex](./Dextérité.md)
- **Prix** 50 po

Récolté sur des [dhabbas](./Dhabba.md) spécialement drogués, ce poison brûle la chair de la victime autour d’une blessure tout en provoquant un état nauséeux chez la créature.
</div>

<div class="BD">
{s:BDTitre|Bave de guenaude|{s:MPNJ}{s:Reference|Bavedeguenaude}}
- **Type** blessure, ingestion ; **JDS** Vigueur (DD 16)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet initial** [cécité](./Aveuglé.md) pendant 1d10 rounds ; **Effet secondaire** 1d4 points de [Sagesse](./Sagesse.md) ; **Guérison** 2 réussites   
- **Prix** 1 500 po

</div>

<div class="BD">
{s:BDTitre|Belladone|{s:Reference|Belladone}}
- **Type** ingestion ; **JDS** Vigueur (DD 14)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d2 [Force](./Force.md), la cible peut tenter un jet de sauvegarde pour guérir une [malédiction lycanthropique](./Lycanthrope, archétype.md#LYCANTHROPIE) contractée dans l’heure précédente ; **Guérison** 1 réussite  
- **Prix** 100 po

</div>

<div class="BD">
{s:BDTitre|Bile de dragon|{s:Reference|Bilededragon}}
- **Type** contact ; **JDS** Vigueur (DD 26)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d3 [Force](./Force.md) ; **Guérison** —   
- **Prix** 1 500 po

</div>

{s:racial|Duergar (race)|duergars|Illustrations/PNJ/Duergar.jpg}<div class="BD">
{s:BDTitre|Brûle-sorts|{s:MR}{s:Reference|Brûle-sorts}}
- **Type** blessure ; **JDS** Vigueur (DD 14)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet** Raffiné à partir de cristaux souterrains rares, ce poison provoque une migraine brûlante qui gêne l’incantation. Si la cible échoue à son jet de [Vigueur](./Vigueur.md), elle doit, au cours de la minute qui suit, effectuer un [test de concentration](./concentration.md) dont le [DD](./DD.md) est égal à 10 + niveau de sort pour lancer un sort, et souffre d’un malus de -5 à tous ses autres tests de concentration pour lancer des sorts. ; **Guérison** 1 réussite   
- **Prix** 200 po

</div>

<div class="BD">
{s:BDTitre|Brume de folie|{s:Reference|Brumedefolie}}
- **Type** inhalation ; **JDS** Vigueur (DD 15)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d3 [Sagesse](./Sagesse.md) ; **Guérison** 1 réussite   
- **Prix** 1 500 po

</div>

<div class="BD">
{s:BDTitre|Calotropis|{s:CSU|7}{s:Reference|Calotropis}}
- **Type** ingestion ; **JDS** Vigueur (DD 14)
- **Incubation** 1 heure ; **Fréquence** 1/minute pendant 6 minutes
- **Effet** 1 [Sagesse](./Sagesse.md) et 1d3 [Dextérité](./Dextérité.md) ; **Guérison** 1 réussite
- **Prix** 120 po

Grâce aux efforts combinés de la guilde des assassins et de celle des empoisonneurs, la grande métropole des Royaumes indépendants est connue pour ses poisons uniques.
</div>

<div class="BD">
{s:BDTitre|Cendres de liche|{s:Reference|Cendresdeliche}}
- **Type** ingestion ; **JDS** Vigueur (DD 17)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Force](./Force.md) ; **Guérison** 2 réussites   
- **Prix** 400 po

</div>

<div class="BD">
{s:BDTitre|Cendres d’ungol|{s:Reference|Cendresdungol}}
- **Type** inhalation ; **JDS** Vigueur (DD 15)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet initial** [diminution permanente](./diminution permanente.md) 1 [Charisme](./Charisme.md) ; **Effet secondaire** 1d2 [Charisme](./Charisme.md) ; **Guérison** 1 réussite   
- **Prix** 1 000 po

</div>

<div class="BD">
{s:BDTitre|Cigüe|{s:Reference|Cigüe}}
- **Type** ingestion ; **JDS** Vigueur (DD 18)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d6 [Dextérité](./Dextérité.md), [asphyxie](./Dangers naturels.md#ASPHYXIE) la cible si elle tombe à 0 en [Dextérité](./Dextérité.md) ; **Guérison** 2 réussites   
- **Prix** 2 500 po

</div>

<div class="BD">
{s:BDTitre|Entolome zébré|{s:Reference|Entolomezébré}}
- **Type** ingestion ; **JDS** Vigueur (DD 11)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 4 minutes   
- **Effet** 1d3 [Sagesse](./Sagesse.md) et 1 [Intelligence](./Intelligence.md) ; **Guérison** 1 réussite   
- **Prix** 180 po

</div>

<div class="BD">
{s:BDTitre|Essence d’ombre|{s:Reference|Essencedombre}}
- **Type** blessure ; **JDS** Vigueur (DD 17)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet initial** [diminution permanente](./diminution permanente.md) 1 [Force](./Force.md) ; **Effet secondaire** 1d2 [Force](./Force.md) ; **Guérison** 1 réussite   
- **Prix** 250 po

</div>

<div class="BD">
{s:BDTitre|Extrait de lotus noir|{s:Reference|Extraitdelotusnoir}}
- **Type** contact ; **JDS** Vigueur (DD 20)  
- **Incubation** 1 minute ; **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d6 [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 4 500 po

</div>

<div class="BD">
{s:BDTitre|Extrait de sanvert|{s:Reference|Extraitdesanvert}}
- **Type** blessure ; **JDS** Vigueur (DD 13)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet** 1 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 100 po

</div>

<div class="BD">
{s:BDTitre|Fléau du mage|{s:CSU|8}{s:Reference|Fléaudumage}}
<u>***Contenu issu d'un supplément 3.5***</u>
- **Type** contact ; **JDS** Vigueur (DD 20)
- **Effet initial** +10 au [DD](./DD.md) de tous les tests de [concentration](./concentration.md) pendant 1 heure ; **Effet secondaire** +10 au [DD](./DD.md) de tous les tests de [concentration](./concentration.md) pendant 1 heure
- **Prix** 500 po

Dans la Terre sans magie pousse une orchidée à la couleur écarlate sombre appelée épine sanglante. Une fois séchée, réduite en poudre et mélangée à de l’entolome zébré, elle produit un poison qui rend extrêmement difficile pour une créature sous ses effets d’effectuer toute tâche demandant de la concentration.
</div>

<div class="BD">
{s:BDTitre|Herbe factice|{s:CSU|7}{s:Reference|Herbefactice}}
- **Type** contact ; **JDS** Vigueur (DD 18)
- **Incubation** immédiate et 1 semaine (voir effet) ; **Fréquence** variable (voir l'effet)
- **Effet initial** +1 [Constitution](./Constitution.md)/jour pendant 1 semaine ; **Effet secondaire** tous les points de Constitution gagnés disparaissent, 1d6 Con/jour pendant 7 jours ; **Guérison** 2 réussites consécutives
- **Prix** 6 500 po

Grâce aux efforts combinés de la guilde des assassins et de celle des empoisonneurs, la grande métropole des Royaumes indépendants est connue pour ses poisons uniques.
</div>

<div class="BD">
{s:BDTitre|Huile de taggit|{s:Reference|Huiledetaggit}}
- **Type** ingestion ; **JDS** Vigueur (DD 15)  
- **Incubation** 1 minute ; **Fréquence**  —   
- **Effet** [Inconscient](./Inconscient.md) 1d3 h ; **Guérison** 1 réussite   
- **Prix** 90 po

</div>

<div class="BD">
{s:BDTitre|Larmes de la mort|{s:Reference|Larmesdelamort}}
- **Type** contact ; **JDS** Vigueur (DD 22)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d6 [Constitution](./Constitution.md) et [paralysé](./Paralysé.md) 1 minute ; **Guérison** —   
- **Prix** 6 500 po

</div>

<div class="BD">
{s:BDTitre|Mortelame|{s:Reference|Mortelame}}
- **Type** blessure ; **JDS** Vigueur (DD 20)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d3 [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 1 800 po

</div>

<div class="BD">
{s:BDTitre|Nitharite|{s:Reference|Nitharite}}
- **Type** contact ; **JDS** Vigueur (DD 13)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 650 po

</div>
</td><td width="2%">
</td><td width="49%">
<div class="BD">
{s:BDTitre|Pesh pourpre|{s:CSU|8}{s:Reference|Peshpourpre}}
<u>***Contenu issu d'un supplément 3.5***</u>
- **Type** ingestion ; **JDS** Vigueur (DD 18)
- **Effet initial** 1d2 [Con](./Constitution.md) et [For](./Force.md) ; **Effet secondaire** [inconscient](./Inconscient.md) pendant 1 heure
- **Prix** 200 po

Les fabricants de poison du Bazar du Bizarre ont découvert que le lait en décomposition d’un cactus de pesh mort peut être récolté afin de produire un poison hautement efficace pour mettre un ennemi hors de combat.
</div>

<div class="BD">
{s:BDTitre|Pilule de folie|{s:CSU|8}{s:Reference|Piluledefolie}}
<u>***Contenu issu d'un supplément 3.5***</u>
- **Type** ingestion ; **JDS** Vigueur (DD 14)
- **Effet** la créature est considérée sous les effets d’un sort de *[confusion](./Confusion.md)* pendant 1 minute
- **Prix** 1 500 po

Ce poison extrêmement rare et difficile à fabriquer provient d’une glande spéciale récoltée sur des [bêtes du chaos](./Bête du Chaos.md). Une fois mélangé à des réactifs et à des produits chimiques stabilisants, il en résulte un poison inodore et sans saveur. Une fois ingéré, l’élixir provoque une folie temporaire durant 1 minute. Tant que dure l’effet, la créature souffre d’hallucinations terrifiantes, voit son corps fondre sous ses yeux et adopter diverses formes hideuses. Une créature affectée est considérée comme sous l’effet d’un sort de *[confusion](./Confusion.md)*.
</div>

{s:racial|Grippli (race)|gripplis|Illustrations/PNJ/Grippli.jpg}<div class="BD">
{s:BDTitre|Poison d'araignée noire des marais|{s:MR}{s:Reference|Poisondaraignéenoiredesmarais}}
- **Type** blessure ; **JDS** Vigueur (DD 14)  
- **Fréquence**  1/round pendant 6 rounds  
- **Effet** 1d4 [Dextérité](./Dextérité.md) et [confus](./Confus.md) pendant 1 round. Ce puissant venin d’araignée désoriente la victime qui perd tout contrôle musculaire jusqu’à ce qu’elle finisse par s’effondrer. ; **Guérison** 2 réussites   
- **Prix** 800 po

</div>

<div class="BD">
{s:BDTitre|Poison de devin des marais|{s:Reference|Poisondedevindesmarais}}
- **Type** ingestion ; **JDS** Vigueur (DD 18)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 3 minutes   
- **Effet initial** 1d4 [Sagesse](./Sagesse.md) ; **Effet secondaire** 1d2 [Sagesse](./Sagesse.md), [confusion](./Confus.md) 1 minute ; **Guérison** 2 réussites   
- **Prix** 400 po

</div>

<div class="BD">
{s:BDTitre|Poison de vouivre|{s:Reference|Poisondevouivre}}
- **Type** blessure ; **JDS** Vigueur (DD 17)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d4 [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 3 000 po

</div>

<div class="BD">
{s:BDTitre|Poison drow|{s:Reference|Poisondrow}}
- **Type** blessure ; **JDS** Vigueur (DD 13)  
- **Fréquence**  1/minute pendant 2 minutes   
- **Effet** [Inconscient](./Inconscient.md) 1 minute/2d4 h ; **Guérison** 1 réussite   
- **Prix** 75 po

</div>

<div class="BD">
{s:BDTitre|Pollen de lys azur|{s:Reference|Pollendelysazur}}
- **Type** inhalation ; **JDS** Vigueur (DD 15)  
- **Fréquence**  1/minute pendant 2 minutes   
- **Effet initial** [Nauséeux](./Nauséeux.md) 1 minute ; **Effet secondaire** [paralysé](./Paralysé.md) 2d4 h ; **Guérison** 1 réussite   
- **Prix** 1 500 po

</div>

<div class="BD">
{s:BDTitre|Pomme d’épine|{s:CSU|7}{s:Reference|Pommedépine}}
- **Type** contact ; **JDS** Vigueur (DD 11)
- **Incubation** 10 minutes ; **Fréquence** 1/minute pendant 6 minutes
- **Effet** 1 [Intelligence](./Intelligence.md), 1 [Sagesse](./Sagesse.md), 1 [Constitution](./Constitution.md), et [cécité](./Aveuglé.md) pendant 1 minute ; **Guérison** 2 réussites
- **Prix** 90 po

Grâce aux efforts combinés de la guilde des assassins et de celle des empoisonneurs, la grande métropole des Royaumes indépendants est connue pour ses poisons uniques.
</div>

<div class="BD">
{s:BDTitre|Poudre d’assonne|{s:Reference|Poudredassonne}}
- **Type** contact ; **JDS** Vigueur (DD 16)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet initial** 2d12 pv ; **Effet secondaire** 1 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 300 po

</div>

<div class="BD">
{s:BDTitre|Préserve-plaie|{s:cs}{s:AA}{s:Reference|Préserve-plaie}}
- **Type** blessure ; **JDS** Vigueur (DD 18)
- **Incubation** 1 round ; **Fréquence**  1/jour
- **Effet** soins handicapés (voir description) ; **Guérison** 2 réussites consécutives
- **Prix** 100 po

Cette pâte noire granuleuse est un poison qui interfère avec la capacité de la victime à récupérer de ses blessures. Tous les tests de [Premiers secours](./Premiers secours.md) effectués sur elle subissent un malus de -10. De plus, quiconque utilise des soins magiques sur la victime doit réussir un test de niveau de lanceur de sorts de DD 25 pour réussir.
</div>

<div class="BD">
{s:BDTitre|Racine d’aconit|{s:CSU|7}{s:Reference|Racinedaconit}}
- **Type** ingestion ; **JDS** Vigueur (DD 25)
- **Incubation** 1 minute ; **Fréquence** 1/round pendant 5 rounds
- **Effet** 1d3 [Dextérité](./Dextérité.md), 1 [Constitution](./Constitution.md), et [nausée](./Nauséeux.md) pendant 1 round ; **Guérison** 2 réussites
- **Prix** 1 800 po

Grâce aux efforts combinés de la guilde des assassins et de celle des empoisonneurs, la cité des assassins est connue pour ses poisons uniques.
</div>

<div class="BD">
{s:BDTitre|Racine de malyasse|{s:Reference|Racinedemalyasse}}
- **Type** contact ; **JDS** Vigueur (DD 16)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d2 [Dextérité](./Dextérité.md) ; **Guérison** 1 réussite   
- **Prix** 250 po

</div>

<div class="BD">
{s:BDTitre|Rêves indigo|{s:Reference|Rêvesindigo}}
- **Type** ingestion ; **JDS** Vigueur (DD 13)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Sagesse](./Sagesse.md) ; **Guérison** 2 réussites   
- **Prix** 150 po

</div>

<div class="BD">
{s:BDTitre|Sommeil du roi|{s:Reference|Sommeilduroi}}
- **Type** ingestion ; **JDS** Vigueur (DD 19)  
- **Incubation** 1 jour ; **Fréquence**  1/jour   
- **Effet** [diminution permanente](./diminution permanente.md) 1 [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 5 000 po

</div>

<div class="BD">
{s:BDTitre|Ténébreux vireux|{s:Reference|Ténébreuxvireux}}
- **Type** ingestion ; **JDS** Vigueur (DD 18)  
- **Incubation** 10 minutes ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Constitution](./Constitution.md) et 1 [Force](./Force.md) ; **Guérison** 2 réussites   
- **Prix** 800 po

</div>

<div class="BD">
{s:BDTitre|Terrinave|{s:Reference|Terrinave}}
- **Type** contact ; **JDS** Vigueur (DD 16)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet** 1d3 [Dextérité](./Dextérité.md) ; **Guérison** 1 réussite   
- **Prix** 400 po
</div>

<div class="BD">
{s:BDTitre|Tormentille|{s:Reference|Tormentille}}
- **Type** blessure ; **JDS** Vigueur (DD 12)  
- **Incubation** 1 round ; **Fréquence**  1/round pendant 4 rounds   
- **Effet** 1 [Constitution](./Constitution.md), 1 [Sagesse](./Sagesse.md), [confusion](./Confus.md) 1 round ; **Guérison** 1 réussite   
- **Prix** 100 po

</div>

<div class="BD">
{s:BDTitre|Toxine de méduse arc-en-ciel|{s:MPNJ}{s:Reference|Toxinedemédusearc-en-ciel}}
- **Type** contact, blessure ; **JDS** Vigueur (DD 14)  
- **Fréquence**  1/round pendant 2 rounds   
- **Effet initial** [chancelant](./Chancelant.md) pendant 1d6 rounds ; **Effet secondaire** [paralysé](./Paralysé.md) pendant 1d6 minutes ; **Guérison** 1 réussite   
- **Prix** 400 po

</div>

<div class="BD">
{s:BDTitre|Vapeur de cauchemar|{s:Reference|Vapeurdecauchemar}}
- **Type** inhalation ; **JDS** Vigueur (DD 20)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1 [Sagesse](./Sagesse.md) et [confusion](./Confus.md) 1 round ; **Guérison** 2 réussites   
- **Prix** 1 800 po

</div>

<div class="BD">
{s:BDTitre|Vapeurs d’othur brûlé|{s:Reference|Vapeurdothurbrûlé}}
- **Type** inhalation ; **JDS** Vigueur (DD 18)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet initial** [diminution permanente](./diminution permanente.md) 1 [Constitution](./Constitution.md) ; **Effet secondaire** 1d3 [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 2 100 po

</div>

<div class="BD">
{s:BDTitre|Venin d’araignée de taille M|{s:Reference|VenindaraignéedetailleM}}
- **Type** blessure ; **JDS** Vigueur (DD 14)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet** 1d2 [Force](./Force.md) ; **Guérison** 1 réussite   
- **Prix** 150 po

</div>

<div class="BD">
{s:BDTitre|Venin d’araignée écorchefeuille|{s:CSU|8}{s:Reference|Venindaraignéeécorchefeuille}}
<u>***Contenu issu d'un supplément 3.5***</u>
- **Type** blessure ; **JDS** Vigueur (DD 11)
- **Effet initial** 1d3 [Con](./Constitution.md) ; **Effet secondaire** 1d3 [Con](./Constitution.md)
- **Prix** 100 po

Récolté sur les araignées venimeuses qui infestent l’[écorchefeuille](./Drogues.md#ECORCHEFEUILLE), ce poison est un moyen peu coûteux mais rarement mortel de mettre un ennemi hors de combat.
</div>

<div class="BD">
{s:BDTitre|Venin d’araignée violoniste|{s:MPNJ}{s:Reference|Venindaraignéevioloniste}}
- **Type** blessure, ingestion ; **JDS** Vigueur (DD 13)  
- **Incubation** 1 minute ; **Fréquence**  1/minute pendant 6 minutes   
- **Effet initial** [nauséeux](./Nauséeux.md) pendant 1d4 rounds ; **Effet secondaire** 1d3 points de [Force](./Force.md) et de 1d4 points de [Constitution](./Constitution.md) ; **Guérison** 2 réussites   
- **Prix** 500 po

</div>

<div class="BD">
{s:BDTitre|Venin de guêpe géante|{s:Reference|Venindeguêpegéante}}
- **Type** blessure ; **JDS** Vigueur (DD 18)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d2 [Dextérité](./Dextérité.md) ; **Guérison** 1 réussite   
- **Prix** 210 po

</div>

<div class="BD">
{s:BDTitre|Venin de mille-pattes de taille P|{s:Reference|Venindemille-pattesdetailleP}}
- **Type** blessure ; **JDS** Vigueur (DD 11)  
- **Fréquence**  1/round pendant 4 rounds   
- **Effet** 1 [Dextérité](./Dextérité.md) ; **Guérison** 1 réussite   
- **Prix** 90 po

</div>

<div class="BD">
{s:BDTitre|Venin de scorpion géant|{s:Reference|Venindescorpiongéant}}
- **Type** blessure ; **JDS** Vigueur (DD 17)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d2 [Force](./Force.md) ; **Guérison** 1 réussite   
- **Prix** 200 po

</div>

<div class="BD">
{s:BDTitre|Venin de ver pourpre|{s:Reference|Venindeverpourpre}}
- **Type** blessure ; **JDS** Vigueur (DD 24)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d3 [Force](./Force.md) ; **Guérison** 2 réussites   
- **Prix** 700 po

</div>

<div class="BD">
{s:BDTitre|Venin de vipère à tête noire|{s:Reference|Venindevipèreàtêtenoire}}
- **Type** blessure ; **JDS** Vigueur (DD 11)  
- **Fréquence**  1/round pendant 6 rounds   
- **Effet** 1d2 [Constitution](./Constitution.md) ; **Guérison** 1 réussite   
- **Prix** 120 po

</div>
</td></tr></table>
