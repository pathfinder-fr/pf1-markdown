---
Name: Pathfinder-RPG.Paladin
Title: Le paladin
LastModified: 2024-09-28 17:26
Categories:
- Classe
- Règle officielle
- Src Art de la magie
- Src Manuel des joueurs
---

{s:MenuClasses}
<div class="fright">***Voir aussi la [liste des sorts de paladin](./Liste des sorts de paladins.md).***
{s:PM0|paladin}***Voir les archétypes du paladin***&emsp;
<li ID="paladin" CLASS="listecachée" STYLE="display:none">{s:Menuarchétypepaladin}</li>
</div>*À travers quelques rares et vertueux élus, on peut voir briller la puissance divine. Ces âmes nobles qu’on appelle paladins dévouent leur épée et leur vie au combat contre le mal. À la fois chevaliers, croisés et justiciers, les paladins ne cherchent pas seulement à propager la justice divine mais également à incarner les enseignements des divinités vertueuses qu’ils servent. Pour atteindre ces objectifs ambitieux, ils adhèrent à un code de moralité et de discipline extrêmement strict. En récompense de leur droiture, ces champions sacrés reçoivent des capacités qui les aident à mener leur quête à bien : le pouvoir de repousser le mal, de soigner les innocents et d’encourager les fidèles. Même si leurs convictions les amènent parfois à entrer en conflit avec ceux qu’ils voudraient sauver, les paladins viennent à bout des incessantes épreuves qui testent leur foi par de viles tentations. Ils mettent leur vie en danger pour faire le bien et se battent pour préparer un avenir meilleur.*

