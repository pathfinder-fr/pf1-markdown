---
Name: Pathfinder-RPG.Combat de masse
Title: Le combat de masse
LastModified: 2022-04-02 21:21
Categories:
- Règle officielle
- Src Guide de campagne
---

{s:MenuGC}{s:GC}<nav class="wiki-toc"></nav>Tôt ou tard, même le plus pacifique des royaumes devra partir en guerre. Certains royaumes en désaccord avec le vôtre accepteront sûrement de chercher un compromis mais d’autres sont fermés à toutes négociations ou répondent aux tentatives d’apaisement pas des agressions de plus en plus violentes. Quand la diplomatie échoue, le fracas de l’acier ne tarde pas à se faire entendre.

Cette section contient des règles qui vous permettront, en tant que dirigeant de royaume, de lever des armées, de leur assigner des commandants et des les préparer à se battre sur terre, sur mer et dans les cieux. Elles vous expliquent comment équiper une armée conventionnelle et comment l’entretenir, comment utiliser des [PJ](./PJ.md) dans un combat de masse, comment convertir un groupe de monstres en force militaire et elles englobent même ce qui se passe après le combat, loin du champ de bataille.

<div style="float: right; margin-left: 10px; margin-right: -10px; max-width: 300px;" class="presentation recentre">
##### Au-delà du royaume
Les règles du combat de masse se réfèrent souvent à des éléments issus des règles de la construction de royaume, comme les tests de [Loyauté](./Royaumes et guerre.md#LOYAUTE) et le [DD de contrôle](./Royaumes et guerre.md#DDDECONTROLE). Si vous ne dirigez pas de royaume, remplacez le test de Loyauté par un [jet de sauvegarde](./JDS.md) et le DD de contrôle par le DD du pouvoir principal d’un monstre possédant un [FP](./FP.md) égal au FPA du groupe (consultez la table "[Valeurs-cibles des monstres selon leur FP](./Créer un monstre.md#TAB11)" dans les règles de création de monstre). Par exemple, si l’armée a un FPA de 12, le DD du jet de sauvegarde sera de 21. Utilisez un mois au lieu d’un [tour](./Tour de royaume.md) ou d’une phase de royaume et, au lieu des [PC](./Royaumes et guerre.md#PONTSDECONSTRUCTION), utilisez des pièces d’or (en multipliant le coût en PC par 500).

</div>
Ces règles vous fournissent un système de combat de masse abstrait et narratif qui vous permet de jouer rapidement un scénario de bataille complexe sans vous noyer sous une avalanche de détails mais tout en restant fidèles aux stratégies, aux tactiques et aux réalités d’un champ de bataille. En revanche, elles ne sont pas conçues pour refléter fidèlement la complexité d’une guerre, ce ne sont pas des simulations tactiques hautement évoluées ni un modèle précis de jeu de guerre miniature. Elles sont là pour vous permettre d’incorporer une guerre dans votre campagne tout en restant concentré sur les aventures et le roleplay traditionnel à échelle réduite.

#### Aperçu
Voici les points clefs du combat de masse, ceux auxquels vous devrez souvent vous référer.
- Des explications sur le profil des armées et la terminologie utilisée dans le chapitre (voir plus bas).
- Des instructions détaillées étape par étape pour gérer les phases de bataille entre les armées ([ici](./Phases dune bataille (guerre).md)).
- Des modificateurs de bataille en fonction du terrain et de divers facteurs similaires ([ici](./Phases dune bataille (guerre).md#CONDITIONS)).
- Les différentes tactiques que les armées peuvent apprendre ([ici](./Tactiques des armées (guerre).md)).
- Ce qui se passe à la fin de la bataille, une fois qu’une armée a gagné, perdu ou pris la fuite ([ici](./Victoire déroute et défaite (guerre).md)).
- Comment utiliser les commandants spéciaux ou les membres du gouvernement pour modifier les statistiques d’une armée ([ici](./Commandants (guerre).md)).
- Des ressources pour améliorer vos armées et les faire évoluer ([ici](./Ressources des armées (guerre).md)).
- Des pouvoirs spéciaux pour les armées hors du commun, comme des incantations ou du poison ([ici](./Pouvoirs spéciaux (guerre).md)).
- Des exemples d’armées ([ici](./Exemples darmées (guerre).md)).
- *Une liste de règles optionnelles pour préciser la gestion des armées ([ici](./Règles optionnelles du combat de masse (guerre).md)).*

#### Diriger un combat de masse
Comme la puissance d’une armée dépend de son [FPA](./Combat de masse.md#FPA), le [MJ](./MJ.md) peut équilibrer les combats de masse en suivant les conseils de [FP](./FP.md) dans la table "[Niveau de la rencontre](./Rencontres.md)" des règles de création de rencontres. Par exemple, une armée de FPA 9 qui affronte une autre armée de FPA 9 présage d’un combat équilibré, tout comme une armée de FPA 9 opposée à trois armées de FPA 6. Cela s’applique surtout aux armées humanoïdes car les monstres qui possèdent de formidables pouvoirs risquent de se montrer bien plus redoutables.

### Les statistiques de l'armée
Chaque armée est décrite selon un format standard. Dans les pages suivantes, nous vous expliquons quelles sont les diverses catégories d’information que nous définissons.

{s:Reference|NOM}**Nom.** Voici le nom de l’armée. Ce peut-être celui d’une compagnie mercenaire comme « Les Enragés sanglants de Thokk, » un régiment numéroté comme « la Septième cavalerie royale » ou quelque chose d’informel comme « la milice de Rougepierre. »

{s:Reference|PX}**PX.** C’est le montant de [PX](./PX.md) que les [PJ](./PJ.md) gagneront si leur armée triomphe de celle-ci. Cela fonctionne comme une récompense de PX pour une [rencontre](./Rencontres.md) d’un [FP](./FP.md) égal au [FPA](./Combat de masse.md#FPA) de l’armée (voir plus bas).

{s:Reference|ALIGNEMENT}**Alignement.** L’alignement de l’armée n’a aucun effet sur ses statistiques, c’est juste un excellent moyen de résumer son attitude en deux lettres. Elle est généralement du même alignement que son unité type.

<div style="float:right; background-color: #fff; padding: 0 0 16px 16px">
<div style="border: 1px solid #4b3124; padding: 4px; max-width: 260px;">
{| CLASS="tablo centre toutgauche autoalt"
|+ Les tailles des armées
|- CLASS="titre"
| Taille de l’armée || Nbre d’unités || FPA
|- CLASS="premier"
| Infime || 1 || FP d’une créature individuelle –8
|-
| Minuscule || 10 || FP d’une créature individuelle –6
|-
| Très petite || 25 || FP d’une créature individuelle –4
|-
| Petite || 50 || FP d’une créature individuelle –2
|-
| Moyenne || 100 || FP d’une créature individuelle
|-
| Grande || 200 || FP d’une créature individuelle +2
|-
| Très grande || 500 || FP d’une créature individuelle +4
|-
| Gigantesque || 1 000 || FP d’une créature individuelle +6
|-
| Colossale || 2 000 || FP d’une créature individuelle +8
|}
</div></div>{s:Reference|TAILLE}**Taille.** La taille de l’armée détermine le nombre d’unités individuelles qu’elle comprend mais aussi son [FPA](./Combat de masse.md#FPA).

{s:Reference|TYPE}**Type.** Voici la composition des unités individuelles de l’armée, comme « orques (homme d’armes 1) » ou « trolls. » Ces règles partent du principe que les unités sont homogènes : si une armée de 100 orques hommes d’armes 1 (c’est-à-dire des hommes d’armes de niveau 1) compte quelques hommes d’armes demi-orques et quelques barbares orques, cela ne suffira pas à modifier les statistiques de toute l’armée. Si une armée comporte beaucoup d’unités différant de l’unité principale (c’est-à-dire assez pour modifier les statistiques de l’armée), il vaut mieux scinder le groupe et le traiter comme deux armées avec des profils différents.

{s:Reference|PV}**pv.** Une armée a un montant de pv égal à [FPA](./Combat de masse.md#FPA) x pv moyens de 1 [DV](./../Ressources/DV.md) d’une unité (3,5 pour des DV calculés en d6, 4,5 pour du d8, 5,5 pour du d10 et 6,5 pour du d12). Prenons l’exemple des [hommes d’armes](./Homme darme.md). Leurs DV sont des d10. Une armée d’hommes d’armes de FPA 1 a donc 5,5 x 1 = 5,5 pv, arrondi à l’inférieur, c’est-à-dire 5 pv. Notez que, pour réduire les pv d’une armée, il faut impérativement en utiliser une autre. Si des individus isolés l’attaquent, ils ne pourront pas la réduire de manière visible mais, si vous voulez déterminer le résultat de leur assaut, vous pouvez les considérer comme une armée de taille infime. Comme pour tous les effets de jeu qui affectent les points de vie, les capacités qui réduisent les dégâts ou la guérison de moitié (ou d’une autre fraction) ont un effet minimum de 1 et non de 0.

{s:Reference|FPA}**Facteur de puissance de l’armée (FPA).** Le FPA est basé sur le [FP](./FP.md) d’un individu de l’armée et sur la taille de cette dernière. Il évolue comme le FP des monstres. Pour déterminer le FPA, consultez la table "Les tailles des armées" et appliquez le modificateur de taille de l’armée au FP d’un membre type de cette armée. S’il s’agit d’une unité de cavalerie, utilisez le FP de la monture ou du cavalier (le plus élevé). Par exemple, un orque [homme d’armes](./Homme darme.md) 1 a un FP 1/3, une armée de 100 orques hommes d’arme 1 a donc un FPA 1/3, une armée de 500 orques hommes d’arme 1 un FPA 3 (4 crans de plus que l’armée standard de 100 soldats). Si le FPA d’une armée est inférieur à 1/8, ce n’est pas une armée : vous devez lui ajouter des troupes jusqu’à ce que vous atteigniez au moins un FPA de 1/8.

{s:Reference|VDEF}**Valeur de défense (VDéf).** C’est la valeur que l’armée utilise pour résister aux attaques, comme une créature utilise sa [CA](./CA.md). La VDéf d’une armée est de [FPA](./Combat de masse.md#FPA) + 10 + bonus dus à des fortifications ou à la [Défense](./Communautés et quartiers.md#DEFENSE) d’une communauté.

{s:Reference|MA}**Modificateur d’attaque (MA).** C’est un modificateur que l’on ajoute au jet de d20 pour déterminer les chances de succès de l’armée. Il fonctionne comme le [bonus d’attaque](./BBA.md) des créatures. Le MA d’une armée est égal à son [FPA](./Combat de masse.md#FPA). Si l’armée peut attaquer à distance, c’est indiqué ici. Les attaques à distance et au corps à corps utilisent le même MA, sauf indication contraire.

{s:Reference|TACTIQUE}**Tactique.** Ce sont les statistiques d’armée (voir [ici](./Tactiques des armées (guerre).md) dont dispose éventuellement l’armée.

{s:Reference|RESSOURCES}**Ressources.** Voici les ressources de l’armée (voir [ici](./Ressources des armées (guerre).md)).

{s:Reference|SPECIAL}**Spécial.** Ce sont les pouvoirs spéciaux de l’armée (voir [ici](./Pouvoirs spéciaux (guerre).md)).

{s:Reference|VITESSE}**Vitesse.** Ce nombre indique le nombre d’hexagones de 20 kilomètres que l’armée traverse en un jour de marche. Sa vitesse décroît de moitié si elle traverse un terrain difficile. Utilisez la table "[Déplacement et distance](./Déplacements.md#LONGUEDISTANCE)" pour déterminer la vitesse de l’armée en fonction de celle de ses unités.

{s:Reference|MORAL}**Moral.** Ce chiffre représente le degré de confiance de l’armée. Il sert à déterminer les changements de [tactique](./Combat de masse.md#TACTIQUE), à savoir si une armée est en [déroute](./Victoire déroute et défaite (guerre).md) après une attaque dévastatrice ou autre. C’est un modificateur qui va de –4 (au pire) à +4 (au mieux). À sa création, une armée a un moral de +0. Il est modifié par le [commandant](./Combat de masse.md#COMMANDANT) de l’armée et d’autres éléments. Si le moral d’une armée tombe à –5 ou plus bas, l’armée se disperse ou déserte et vous ne pouvez plus la contrôler.

{s:Reference|CONSOMMATION}**Consommation.** C’est le nombre de [PC](./Royaumes et guerre.md#POINTSDECONSTRUCTION) qu’une armée consomme chaque semaine (contrairement aux autres dépenses du royaume qui sont mensuelles). Il couvre le boire et le manger des soldats, les armes, l’entraînement et l’entretien de l’armée ainsi que le salaire des militaires. La Consommation de base est égale au [FPA](./Combat de masse.md#FPA)/2 (1 au minimum). Si vous payez votre armée en retard, réduisez son [moral](./Combat de masse.md#MORAL) de 2. Ce malus disparaît dès que vous êtes à jour dans vos paiements.

{s:Reference|COMMANDANT}**Commandant.** Voici le [commandant](./Commandants (guerre).md) de l’armée, avec son modificateur de [Charisme](./Charisme.md), ses rangs en [Profession](./Profession.md) (soldat) et sa valeur de prestige. Pour donner des ordres ou donner un bonus aux jets de l’armée, le commandant doit être en mesure de communiquer avec elle, éventuellement avec des sorts comme message ou via d’autres formes de communication magique.

### Références de base du combat de masse
Les règles de combat de masse assimilent les armées à des créatures individuelles. Quand des elfes affrontent des orques, au lieu de lancer cent fois le dé pour chaque camp, vous traitez l’armée elfique comme une seule entité et de même pour l’armée orque. Elles font donc chacune un seul jet lors de l’affrontement. De plus, elles attaquent simultanément et non chacune leur tour. Les petites armées comptent peu de créatures individuelles (appelées des unités) tandis que les armées bien fournies en ont plus. Le nombre d’unités influe directement sur la puissance de l’armée.

Utilisez la feuille de combat de masse, en page 266 du Guide de campagne, pour noter l’évolution des statistiques de votre armée, tout comme vous suivez celles de votre personnage sur sa feuille.

Chaque armée a un [commandant](./Combat de masse.md#COMMANDANT). Il s’agit en général d’un vétéran aguerri qui dirige ses mouvements. Vous pouvez très bien prendre le commandement d’une armée et lui apporter des bonus qui dépendent de votre [rôle gouvernemental](./Responsables gouvernementaux.md).

Les armées peuvent apprendre diverses [tactiques](./Tactiques des armées (guerre).md) : utiliser des archers restés en réserve, former un mur défensif ou faire des coups bas. Elles peuvent aussi varier leur [stratégie d’attaque](./Phases dune bataille (guerre).md#Léchelle_de_stratégie_0) : se montrer téméraires et agressives (comme une créature qui utilise [Attaque en puissance](./Attaque en puissance.md)) ou prudentes et rester sur la défensive (comme avec [Expertise du combat](./Expertise du combat.md)). C’est au commandant de décider de la tactique et de la stratégie à employer.

Les [conditions du champ de bataille](./Phases dune bataille (guerre).md#CONDITIONS) influent sur le déroulement et l’issue du combat. Par exemple, un terrain boueux va ralentir des armées piétonnes mais pas des armées aériennes, un combat de nuit handicape des armées humaines mais pas des orques, etc.

La bataille se déroule en trois phases : les commandants choisissent leur tactique, les armées attaquent à distance (le cas échéant) et les armées se rejoignent pour le corps à corps. Elles restent ainsi jusqu’à ce qu’un camp s’enfuie ou soit détruit.

Voici un résumé des jets clefs du combat de masse.
- **Test d’attaque.** d20 + modificateur d’attaque ([MA](./Combat de masse.md#MA))
- **Dégâts infligés.** Résultat du test d’attaque – valeur de défense ([VDéf](./Combat de masse.md#VDEF)) de l’armée qui défend
- **Test de moral.** d20 + modificateurs du commandant + [moral](./Combat de masse.md#MORAL) de l’armée
