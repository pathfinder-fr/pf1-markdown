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
</script>{s:MenuDons}{s:FAQ|***[[FAQ- Manuel des joueurs (Dons et compétences)#12|→]] Dons de création d’objet : Avoir un niveau de lanceur de sort par un pouvoir magique remplit-il le prérequis de NLS des dons de création d’objet ?***

Non. *(Retour à la <u>[[Dons#DONCREATION|règle]]</u>)*}Les dons de création d’objets permettent au personnage de créer des objets d’un type précis. Tous les dons de cette catégorie possèdent des points communs, quel que soit le type d’objet concerné.

**Coût des matières premières.** Le coût de création d’un objet magique équivaut à la moitié du prix de base de l’objet.

Pour pouvoir utiliser un don de création d’objet, il faut avoir accès à un laboratoire ou à un atelier de magie, aux ustensiles appropriés, etc. Le personnage possède généralement tout ce dont il a besoin, sauf circonstances exceptionnelles.

**Temps nécessaire.** Le temps de création d’un objet magique dépend du don concerné et du coût de l’objet.

**Coût de l’objet.** [[Création de baguettes magiques]], [[Création de bâtons magiques]], [[Écriture de parchemins]] et [[Préparation de potions]] permettent de fabriquer des objets qui reproduisent directement les effets d’un sort et dont la puissance dépend de leur [[NLS|niveau de lanceur de sorts]]. Donc, les sorts lancés par ces objets ont la même puissance que s’ils étaient directement lancés par un lanceur de sorts de ce niveau. Le prix de ces objets (et donc leur coût en matières premières) dépend lui aussi de leur [[NLS|niveau de lanceur de sorts]]. Le créateur doit avoir un niveau de lanceur de sorts suffisamment haut pour pouvoir jeter le sort correspondant sur son objet. Pour trouver le prix de base de l’objet, il suffit de multiplier le niveau du sort par le niveau de lanceur de sorts de l’objet et de multiplier le résultat obtenu par une constante, comme suit :
- **Parchemin** : prix de base = niveau de sort x [[NLS]] x 25 po.
- **Potion** : prix de base = niveau de sort x [[NLS]] x 50 po.
- **Baguette** : prix de base = niveau de sort x [[NLS]] x 750 po.
- **Bâtons** : Le prix des bâtons se calcule à l’aide d’une formule plus complexe (voir [[Création dobjets magiques#Création de bâtons magiques|ici]]).

Pour ce calcul, les sorts du niveau 0 comptent comme des sorts de niveau 1/2.

**Coûts supplémentaires.** Les potions, parchemins et baguettes qui stockent un sort nécessitant une [[composante matérielle]] coûteuse exigent une dépense supplémentaire, hors du prix de base. Pour une potion ou un parchemin, le personnage doit payer le prix indiqué dans la description du sort en composantes matérielles. Pour une baguette, il doit acquitter cinquante fois le prix exigé par le sort. Certains objets s’accompagnent également d’un coût supplémentaire, indiqué dans leur description.

**Test de compétence.** Pour créer un objet magique, il faut réussir un test d’[[Art de la magie]] [[DD]] 5 + [[NLS|niveau de lanceur de sorts]] de l’objet. Le personnage peut également utiliser une compétence d’[[Artisanat]] ou de [[Profession]] adaptée à l’objet qu’il fabrique. Consultez la section sur la [[Création dobjets magiques|Création d'objets magiques]] pour plus de détails sur les tests d’[[Artisanat]] et de [[Profession]] qui peuvent remplacer le test d’[[Art de la magie]]. Le [[DD]] du test peut augmenter si l’artisan est pressé ou s’il ne remplit pas toutes les conditions. En cas d’échec, les composantes matérielles sont perdues, mais si le personnage échoue de cinq ou plus, il produit un [[objets maudits|objet maudit]].

<center>

<table CLASS="tablo toutgauche">
  <caption>Tableau récapitulatif des dons de création d'objets</caption>
  <tr CLASS="titre">
    <td WIDTH="30%">Dons</td>
    <td WIDTH="3%">Src</td>
    <td WIDTH="27%">Conditions</td>
    <td WIDTH="40%">Avantages</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[Création danneaux magiques|Création d'anneaux magiques]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 7</td>
    <td>Création d’anneaux magiques</td>
  </tr>
  <tr CLASS="premier alt donprincipal">
    <td>[[Création darmes et armures magiques|Création d'armes et armures magiques]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 5</td>
    <td>Création d’armures, de boucliers et d’armes magiques</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Création de créatures artificielles]]</td>
    <td><sup>B1</sup></td>
    <td>
      [[NLS]] 5, [[Création darmes et armures magiques|Création d'armes et armures magiques]], [[Création dobjets
      merveilleux|Création d'objets merveilleux]]
    </td>
    <td>Création de créatures artificielles</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[Création de baguettes magiques]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 5</td>
    <td>Création de baguettes magiques</td>
  </tr>
  <tr CLASS="premier alt donprincipal">
    <td>[[Création de bâtons magiques]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 11</td>
    <td>Création de bâtons magiques</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[Création de créatures artificielles]]</td>
    <td><sup>B1</sup></td>
    <td>
      [[NLS]] 5, [[Création darmes et armures magiques|Création d'armes et armures magiques]], [[Création dobjets
      merveilleux|Création d'objets merveilleux]]
    </td>
    <td>Création de créatures artificielles</td>
  </tr>
  <tr CLASS="premier alt donprincipal">
    <td>[[Création de sceptres magiques]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 9</td>
    <td>Création de sceptres magiques</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[Création de tatouages magiques]]</td>
    <td><sup>MMI</sup></td>
    <td>5 rangs en [[Artisanat]] (calligraphie, peinture, ou tatouage), [[NLS]] 5</td>
    <td>Le personnage sait créer des tatouages magiques</td>
  </tr>
  <tr CLASS="premier alt donprincipal">
    <td>[[Création dobjets merveilleux|Création d'objets merveilleux]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 3</td>
    <td>Création d’objets magiques merveilleux</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Création de créatures artificielles]]</td>
    <td><sup>B1</sup></td>
    <td>
      [[NLS]] 5, [[Création darmes et armures magiques|Création d'armes et armures magiques]], [[Création dobjets
      merveilleux|Création d'objets merveilleux]]
    </td>
    <td>Création de créatures artificielles</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[Écriture de parchemins]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 1</td>
    <td>Création de parchemins magiques</td>
  </tr>
  <tr CLASS="premier alt donprincipal">
    <td>[[Préparation de potions]]</td>
    <td><sup>MJ</sup></td>
    <td>[[NLS]] 3</td>
    <td>Création de potions magiques</td>
  </tr>
</table>

</center>