{| CLASS="tablo centre"
|+ {s:Reference|TABLEPALADIN}Le paladin
|- CLASS="titre"
| ROWSPAN="2" | Niveau
| ROWSPAN="2" | BBA
| ROWSPAN="2" | Réflexes
| ROWSPAN="2" | Vigueur
| ROWSPAN="2" | Volonté
| CLASS="gauche" ROWSPAN="2" | Spécial
| CLASS="avecsoustitre" COLSPAN="4" | Sorts par jour
|- CLASS="soustitre"
| 1e
| 2e
| 3e
| 4e
|- CLASS="premier"
| 1
| +1
| +0
| +2
| +2
| CLASS="gauche" | [Aura du bien](./Paladin.md#AURADUBIEN), [châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 1/jour, [détection du mal](./Paladin.md#DETECTIONDUMAL)
| -
| -
| -
| -
|- CLASS="alt"
| 2
| +2
| +0
| +3
| +3
| CLASS="gauche" | [Grâce divine](./Paladin.md#GRACEDIVINE), [imposition des mains](./Paladin.md#IMPOSITIONDESMAINS)
| -
| -
| -
| -
|-
| 3
| +3
| +1
| +3
| +3
| CLASS="gauche" | [Aura de courage](./Paladin.md#AURADECOURAGE), [grâce](./Paladin.md#GRACE), [santé divine](./Paladin.md#SANTEDIVINE)
| -
| -
| -
| -
|- CLASS="alt"
| 4
| +4
| +1
| +4
| +4
| CLASS="gauche" | [Canalisation d'énergie positive](./Paladin.md#CANALISATIONDENERGIEPOSITIVE), [châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 2/jour
| 0*
| -
| -
| -
|-
| 5
| +5
| +1
| +4
| +4
| CLASS="gauche" | [Pacte divin](./Paladin.md#PACTEDIVIN)
| 1
| -
| -
| -
|- CLASS="alt"
| 6
| +6/+1
| +2
| +5
| +5
| CLASS="gauche" | [Grâce](./Paladin.md#GRACE)
| 1
| -
| -
| -
|-
| 7
| +7/+2
| +2
| +5
| +5
| CLASS="gauche" | [Châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 3/jour
| 1
| 0*
| -
| -
|- CLASS="alt"
| 8
| +8/+3
| +2
| +6
| +6
| CLASS="gauche" | [Aura de fermeté](./Paladin.md#AURADEFERMETE)
| 1
| 1
| -
| -
|-
| 9
| +9/+4
| +3
| +6
| +6
| CLASS="gauche" | [Grâce](./Paladin.md#GRACE)
| 2
| 1
| -
| -
|- CLASS="alt"
| 10
| +10/+5
| +3
| +7
| +7
| CLASS="gauche" | [Châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 4/jour
| 2
| 1
| 0*
| -
|-
| 11
| +11/+6/+1
| +3
| +7
| +7
| CLASS="gauche" | [Aura de justice](./Paladin.md#AURADEJUSTICE)
| 2
| 1
| 1
| -
|- CLASS="alt"
| 12
| +12/+7/+2
| +4
| +8
| +8
| CLASS="gauche" | [Grâce](./Paladin.md#GRACE)
| 2
| 2
| 1
| -
|-
| 13
| +13/+8/+3
| +4
| +8
| +8
| CLASS="gauche" | [Châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 5/jour
| 3
| 2
| 1
| 0*
|- CLASS="alt"
| 14
| +14/+9/+4
| +4
| +9
| +9
| CLASS="gauche" | [Aura de foi](./Paladin.md#AURADEFOI)
| 3
| 2
| 1
| 1
|-
| 15
| +15/+10/+5
| +5
| +9
| +9
| CLASS="gauche" | [Grâce](./Paladin.md#GRACE)
| 3
| 2
| 2
| 1
|- CLASS="alt"
| 16
| +16/+11/+6/+1
| +5
| +10
| +10
| CLASS="gauche" | [Châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 6/jour
| 3
| 3
| 2
| 1
|-
| 17
| +17/+12/+7/+2
| +5
| +10
| +10
| CLASS="gauche" | [Aura de droiture](./Paladin.md#AURADEDROITURE)
| 4
| 3
| 2
| 1
|- CLASS="alt"
| 18
| +18/+13/+8/+3
| +6
| +11
| +11
| CLASS="gauche" | [Grâce](./Paladin.md#GRACE)
| 4
| 3
| 2
| 2
|-
| 19
| +19/+14/+9/+4
| +6
| +11
| +11
| CLASS="gauche" | [Châtiment du mal](./Paladin.md#CHATIMENTDUMAL) 7/jour
| 4
| 3
| 3
| 2
|- CLASS="alt"
| 20
| +20/+15/+10/+5
| +6
| +12
| +12
| CLASS="gauche" | [Champion sacré](./Paladin.md#CHAMPIONSACRE)
| 4
| 4
| 3
| 3
|- CLASS="note"
| COLSPAN="5" | *(*) Aucun sort sauf sorts bonus octroyés par un Charisme élevé.*
|}

**Rôle.** Les paladins sont pour leurs alliés comme des phares au milieu du chaos de la bataille. Ils sont redoutables quand ils combattent le mal, mais ils peuvent également fortifier les combattants du bien et les aider dans leurs croisades. Leurs capacités magiques et martiales en font également de bons protecteurs et des alliés capables de redonner à ceux qui ont été vaincus la force de continuer à se battre.

**Alignement.** Loyal Bon.

**Dés de vie.** d10.

**Argent de départ.** 5d6 x 10 po (moyenne 175 po).

### Compétences de classe
Les compétences de classe du paladin sont les suivantes : [Art de la magie](./Art de la magie.md) (Int), [Artisanat](./Artisanat.md) (Int), [Connaissances](./Connaissances.md) (noblesse) (Int), [Connaissances](./Connaissances.md) (religion) (Int), [Diplomatie](./Diplomatie.md) (Cha), [Dressage](./Dressage.md) (Cha), [Équitation](./Équitation.md) (Dex), [Premiers secours](./Premiers secours.md) (Sag), [Profession](./Profession.md) (Sag) et [Psychologie](./Psychologie.md) (Sag).

**Points de compétence par niveau.** 2 + modificateur d’[Intelligence](./Intelligence.md).

### Descriptif de la classe
Les aptitudes du paladin sont décrites ci-dessous.<div class="description">**Note.** les options marquées d'un "(*HH*)" proviennent du *Healer's Handbook* et ont été traduites par la communauté.</div>

{s:ImageDroite|Illustrations/PNJ/Seelah.jpg|35%}
#### Armes et armures
Le paladin est formé au maniement de toutes les [armes courantes](./arme courante.md) et [de guerre](./arme de guerre.md), ainsi qu’au port de toutes les [armures](./Tableau récapitulatif des armures.md) (légères, intermédiaires et lourdes) et à l’utilisation des boucliers (à l’exception des pavois).

{s:Reference|AURADUBIEN}
#### Aura de Bien (Ext)
Un paladin génère une aura de Bien (voir le sort *[détection du Mal](./Détection.md)*), dont la puissance correspond à son niveau de paladin.

{s:Reference|DETECTIONDUMAL}
#### Détection du Mal (Mag)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#25) Paladin, Détection du Mal : Un paladin doit-il dépenser une action simple pour activer sa détection du Mal avant de dépenser une action de mouvement pour se concentrer sur une créature ou un objet ?***

Non, la première phrase est distincte du reste de la capacité, et offre une option alternative pour utiliser la <u>[détection du Mal](./Paladin.md#DETECTIONDUMAL)</u>. Un paladin peut utiliser l’action de mouvement sur une créature ou un objet à la place de l’action simple nécessaire à l’activation d’une *[détection du Mal](./Détection du Mal.md)* normale.}Un paladin peut détecter le Mal à volonté, comme par le sort de *[détection du Mal](./Détection.md)*. Par une [action de mouvement](./Action de mouvement.md), le paladin peut se concentrer sur un objet ou un individu unique distant de 18 m (12 cases) ou moins pour déterminer s’il est d’[alignement](./Alignement.md) Mauvais et pour connaître la puissance de son aura comme s’il l’avait étudié pendant trois rounds. Lorsqu’il se concentre sur un objet ou un individu, le paladin ne détecte pas le Mal sur les autres objets ou individus à proximité.

{s:Reference|CHATIMENTDUMAL}
#### Châtiment du Mal (Sur)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#24) Paladin, Châtiment du Mal : Le châtiment du Mal ignore-t-il les défenses du pouvoir spécial intangible ?***

Le châtiment n’est pas un effet sur l’arme, c’est un effet sur le <u>[paladin](./Paladin.md#CHATIMENTDUMAL)</u>. L’arme a toujours besoin d’être magique pour blesser la créature [intangible](./Intangible (capacité).md), et même une arme magique ne lui inflige que la moitié de ses dégâts.}Une fois par jour, un paladin peut faire appel aux pouvoirs du bien dans son combat contre le mal. Par une [action rapide](./Action rapide.md), le paladin désigne comme cible de son châtiment du Mal un ennemi qu’il peut voir. Si la cible est d’alignement Mauvais, le paladin ajoute son bonus de [Charisme](./Charisme.md) (s’il en a un) à ses jets d’attaque et son niveau de paladin à tous les jets de dégâts à l’encontre de sa cible. Si la cible est un [Extérieur](./type Extérieur.md) du sous-type [Mal](./sous-type Mal.md), un dragon d’alignement Mauvais ou un [mort-vivant](./type Mort-vivant.md), le bonus aux dégâts passe à 2 points de dégâts par niveau du paladin pour la première attaque qui touche l'adversaire. Dans tous les cas, le châtiment du mal ignore toutes les [réductions de dégâts](./RD.md) de la cible.

De plus, lorsqu’un châtiment du Mal est en cours, le paladin gagne un bonus de parade à sa [CA](./CA.md) égal à son bonus de [Charisme](./Charisme.md) (s’il en a un) contre les attaques portées par la cible du châtiment du Mal. Si le paladin désigne une créature qui n’est pas d’alignement Mauvais, le châtiment est dépensé mais n’a aucun effet.

L’effet du châtiment du Mal persiste jusqu’à ce que la cible soit morte ou jusqu’à ce que le paladin se repose et récupère son quota d’utilisations de cette capacité. Au niveau 4 et tous les trois niveaux par la suite, le paladin obtient une utilisation quotidienne supplémentaire de ce pouvoir, comme indiqué dans la Table "[Le Paladin](./Paladin.md#TABLEPALADIN)", avec un maximum de sept utilisations quotidiennes au niveau 19.

{s:Reference|GRACEDIVINE}
#### Grâce divine (Sur)
Un paladin de niveau 2 ou plus bénéficie d’un bonus à tous ses [jets de sauvegarde](./jet de sauvegarde.md) égal à son bonus de [Charisme](./Charisme.md) (s’il en a un).

{s:Reference|IMPOSITIONDESMAINS}
#### Imposition des mains (Sur)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#26) Paladin, Imposition des mains : L’imposition des mains du paladin utilise-t-elle de l’énergie positive ?***

Oui. *(Retour à la <u>[capacité](./Paladin.md)</u>)*}À partir du niveau 2, un paladin peut soigner ses blessures ou celles de ses camarades d’un simple toucher. Il peut utiliser ce pouvoir un nombre de fois par jour égal à la moitié de son niveau de paladin + son modificateur de [Charisme](./Charisme.md). Chaque utilisation permet de soigner 1d6 points de vie par tranche de deux niveaux de paladin et nécessite une [action simple](./Action simple.md) (sauf si le paladin soigne ses propres blessures, auquel cas une [action rapide](./Action rapide.md) suffit). Contrairement à ce que son nom pourrait laisser penser, cette capacité ne nécessite qu’une seule main de libre pour être utilisée.

Le paladin peut également utiliser ce pouvoir de guérison pour infliger des blessures aux [morts-vivants](./type Mort-vivant.md), à hauteur de 1d6 points de dégâts par tranche de deux niveaux de paladin. Cette utilisation du pouvoir nécessite un jet d’[attaque de contact](./attaque de contact.md) au corps à corps et ne provoque pas d’[attaque d’opportunité](./attaque dopportunité.md). Les morts-vivants ne bénéficient d’aucun jet de sauvegarde contre ces dégâts.

{s:Reference|AURADECOURAGE}
#### Aura de courage (Sur)
Un paladin de niveau 3 est immunisé contre la [Terreur (capacité)|terreur] (magique ou non). De plus, tous ses alliés situés à 3 m (2 cases) ou moins bénéficient d’un bonus de moral de +4 aux jets de sauvegarde contre tous les effets de [Terreur (capacité)|terreur]. Cette aptitude fonctionne tant que le paladin est conscient, mais pas s’il est [inconscient](./Inconscient.md) ou mort.

{s:Reference|SANTEDIVINE}
#### Santé divine (Ext)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#28) Paladin, Santé divine : Si je suis immunisé aux maladies, suis-je immunisé à la putréfaction de la momie, qui est à la fois une maladie et une malédiction ?***

Oui. *(Retour à la <u>[capacité](./Paladin.md)</u>)*}Un paladin de niveau 3 est immunisé contre toutes les [maladies](./Maladies.md), y compris celles qui sont d’origine magique ou surnaturelle comme la putréfaction de la momie.

{s:Reference|GRACE}{s:Desambi|Grâce est également le nom d'un [sort](./Grâce (sort).md).}
#### Grâce (Sur)
Au niveau 3 et tous les trois niveaux par la suite, un paladin peut choisir une grâce. Chaque grâce ajoute un effet supplémentaire à sa capacité d’[imposition des mains](./Paladin.md#IMPOSITIONDESMAINS). Chaque fois que le paladin impose les mains pour soigner les blessures d’une créature, celle-ci bénéficie également des effets supplémentaires relatifs à toutes les grâces que le paladin a choisies. Une grâce peut annuler un [état préjudiciable](./États préjudiciables.md) infligé par une [maladie](./maladie.md), une [malédiction](./malédiction.md) ou un [poison](./poison.md) sans pour autant soigner l’affliction elle-même. L’[état préjudiciable](./États préjudiciables.md) en question réapparaît après une heure, à moins que la grâce ait effectivement supprimé l’affliction qui le causait.

Au niveau 3, le paladin peut sélectionner une des grâces suivantes :
- **Agité** (*HH*) : l’imposition des mains du paladin agit également comme un sort d’*[apaisement des émotions](./Apaisement des émotions.md)* avec un [NLS](./NLS.md) égal au niveau du paladin, mais seulement dans le but d’enrayer les bonus de moral de la cible (comme ceux d’un sort de *[rage](./Rage.md)*) et les effets d’émotion qui ne sont pas des effets de peur.
- **Fatigué** : la cible n’est plus [fatiguée](./Fatigué.md).
- **Fiévreux** : la cible n’est plus [fiévreuse](./Fiévreux.md).
- **Secoué** : la cible n’est plus [secouée](./Secoué.md).
- **Trompé** (*HH*) : la cible peut immédiatement effectuer un nouveau [jet de sauvegarde](./JDS.md) contre toute [illusion](./Illusion.md) qu’elle a échoué a dévoiler dans la dernière minute.

Au niveau 6, les choix suivants s’ajoutent à la liste des grâces disponibles :
- **Affaibli** (*HH*) : la paladin dissipe tout effet magique réduisant une des valeurs de caractéristique de la cible (au choix du paladin).
- **Chancelant** : la cible n’est plus [chancelante](./Chancelant.md), sauf si elle a exactement 0 point de vie.
- **Ciblé** (*HH*) : l’imposition des mains du paladin agit également comme un sort de *[sanctuaire](./Sanctuaire.md)* avec un [NLS](./NLS.md) égal au niveau du paladin. Le [DD](./DD.md) du [jet de sauvegarde](./JDS.md) contre cet effet est égal à 10 + la moitié du niveau du paladin + le modificateur du [Charisme](./Charisme.md) du paladin.
- **Guérison de la maladie** : l’imposition des mains du paladin agit également comme un sort de *[guérison des maladies](./Guérison des maladies.md)* avec un [NLS](./NLS.md) égal au niveau du paladin.
- **Hanté** (*HH*) : l’imposition des mains du paladin agit également comme un sort de *[protection contre le Mal](./Protection contre le Mal.md)* avec un [NLS](./NLS.md) égal au niveau du paladin, mais seulement dans le but d’autoriser un nouveau [jet de sauvegarde](./JDS.md) contre les effets d'[enchantement (charme)](./branche charme.md) et d'[enchantement (coercition)](./branche coercition.md), et d’immuniser la cible contre toutes les nouvelles tentatives de la posséder ou d'exercer un contrôle mental sur elle (comme décrit dans le deuxième effet du sort *protection contre le Mal*).
- **Hébété** : la cible n’est plus [hébétée](./Hébété.md).

Au niveau 9, les choix suivants s’ajoutent à la liste des grâces disponibles :
- **Blessé** (*HH*) : la cible bénéficie d’une [guérison accélérée 3](./Guérison accélérée (capacité).md) pendant un nombre de [round](./round.md) égal à la moitié du niveau du paladin.
- **Confus** (*HH*) : la cible n’est plus [confuse](./Confus.md).
- **Délivrance de la malédiction** : l’imposition des mains du paladin agit également comme un sort de *[délivrance des malédictions](./Délivrance des malédictions.md)* avec un [NLS](./NLS.md) égal au niveau du paladin.
- **Effrayé** : la cible n’est plus [effrayée](./Effrayé.md) (le paladin doit posséder la grâce *Secoué* avant de pouvoir choisir cette option).
- **Épuisé** : la cible n’est plus [épuisée](./Épuisé.md) (le paladin doit posséder la grâce *Fatigué* avant de pouvoir choisir cette option).
- **Guérison du poison** : l’imposition des mains du paladin agit également comme un sort de *[neutralisation du poison](./Neutralisation du poison.md)* avec un [NLS](./NLS.md) égal au niveau du paladin.
- **Nauséeux** : la cible n’est plus [nauséeuse](./Nauséeux.md) (le paladin doit posséder la grâce *Fiévreux* avant de pouvoir choisir cette option).
- **Restauratrice** (*HH*) : la cible soigne 1d4 points d’[affaiblissement temporaire](./affaiblissement temporaire (capacité).md) affectant une unique valeur de caractéristique, au choix du paladin. Le paladin doit posséder la grâce affaibli avant de pouvoir choisir cette grâce.

Au niveau 12, les choix suivants s’ajoutent à la liste des grâces disponibles.
- **Amputé** (*HH*) : l’imposition des mains du paladin agit également comme un sort de *[régénération](./Régénération.md)* avec un [NLS](./NLS.md) égal au niveau du paladin, mais seulement dans le but de faire repousser les membres tranchés, de ressouder les os brisés et de reconstituer les organes détruits.
- **Aveugle** : la cible n’est plus [aveugle](./Aveuglé.md).
- **Assourdi** : la cible n’est plus [assourdie](./sourd.md).
- **Ensorcelé** (*HH*) : l’imposition des mains du paladin agit également comme un sort de *[dissipation de la magie](./Dissipation de la magie.md)* avec un [NLS](./NLS.md) égal au niveau du paladin (maximum 20).
- **Étourdi** : la cible n’est plus [étourdie](./Étourdi.md).
- **Paralysé** : la cible n’est plus [paralysée](./Paralysé.md).
- **Pétrifié** (*HH*) : l’imposition des mains du paladin agit également comme un sort de *[transmutation de la pierre en chair](./Transmutation de la pierre en chair.md)* avec un [NLS](./NLS.md) égal au niveau du paladin, mais seulement dans le but de redonner son apparence normale à une créature pétrifiée.

Ces effets se cumulent. Par exemple, lorsqu’un paladin de niveau 12 impose les mains, il guérit 6d6 points de dégâts et peut également supprimer les [états préjudiciables](./États préjudiciables.md) [fatigué](./Fatigué.md) et [épuisé](./Épuisé.md) en plus de soigner les maladies et de neutraliser les poisons. Une fois qu’une grâce a été sélectionnée, ce choix ne peut plus être modifié.

{s:Reference|CANALISATIONDENERGIEPOSITIVE}
#### Canalisation d’énergie positive (Sur)
Lorsque le paladin atteint le niveau 4, il acquiert la capacité surnaturelle de [canaliser de l’énergie positive](./Prêtre.md#CANALISATION) avec un niveau effectif de [prêtre](./Prêtre.md) égal à son niveau de paladin (voir la [description de cette capacité chez le prêtre](./Prêtre.md#CANALISATION)). Chaque canalisation d’énergie consomme deux utilisations de sa capacité d’imposition des mains. Il s’agit d’une capacité basée sur le [Charisme](./Charisme.md).

{s:um}Voir aussi les [variantes de canalisation](./Variantes de canalisation.md).

{s:Reference|SORTS}
#### Sorts
Dès le niveau 4, un paladin peut lancer un petit nombre de sorts divins appartenant à la [liste des sorts de paladins](./Liste des sorts de paladins.md). Un paladin doit choisir et préparer ses sorts à l’avance.

Pour préparer ou lancer un sort, un paladin doit avoir une valeur de [Charisme](./Charisme.md) au moins égale à 10 + le [niveau du sort](./Niveau de sort.md). Le [DD](./DD.md) des [jets de sauvegarde](./jet de sauvegarde.md) contre les sorts du paladin est égal à 10 + le [niveau du sort](./Niveau de sort.md) + le modificateur de [Charisme](./Charisme.md) du paladin.

Comme les autres lanceurs de sorts, le paladin ne peut lancer qu’un nombre de sorts donné de chaque niveau chaque jour. Son quota de sorts quotidiens est indiqué dans la Table "[Le Paladin](./Paladin.md#TABLEPALADIN)". En plus de cela, il reçoit des sorts en bonus si sa valeur de [Charisme](./Charisme.md) est suffisamment élevée. Quand la Table "[Le Paladin](./Paladin.md#TABLEPALADIN)" indique que le paladin peut lancer quotidiennement 0 sort d’un niveau donné, il ne dispose, pour ce niveau de sorts, que des sorts en bonus que peut lui accorder un [Charisme](./Charisme.md) élevé (voir la Table "[Modificateurs de caractéristique et sorts en bonus](./Caractéristiques.md#TABLEAUCARACTERISTIQUES)").

Chaque jour, le paladin doit passer une heure à prier et à méditer afin de renouveler son quota journalier de sorts. Le paladin peut préparer et lancer n’importe quel sort de la liste des paladins, pour autant qu’il puisse lancer des sorts de ce niveau. Il doit cependant choisir quels sorts préparer au cours de sa méditation quotidienne.

Jusqu’au niveau 3, le paladin n’a pas de niveau de lanceur de sorts. À partir du niveau 4, son [niveau de lanceur de sorts](./NLS.md) est égal à son niveau de paladin -3.

{s:Reference|PACTEDIVIN}
#### Pacte divin (Mag)
{s:FAQ|***[→](./FAQ- Manuel des joueurs (Races et classes).md#27) Paladin, Pacte divin : Puis-je dépenser deux utilisations de cette capacité pour altérer deux de mes armes ou les deux extrémités d’une arme double ?***

Oui. *(Retour à la [classe](./Paladin.md))*}Lorsque le paladin atteint le niveau 5, un lien divin se tisse entre lui et son dieu. Celui-ci peut prendre une des deux formes suivantes. Une fois qu’une forme a été choisie, ce choix ne peut plus être modifié.
- ***Arme sacrée.*** La première forme de lien permet à un paladin d’enchanter son arme par une [action simple](./Action simple.md) en faisant appel à un esprit céleste qui lui accorde son aide pendant une minute par niveau de paladin. Lorsqu’il est appelé, l’esprit fait briller l’arme comme une torche. Au niveau 5, cet esprit donne à l’arme un bonus d’altération de +1. Tous les trois niveaux suivants, l’arme gagne un bonus d’altération de +1 supplémentaire, jusqu’à un maximum de +6 au niveau 20. Ces bonus peuvent être ajoutés directement à l’arme et cumulés avec les bonus qu’elle possède déjà et ce jusqu’à un maximum de +5. Ces bonus peuvent également être utilisés pour ajouter l’une des propriétés suivantes à l’arme : *[acérée](./acérée (propriété).md)*, *[axiomatique](./axiomatique (propriété).md)*, *de [destruction](./destruction (propriété).md)*, *de [feu](./feu (propriété).md)*, *de [feu intense](./feu intense (propriété).md)*, *de [lumière](./lumière (propriété).md)*, *[rapide](./rapide (propriété).md)*, *[gardienne](./gardienne (propriété).md)*, *[miséricordieuse](./miséricordieuse (propriété).md)* ou *[sainte](./sainte (propriété).md)*. Ajouter une de ces propriétés coûte une quantité de bonus équivalente au coût de la propriété (voir [ici](./Armes magiques.md)). Ces propriétés s’ajoutent à celles que l’arme possède déjà mais les propriétés en double ne se cumulent pas. Si l’arme n’est pas magique, il faut lui ajouter un bonus d’altération d’au moins +1 avant de pouvoir lui conférer des propriétés. Les bonus et les propriétés donnés par l’esprit sont déterminés lorsqu’il est appelé et ne peuvent donc être modifiés que lorsque l’esprit est appelé à nouveau. L’esprit céleste n’accorde aucun bonus si quelqu’un d’autre que le paladin tient l’arme, mais les bonus réapparaissent si l’arme revient dans la main du paladin. Ces bonus ne s’appliquent qu’à une seule tête si l’arme est une arme double. Un paladin peut utiliser cette capacité une fois par jour au niveau 5 et une fois de plus par jour tous les quatre niveaux suivants, pour un total de quatre utilisations quotidiennes au niveau 17.

: Si une arme est détruite alors qu’elle est liée à un esprit céleste, le paladin doit attendre de gagner un niveau ou que trente jours se soient écoulés avant de pouvoir utiliser cette capacité à nouveau. Pendant cette période d’attente, le paladin subit un malus de -1 à tous les jets d’attaque et de dégâts lorsqu’il combat avec une arme.
- ***Destrier.*** La seconde forme de lien permet à un paladin d’acquérir les services d’un destrier plus intelligent, fort et loyal que la moyenne, qui viendra l’aider dans sa croisade contre le mal. Il s’agit généralement d’un cheval lourd (pour un paladin de taille M) ou d’un poney (pour un paladin de taille P), mais des montures plus exotiques comme un sanglier, un chameau ou un chien sont également possibles. Le destrier suit les mêmes règles que les [compagnons animaux](./Compagnons animaux.md) des druides, avec un niveau de druide effectif égal au niveau du paladin. Les montures ainsi liées au paladin possèdent une [Intelligence](./Intelligence.md) d’au moins 6.

: Une fois par jour, le paladin peut appeler son destrier auprès de lui en utilisant une [action complexe](./Action complexe.md). Cette capacité est équivalente à un sort d’un niveau égal au tiers du niveau du paladin. Le destrier apparaît immédiatement à côté du paladin. Un paladin peut utiliser ce pouvoir une fois par jour au niveau 5 et une fois de plus chaque jour tous les quatre niveaux par la suite, pour un total de quatre fois par jour au niveau 17.

: Au niveau 11, le destrier acquiert l’archétype [céleste](./Céleste, archétype.md) et est désormais considéré comme une [créature magique](./type Créature magique.md) lorsqu’il s’agit de déterminer les effets des sorts. Au niveau 15, le destrier gagne une [résistance à la magie](./RM.md) égale au niveau du paladin + 11.

: Si le destrier vient à mourir, le paladin doit attendre de gagner un niveau ou que trente jours se soient écoulés avant de pouvoir utiliser cette capacité à nouveau. Pendant cette période d’attente, le paladin subit un malus de -1 à tous les [jets d’attaque](./jet dattaque.md) et de [dégâts](./jet de dégâts.md) lorsqu’il combat avec une arme.

{s:cs}**Les variantes de pacte divin** (*HH*). Bien que tous les paladins forment un lien avec les forces divines et les esprits célestes, certains sont capables de le faire d’une manière qui transcende les habituelles armes sacrées ou destriers célestes. Lorsqu’un paladin gagne la capacité de classe pacte divin, il peut choisir une des variantes de pacte divin suivants à la place de ceux décrits dans la classe. Toutes les variantes de pacte divin sont des [pouvoirs surnaturels](./Capacités spéciales.md#TYPES), et un paladin ne peut pas choisir une variante de pacte divin s’il a un archétype qui modifie ou remplace le pacte divin.
- ***Pacte angélique.*** Par une [action simple](./Action simple.md), le paladin peut faire surgir un esprit angélique qui se lie à lui, lui faisant manifester un halo resplendissant. Ce lien permet au paladin d’émettre de la lumière comme avec un sort de *[flamme éternelle](./Flamme éternelle.md)* pendant une minute par niveau de paladin. De plus, tant que ce halo brille, tous les alliés dans un rayon de 6 mètres obtiennent les avantages du sort *[protection contre le Mal](./Protection contre le Mal.md)*, sauf que les bonus de parade et de résistance sont de +3. Tous les 3 niveaux après le 5e, le bonus de parade et le bonus de résistance accordé par cet effet augmentent de 1, jusqu’à un maximum de +8 au niveau 20. Un paladin peut utiliser cette capacité une fois par jour au niveau 5 et une fois de plus par jour tous les quatre niveaux suivants, pour un total de quatre utilisations quotidiennes au niveau 17.

- ***Pacte de l’agathion.*** Par une [action simple](./Action simple.md), le paladin peut faire surgir un esprit agathion qui se lie à ses mains guérisseuses pendant une minute par niveau de paladin, lui faisant manifester des traits physiques évoquant un type particulier d’agathion. Ce lien permet au paladin d’ajouter son bonus de [Charisme](./Charisme.md) au montant de [points de vie](./pv.md) qu’il soigne avec ses sorts, sa capacité d’[imposition des mains](./Paladin.md#IMPOSITIONDESMAINS) et sa capacité de [canalisation d’énergie positive](./Paladin.md#CANALISATIONDENERGIEPOSITIVE). Tous les 3 niveaux après le niveau 5, il soigne un point de vie supplémentaire avec ces capacités, jusqu’à un maximum de 5 + son modificateur de Charisme au niveau 20. Un paladin peut utiliser cette capacité une fois par jour au niveau 5 et une fois de plus par jour tous les quatre niveaux suivants, pour un total de quatre utilisations quotidiennes au niveau 17.

- ***Pacte de l’archon.*** Par une [action simple](./Action simple.md), le paladin peut faire surgir un esprit archon qui se lie à son visage, faisant briller ses yeux d’un courroux vertueux pendant une minute par niveau de paladin. Tant que ce lien est actif, toutes les créatures hostiles dans un rayon de 3 mètres qui regardent le paladin doivent réussir un jet de [Volonté](./Volonté.md) ([DD](./DD.md) = 10 + la moitié du niveau du paladin + son modificateur de [Charisme](./Charisme.md)) ou subir un malus de de -2 à la [CA](./CA.md) et aux [jets de sauvegarde](./JDS.md) pendant 24 heures. Que la cible réussisse son jet de sauvage ou non, elle ne peut plus être affectée par le pacte de l’archon d’un même paladin pendant 24 heures, et les malus de différents pactes de l’archon ne se cumulent pas. Les créatures n’ayant pas de vision ne sont pas affectée par cette capacité. Tous les 3 niveaux après le 5e, le rayon de cette capacité augmente de 1,5 mètre, jusqu’à un maximum de 10,5 mètres au niveau 20. Un paladin peut utiliser cette capacité une fois par jour au niveau 5 et une fois de plus par jour tous les quatre niveaux suivants, pour un total de quatre utilisations quotidiennes au niveau 17.

{s:Reference|AURADEFERMETE}
#### Aura de fermeté (Sur)
Un paladin de niveau 8 est immunisé contre les sorts et les pouvoirs magiques de [charme](./charme.md). De plus, tous ses alliés situés à 3 m ou moins bénéficient d’un bonus de moral de +4 aux jets de sauvegarde contre tous les effets de [charme](./charme.md).

Cette aptitude fonctionne tant que le paladin est conscient, mais pas s’il est inconscient ou mort.

{s:Reference|AURADEJUSTICE}
#### Aura de justice (Sur)
Au niveau 11, un paladin peut sacrifier deux utilisations de sa capacité du [châtiment du Mal](./Paladin.md#CHATIMENTDUMAL) pour permettre à tous ses alliés situés à 3 m ou moins d’utiliser un [châtiment du Mal](./Paladin.md#CHATIMENTDUMAL) avec ses propres bonus. Les alliés doivent utiliser ce [châtiment du Mal](./Paladin.md#CHATIMENTDUMAL) avant que le prochain tour du paladin commence et les bonus persistent pendant une minute. Ce pouvoir s’utilise par une action libre. Les créatures d’alignement Mauvais ne tirent aucun avantage de l’aura de justice.

{s:Reference|AURADEFOI}
#### Aura de foi (Sur)
Au niveau 14, les armes d’un paladin sont considérées comme dotées de l’alignement Bon lorsqu’il s’agit de déterminer si elles ignorent les réductions de dégâts. De plus, toutes les attaques faites contre un ennemi dans un rayon de 3 m autour du paladin sont également considérées comme dotées de l’alignement Bon lorsqu’il s’agit de déterminer si elles ignorent les réductions de dégâts.

Cette capacité fonctionne tant que le paladin est conscient, mais pas s’il est inconscient ou mort.

{s:Reference|AURADEDROITURE}
#### Aura de droiture (Sur)
Au niveau 17, un paladin gagne une [RD](./RD.md) 5/Mal et est immunisé aux sorts et aux pouvoirs magiques de [coercition](./coercition.md). De plus, tous ses alliés situés à 3 m ou moins bénéficient d’un bonus de moral de +4 aux [jets de sauvegarde](./jet de sauvegarde.md) contre tous les effets de [coercition](./coercition.md).

Cette aptitude fonctionne tant que le paladin est conscient, mais pas s’il est [inconscient](./Inconscient.md) ou [mort](./Mort.md).

{s:Reference|CHAMPIONSACRE}
#### Champion sacré (Sur)
Au niveau 20, un paladin devient un véritable réceptacle de la puissance de son dieu. Sa RD augmente jusqu’à 10/Mal. Chaque fois qu’il utilise un [châtiment du Mal](./Paladin.md#CHATIMENTDUMAL) et frappe un [Extérieur](./type Extérieur.md) d’alignement Mauvais, celui-ci est également soumis à un bannissement dont le NLS est égal au niveau du paladin (l’arme et le symbole sacré du paladin comptent automatiquement comme objets que la cible hait). Le [châtiment du Mal](./Paladin.md#CHATIMENTDUMAL) se termine immédiatement après que l’effet de bannissement et les dégâts de l’attaque ont été appliqués. De plus, chaque fois que le paladin [canalise de l’énergie positive](./Paladin.md#CANALISATIONDENERGIEPOSITIVE) ou utilise une [imposition des mains](./Paladin.md#IMPOSITIONDESMAINS) pour guérir une créature, il soigne toujours le maximum de points de vie.

### Code de conduite
Le paladin est obligatoirement [Loyal Bon](./Alignement.md). S’il commet sciemment un acte maléfique, il perd aussitôt son statut et ses pouvoirs, en dehors des compétences de maniement d’armes, de port d’armures et d’utilisation de boucliers.

De plus, son code de conduite l’oblige à respecter l’autorité légitime, à se comporter de façon honorable (c’est-à-dire à ne pas mentir, tricher, utiliser le [poison](./poison.md), etc.), à aider les gens dans le besoin (à condition qu’ils ne cherchent pas à utiliser le paladin dans un but chaotique ou maléfique), et à châtier ceux qui menacent ou maltraitent les innocents.

### Compagnons
Le paladin peut partir à l’aventure avec des alliés d’alignement Bon ou Neutre mais il évitera de collaborer avec des personnes d’alignement Mauvais ou avec ceux qui bafouent sans cesse son code de conduite. Dans des circonstances exceptionnelles, un paladin pourra s’associer avec des créatures d’alignement Mauvais mais seulement avec comme but de venir à bout d’un plus grand mal. Le paladin devrait chercher à recevoir régulièrement un sort de pénitence pendant ce genre d’alliance inhabituelle et il devrait immédiatement mettre un terme à celle-ci s’il a l’impression de faire plus de mal que de bien. Enfin, le paladin ne peut louer les services d’hommes d’armes et accepter les suivants que s’ils sont Bons et Loyaux.

{s:Reference|ANCIENPALADIN}
### Anciens paladins
Un paladin changeant d’alignement, commettant sciemment un acte maléfique ou bafouant son code de conduite perd ses sorts et ses aptitudes (y compris la collaboration de son destrier, mais pas sa formation en matière d’armes, d’armures et de boucliers). Il ne peut plus gagner de niveaux de paladin. Il récupère son statut et ses capacités et peut à nouveau progresser en tant que paladin s’il fait acte de contrition (voir le sort *[pénitence](./Pénitence.md)*).
