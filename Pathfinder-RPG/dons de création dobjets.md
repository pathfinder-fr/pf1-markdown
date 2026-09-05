---
Name: Pathfinder-RPG.dons de création dobjets
Title: Dons de création d'objets
LastModified: 2024-06-29 01:04
Categories:
- Don
- Don création
- Liste de dons
- Règle officielle
---

<script>
$(function () {
$("tr.donprérequis0, tr.donprérequis1, tr.donprérequis2").hide();
$("tr.donprincipal").bind("click", togglePrereq);
$("tr.donprincipal").each(addPrereqIconIfNeeded);
});

function togglePrereq() {
let node = $(this).next();
while (node.length > 0 && !node.hasClass("donprincipal")) {
node.toggle();
node = node.next();
}
}

function addPrereqIconIfNeeded() {
let next = $(this).next();
if (next.length > 0 && !next.hasClass("donprincipal")) {
let icon = document.createElement("img");
icon.src = "/Forum/themes/v2/sort_down.gif"
icon.style = "float:right;margin-top: 3px;";
icon.title = "Cliquez pour afficher les dons qui découlent de celui-ci.";
$(this).children("td").first().append($(icon));
}
}
</script>{s:MenuDons}{s:FAQ|***[→](./FAQ- Manuel des joueurs (Dons et compétences).md#12) Dons de création d’objet : Avoir un niveau de lanceur de sort par un pouvoir magique remplit-il le prérequis de NLS des dons de création d’objet ?***

Non. *(Retour à la <u>[règle](./Dons.md#DONCREATION)</u>)*}Les dons de création d’objets permettent au personnage de créer des objets d’un type précis. Tous les dons de cette catégorie possèdent des points communs, quel que soit le type d’objet concerné.

**Coût des matières premières.** Le coût de création d’un objet magique équivaut à la moitié du prix de base de l’objet.

Pour pouvoir utiliser un don de création d’objet, il faut avoir accès à un laboratoire ou à un atelier de magie, aux ustensiles appropriés, etc. Le personnage possède généralement tout ce dont il a besoin, sauf circonstances exceptionnelles.

**Temps nécessaire.** Le temps de création d’un objet magique dépend du don concerné et du coût de l’objet.

**Coût de l’objet.** [Création de baguettes magiques](./Création de baguettes magiques.md), [Création de bâtons magiques](./Création de bâtons magiques.md), [Écriture de parchemins](./Écriture de parchemins.md) et [Préparation de potions](./Préparation de potions.md) permettent de fabriquer des objets qui reproduisent directement les effets d’un sort et dont la puissance dépend de leur [niveau de lanceur de sorts](./NLS.md). Donc, les sorts lancés par ces objets ont la même puissance que s’ils étaient directement lancés par un lanceur de sorts de ce niveau. Le prix de ces objets (et donc leur coût en matières premières) dépend lui aussi de leur [niveau de lanceur de sorts](./NLS.md). Le créateur doit avoir un niveau de lanceur de sorts suffisamment haut pour pouvoir jeter le sort correspondant sur son objet. Pour trouver le prix de base de l’objet, il suffit de multiplier le niveau du sort par le niveau de lanceur de sorts de l’objet et de multiplier le résultat obtenu par une constante, comme suit :
- **Parchemin** : prix de base = niveau de sort x [NLS](./NLS.md) x 25 po.
- **Potion** : prix de base = niveau de sort x [NLS](./NLS.md) x 50 po.
- **Baguette** : prix de base = niveau de sort x [NLS](./NLS.md) x 750 po.
- **Bâtons** : Le prix des bâtons se calcule à l’aide d’une formule plus complexe (voir [ici](./Création dobjets magiques.md#Création de bâtons magiques)).

Pour ce calcul, les sorts du niveau 0 comptent comme des sorts de niveau 1/2.

**Coûts supplémentaires.** Les potions, parchemins et baguettes qui stockent un sort nécessitant une [composante matérielle](./composante matérielle.md) coûteuse exigent une dépense supplémentaire, hors du prix de base. Pour une potion ou un parchemin, le personnage doit payer le prix indiqué dans la description du sort en composantes matérielles. Pour une baguette, il doit acquitter cinquante fois le prix exigé par le sort. Certains objets s’accompagnent également d’un coût supplémentaire, indiqué dans leur description.

**Test de compétence.** Pour créer un objet magique, il faut réussir un test d’[Art de la magie](./Art de la magie.md) [DD](./DD.md) 5 + [niveau de lanceur de sorts](./NLS.md) de l’objet. Le personnage peut également utiliser une compétence d’[Artisanat](./Artisanat.md) ou de [Profession](./Profession.md) adaptée à l’objet qu’il fabrique. Consultez la section sur la [Création d'objets magiques](./Création dobjets magiques.md) pour plus de détails sur les tests d’[Artisanat](./Artisanat.md) et de [Profession](./Profession.md) qui peuvent remplacer le test d’[Art de la magie](./Art de la magie.md). Le [DD](./DD.md) du test peut augmenter si l’artisan est pressé ou s’il ne remplit pas toutes les conditions. En cas d’échec, les composantes matérielles sont perdues, mais si le personnage échoue de cinq ou plus, il produit un [objet maudit](./Objets maudits.md).

<center>
{| CLASS="tablo toutgauche"
|+ Tableau récapitulatif des dons de création d'objets
|- CLASS="titre"
| WIDTH="30%" | Dons
| WIDTH="3%" | Src
| WIDTH="27%" | Conditions
| WIDTH="40%" | Avantages

|- CLASS="premier donprincipal"
| [Création d'anneaux magiques](./Création danneaux magiques.md) || <sup>MJ</sup> || [NLS](./NLS.md) 7 || Création d’anneaux magiques

|- CLASS="premier alt donprincipal"
| [Création d'armes et armures magiques](./Création darmes et armures magiques.md) || <sup>MJ</sup> || [NLS](./NLS.md) 5 || Création d’armures, de boucliers et d’armes magiques
|- CLASS="donprérequis0"
| &emsp;[Création de créatures artificielles](./Création de créatures artificielles.md) || <sup>B1</sup> || [NLS](./NLS.md) 5, [Création d'armes et armures magiques](./Création darmes et armures magiques.md), [Création d'objets merveilleux](./Création dobjets merveilleux.md) || Création de créatures artificielles

|- CLASS="premier donprincipal"
| [Création de baguettes magiques](./Création de baguettes magiques.md) || <sup>MJ</sup> || [NLS](./NLS.md) 5 || Création de baguettes magiques

|- CLASS="premier alt donprincipal"
| [Création de bâtons magiques](./Création de bâtons magiques.md) || <sup>MJ</sup> || [NLS](./NLS.md) 11 || Création de bâtons magiques

|- CLASS="premier donprincipal"
| [Création de créatures artificielles](./Création de créatures artificielles.md) || <sup>B1</sup> || [NLS](./NLS.md) 5, [Création d'armes et armures magiques](./Création darmes et armures magiques.md), [Création d'objets merveilleux](./Création dobjets merveilleux.md) || Création de créatures artificielles

|- CLASS="premier alt donprincipal"
| [Création de sceptres magiques](./Création de sceptres magiques.md) || <sup>MJ</sup> || [NLS](./NLS.md) 9 || Création de sceptres magiques

|- CLASS="premier donprincipal"
| [Création de tatouages magiques](./Création de tatouages magiques.md) || <sup>MMI</sup> || 5 rangs en [Artisanat](./Artisanat.md) (calligraphie, peinture, ou tatouage), [NLS](./NLS.md) 5 || Le personnage sait créer des tatouages magiques

|- CLASS="premier alt donprincipal"
| [Création d'objets merveilleux](./Création dobjets merveilleux.md) || <sup>MJ</sup> || [NLS](./NLS.md) 3 || Création d’objets magiques merveilleux
|- CLASS="donprérequis0"
| &emsp;[Création de créatures artificielles](./Création de créatures artificielles.md) || <sup>B1</sup> || [NLS](./NLS.md) 5, [Création d'armes et armures magiques](./Création darmes et armures magiques.md), [Création d'objets merveilleux](./Création dobjets merveilleux.md) || Création de créatures artificielles

|- CLASS="premier donprincipal"
| [Écriture de parchemins](./Écriture de parchemins.md) || <sup>MJ</sup> || [NLS](./NLS.md) 1 || Création de parchemins magiques

|- CLASS="premier alt donprincipal"
| [Préparation de potions](./Préparation de potions.md) || <sup>MJ</sup> || [NLS](./NLS.md) 3 || Création de potions magiques
|}
</center>
