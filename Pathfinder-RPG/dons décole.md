---
Name: Pathfinder-RPG.dons décole
Title: Dons d'école
LastModified: 2024-05-19 18:31
Categories:
- Don école
- Liste de dons
- Règle officielle
- Src Art de la guerre
---

<script>
$(function () {
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
</script>{s:MenuDons}Pendant des siècles, les plus grands combattants ont observé la nature et le multivers pour y puiser une inspiration guerrière. D’innombrables ordres monastiques et contemplatifs ont développé des écoles de combat à mains nues basées sur l’efficacité mortelle et la grâce de créatures naturelles ou non. Au départ, ces techniques étaient réservées à des ordres secrets mais, depuis, elles se sont répandues dans le monde entier.

Par une [[action rapide]], le personnage peut adopter la posture de référence de l’école liée au don. Il ne peut pas utiliser de don d’école avant le début du combat mais il conserve la posture choisie jusqu’à ce qu’il dépense une action rapide pour changer d’école. Si une école particulière figure dans les conditions requises d’un don, le personnage doit obligatoirement se trouver dans la posture de cette école pour l’utiliser.
*Par exemple, si le personnage connaît des dons liés à l’École de la mante et à celle du tigre, il peut utiliser une action rapide pour adopter l’École du tigre au début de son tour puis utiliser d’autres dons qui exigent l’École du tigre comme condition requise. Au début du tour suivant, il peut dépenser une nouvelle action rapide pour adopter l’École de la mante et utiliser des dons associés à cette école.*

*Les dons marqués d'un astérisque (*) sont des dons de combat.*
<center>

<table CLASS="tablo autoalt toutgauche">
  <caption>Tableau récapitulatif des dons d'école</caption>
  <tr CLASS="titre">
    <td WIDTH="25%">Dons</td>
    <td WIDTH="3%">Src</td>
    <td WIDTH="36%">Conditions</td>
    <td WIDTH="36%">Avantages</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lascète|École de l'ascète]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Arme de prédilection]] avec l'arme de corps à corps choisie, [[BBA]] +1 ou [[moine]] de niveau 1</td>
    <td>Utilise des armes dans le cadre des capacités à mains nues</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Forme de lascète|Forme de l'ascète]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École de lascète|École de l'ascète]], [[Arme de prédilection]] avec l'arme de corps à corps choisie, [[BBA]]
      +5 ou [[moine]] de niveau 5
    </td>
    <td>Utilise une nouvelle arme de corps à corps dans le cadre des capacités à mains nues</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Frappe de lascète|Frappe de l'ascète]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Forme de lascète|Forme de l'ascète]], [[École de lascète|École de l'ascète]], [[Arme de prédilection]] avec
      l'arme choisie, [[BBA]] +7 ou [[moine]] de niveau 7
    </td>
    <td>Utilise les dégâts à mains nues d'un moine de niveau inférieur à la place des dés de dégâts de l'arme</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lavant-garde|École de l'avant-garde]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Attaques réflexes]], [[Garde du corps]], maniement des [[rondache (armure)|rondaches]] ou des [[écu
      (armure)|écus]]
    </td>
    <td>Utilise Garde du corps pour améliorer les jets de Réflexes des alliés</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Protecteur de lavant-garde|Protecteur de l'avant-garde]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Attaques réflexes]], [[École de lavant-garde|École de l'avant-garde]], [[Garde du corps]], maniement des
      [[rondache (armure)|rondaches]] ou des [[écu (armure)|écus]]
    </td>
    <td>Utilise Garde du corps et École de l'avant-garde dans la même action</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Frénésie de lavant-garde|Frénésie de l'avant-garde]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 13, [[Attaques réflexes]], [[Bouclier salvateur]], [[École de lavant-garde|École de l'avant-garde]],
      [[Garde du corps]], [[Patrouille en combat]], [[Protecteur de lavant-garde|Protecteur de l'avant-garde]],
      [[Souplesse du serpent]], maniement des [[rondache (armure)|rondaches]] ou des [[écu (armure)|écus]]
    </td>
    <td>Ajoute la moitié du bonus d'altération du bouclier au bonus de Bouclier salvateur</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la bulette renversante]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[For]] 13, [[Attaque en puissance]], [[Science du renversement]], formation au port des armures lourdes</td>
    <td>+4 aux manœuvres de renversement</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Bond de la bulette renversante]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[For]] 15, [[Attaque en puissance]], [[École de la bulette renversante]], [[Science du renversement]],
      formation au port des armures lourdes
    </td>
    <td>Renverse plusieurs adversaire et ajoute le modificateur de Force aux tests d'Acrobaties pour sauter</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Carnage de la bulette renversante]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[For]] 15, [[Attaque en puissance]], [[Bond de la bulette renversante]], [[École de la bulette renversante]],
      [[Science du renversement]], formation au port des armures lourdes
    </td>
    <td>Inflige des dégâts après un renversement réussi</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lefrit|École de l'efrit]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 13, [[Sag]] 15, [[Poing élémentaire]], [[Science du combat à mains nues]], [[BBA]] +9 ou [[moine]] de
      niveau 5
    </td>
    <td>Une utilisation quotidienne de Poing élémentaire de plus et un bonus aux dégâts de feu</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Posture de lefrit|Posture de l'efrit]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 15, [[École de lefrit|École de l'efrit]], [[Poing élémentaire]], [[Science du combat à
      mains nues]], [[BBA]] +11 ou [[moine]] de niveau 9
    </td>
    <td>Une utilisation quotidienne de Poing élémentaire de plus et résistance au feu</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Caresse de lefrit|Caresse de l'efrit]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 17, [[École de lefrit|École de l'efrit]], [[Posture de lefrit|Posture de l'efrit]],
      [[Poing élémentaire]], [[Science du combat à mains nues]], [[BBA]] +13 ou [[moine]] de niveau 11
    </td>
    <td>Le personnage projette un cône de feu qui peut enflammer ses adversaires</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lempoigneur|École de l'empoigneur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Science de la lutte]]; [[BBA]] +6, capacité de classe [[Lutteur#DELUGEDECOUPSDULUTTEUR|déluge de coups du
      lutteur]] ou [[Moine#DELUGEDECOUPS|déluge de coups]]
    </td>
    <td>
      Le personnage ne reçoit aucun malus lorsqu'il agrippe un ennemi à une main et conserve son bonus de Dex à la
      CA quand il l'immobilise
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Traction de lempoigneur|Traction de l'empoigneur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[École de lempoigneur|École de l'empoigneur]], [[Science de la lutte]]; [[BBA]] +8, [[lutteur]] de niveau 4,
      ou [[moine]] de niveau 4
    </td>
    <td>Le personnage se déplace plus loin avec les ennemis qu'il traîne</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Maître empoigneur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Traction de lempoigneur|Traction de l'empoigneur]], [[École de lempoigneur|École de l'empoigneur]],
      [[Science de la lutte]]; [[BBA]] +12, [[lutteur]] de niveau 8, ou [[moine]] de niveau 8
    </td>
    <td>Le personnage agrippe deux ennemis au lieu d'un seul</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lenfant de la terre|École de l'enfant de la terre]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 13, [[nain]] ou [[gnome]], trait racial entraînement défensif, [[Science du combat à mains nues]], 3
      rangs en [[Acrobaties]]
    </td>
    <td>La CA de l'entraînement défensif passe à +6 contre les géants</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Renversement de lenfant de la terre|Renversement de l'enfant de la terre]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 13, [[nain]] ou [[gnome]], trait racial entraînement défensif, [[École de lenfant de la terre|École de
      l'enfant de la terre]], [[Science du croc-en-jambe]], [[Science du combat à mains nues]], 6 rangs en
      [[Acrobaties]]
    </td>
    <td>Le personnage peut faire un croc-en-jambe à un géant de taille TG au maximum</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Lien de lenfant de la terre|Lien de l'enfant de la terre]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 13, [[nain]] ou [[gnome]], trait racial entraînement défensif, [[École de lenfant de la terre|École de
      l'enfant de la terre]], [[Renversement de lenfant de la terre|Renversement de l'enfant de la terre]],
      [[Croc-en-jambe supérieur]], [[Science du croc-en-jambe]], [[Science du combat à mains nues]], [[Coup
      étourdissant]], 9 rangs en [[Acrobaties]]
    </td>
    <td>
      Le personnage peut faire un croc-en-jambe à un géant de n'importe quelle taille. Il peut décider d'appliquer
      le Coup étourdissant une fois qu'il sait que l'attaque d'opportunité portée contre un géant qui se relève a
      touché
    </td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de lescrimeur|École de l'escrimeur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Expertise du combat]], [[Arme de prédilection]] avec l'arme choisie, [[BBA]] +3</td>
    <td>
      Bonus de bouclier de +1 à la CA en combat sur la défensive, évite le malus d'Expertise du combat sur la
      première attaque à chaque round
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Moquerie de lescrimeur|Moquerie de l'escrimeur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Expertise du combat]], [[Science de la feinte]], [[École de lescrimeur|École de l'escrimeur]], [[Arme de
      prédilection]] avec l'arme choisie, [[BBA]] +5
    </td>
    <td>Feinte un adversaire qui rate une attaque contre le personnage</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Parade de lescrimeur|Parade de l'escrimeur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Expertise du combat]], [[Science de la feinte]], [[École de lescrimeur|École de l'escrimeur]], [[Moquerie de
      lescrimeur|Moquerie de l'escrimeur]], [[Arme de prédilection]] avec l'arme choisie, [[BBA]] +7
    </td>
    <td>Abandonne une attaque pour perturber un adversaire</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la furie orque]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Coup de brute]], [[Force intimidante]], 3 rangs en [[Intimidation]], trait racial [[Orque
      (race)#Traits_raciaux_standards_7|apprentissage martial]]
    </td>
    <td>Utilise Coup de brute sur la première attaque à chaque round</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Dévastation orque]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Coup de brute]], [[Force intimidante]], [[École de la furie orque]], 5 rangs en [[Intimidation]], trait
      racial [[Orque (race)#Traits_raciaux_standards_7|apprentissage martial]]
    </td>
    <td>Bonus à l'attaque et aux dégâts contre les adversaires secoués</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Grognement orque]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Coup de brute]], [[Force intimidante]], [[École de la furie orque]], [[Dévastation orque]], 7 rangs en
      [[Intimidation]], trait racial [[Orque (race)#Traits_raciaux_standards_7|apprentissage martial]]
    </td>
    <td>+4 aux jets de sauvegarde contre les effets créés par des adversaires secoués</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la grue]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Esquive]], [[Science du combat à mains nues]], [[BBA]] +2 ou [[moine]] de niveau 1</td>
    <td>Malus de -2 quand le personnage se bat sur la défensive</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Aile de la grue]]*</td>
    <td><sup>AG</sup></td>
    <td>[[École de la grue]], [[Esquive]], [[Science du combat à mains nues]], [[BBA]] +5 ou [[moine]] de niveau 5</td>
    <td>En cas de combat sur la défensive ou de défense totale, le personnage dévie une attaque par round</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Riposte de la grue]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[École de la grue]], [[Aile de la grue]], [[Esquive]], [[Science du combat à mains nues]], [[BBA]] +8 ou
      [[moine]] de niveau 7
    </td>
    <td>Quand le personnage dévie une attaque, il peut faire une attaque d'opportunité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la lance dansante]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Dex]] 13, [[Combat à deux armes]], [[Arme de prédilection]] avec l'arme choisie</td>
    <td>Ajoute l'attribut double à un type d'arme d'hast</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Spirale de la lance dansante]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Dex]] 15, [[École de la lance dansante]], [[Attaque en finesse]], [[Combat à deux armes]], [[Arme de
      prédilection]] avec l'arme choisie
    </td>
    <td>Avantages d'Attaque en finesse avec École de la lance dansante</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Allonge de la lance dansante]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Dex]] 17, [[École de la lance dansante]], [[Spirale de la lance dansante]], [[Attaque en finesse]], [[Combat
      à deux armes]], [[Arme de prédilection]] avec l'arme choisie
    </td>
    <td>Allonge augmentée avec École de la lance dansante</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la mante]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], [[Coup étourdissant]], 3 rangs en [[Premiers secours]]</td>
    <td>1 utilisation quotidienne de Coup étourdissant de plus, DD du Coup étourdissant augmenté de 2</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Sagesse de la mante]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[École de la mante]], [[Coup étourdissant]], 6 rangs en [[Premiers
      secours]]
    </td>
    <td>
      Pour les effets du Coup étourdissant, le personnage compte la moitié de ses niveaux d'autres classes comme des
      niveaux de moine
    </td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Tourment de la mante]]*</td>
    <td><sup>AG</sup></td>
    <td>
      9 rangs en [[Premiers secours]], [[Science du combat à mains nues]], [[École de la mante]], [[Sagesse de la
      mante]], [[Coup étourdissant]]
    </td>
    <td>
      1 utilisation quotidienne de Coup étourdissant de plus, possibilité d'éblouir l'adversaire et de le rendre
      chancelant avant de le fatiguer
    </td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la panthère]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Sag]] 13, [[Attaques réflexes]], [[Science du combat à mains nues]].</td>
    <td>Le personnage riposte contre un adversaire qui fait une attaque d'opportunité contre lui</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Griffe de la panthère]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Sag]] 15, [[Attaques réflexes]], [[Science du combat à mains nues]], [[École de la panthère]]</td>
    <td>La riposte est une action libre et non rapide</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Parade de la panthère]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 15, [[Attaques réflexes]], [[Science du combat à mains nues]], [[Griffe de la panthère]], [[École de
      la panthère]]
    </td>
    <td>La riposte se produit avant l'attaque qui l'a provoquée</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la rue]]*</td>
    <td><sup>*UI*</sup></td>
    <td>
      [[For]] 15, [[Attaque en puissance]], [[Science de la bousculade]], [[Science du combat à mains nues]],
      [[BBA]] +4 ou [[moine]] de niveau 3
    </td>
    <td>Inflige des dégâts supplémentaires et bouscule facilement en milieu urbain</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Balayage de la rue]]*</td>
    <td><sup>*UI*</sup></td>
    <td>
      [[For]] 15, [[Attaque en puissance]], [[École de la rue]], [[Science de la bousculade]], [[Science du combat à
      mains nues]], [[BBA]] +6 ou [[moine]] de niveau 5
    </td>
    <td>Attaquer un adversaire bousculé le fait tomber</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Tuerie de la rue]]*</td>
    <td><sup>*UI*</sup></td>
    <td>
      [[For]] 15, [[Attaque en puissance]], [[Balayage de la rue]], [[École de la rue]], [[Science de la
      bousculade]], [[Science du combat à mains nues]], [[BBA]] +8 ou [[moine]] de niveau 7
    </td>
    <td>Le facteur de critique des attaques à mains nues passe à ×3</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la sentinelle]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Tir de précision]], [[Tir rapide]], [[Arme de prédilection]] avec l'arme choisie</td>
    <td>Prépare deux attaques à distance</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Tactique de sentinelle]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École de la sentinelle]], [[Tir de précision]], [[Tir rapide]], [[Arme de prédilection]] avec l'arme
      choisie.
    </td>
    <td>Prépare deux attaques à distance par une action simple au lieu d'une action complexe</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Tourbillon de la sentinelle]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Tactique de la sentinelle]], [[École de la sentinelle]], [[Tir de précision]], [[Tir rapide]], [[Arme de
      prédilection]] avec l'arme choisie, [[BBA]] +11
    </td>
    <td>Prépare jusqu'à quatre attaques à distance au lieu de deux avec École de la sentinelle</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École de la tortue alligator]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], [[BBA]] +1 ou [[moine]] de niveau 1</td>
    <td>Quand le personnage a une main libre, il gagne un bonus de bouclier de +1 à la CA</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Étreinte de la tortue alligator]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[École de la tortue alligator]], [[Science de la lutte]], [[Science du combat à mains nues]], [[BBA]] +3 ou
      [[moine]] de niveau 3
    </td>
    <td>Le bonus de bouclier s'applique au DMD et à la CA au contact</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Carapace de la tortue alligator]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Étreinte de la tortue alligator]], [[École de la tortue alligator]], [[Science de la lutte]], [[Science du
      combat à mains nues]], [[BBA]] +5 ou [[moine]] de niveau 5
    </td>
    <td>Le bonus de CA augmente de 2 et les adversaires ont un malus de -4 aux confirmations de coup critique</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du bouclier bouleversant]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[Dex]] 13, maniement des [[targe (armure)|targes]]</td>
    <td>Utilise une targe pour effectuer des coups de bouclier</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Frappe du bouclier bouleversant]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 15, [[Attaques réflexes]], [[École du bouclier bouleversant]], [[Science du coup de bouclier]],
      maniement des [[targe (armure)|targes]]
    </td>
    <td>Les adversaires qui ratent le personnage provoquent une attaque d'opportunité</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Vengeance du bouclier bouleversant]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 13, [[Attaques réflexes]], [[École du bouclier bouleversant]], [[Frappe du bouclier bouleversant]],
      [[Science du coup de bouclier]], maniement des [[targe (armure)|targes]]
    </td>
    <td>Utilise Frappe du bouclier bouleversant contre les adversaires qui attaquent les alliés</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du boxeur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Science du combat à mains nues]]; [[BBA]] +6, capacité de classe [[Lutteur#DELUGEDECOUPSDULUTTEUR|déluge de
      coups du lutteur]] ou [[Moine#DELUGEDECOUPS|déluge de coups]]
    </td>
    <td>
      Gain d'un bonus aux dégâts quand deux attaques à mains nues ou plus touchent le même adversaire lors du tour
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Danse du boxeur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Esquive]], [[Science du combat à mains nues]], [[École du boxeur]], [[Souplesse du serpent]]; [[BBA]] +9,
      [[lutteur]] de nvieau 5, ou [[moine]] de niveau 5
    </td>
    <td>
      Le personnage se déplace de 1,50 mètre sans provoquer d'attaque d'opportunité chaque fois qu'il touche avec
      une attaque à mains nues
    </td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Maître boxeur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Esquive]], [[Science du combat à mains nues]], [[Danse du boxeur]], [[École du boxeur]], [[Souplesse du
      serpent]], [[Attaque en puissance]]; [[BBA]] +12, [[lutteur]] de niveau 8, ou [[moine]] de niveau 8
    </td>
    <td>Augmente les dégâts infligés avec École du boxeur</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du carquois vide]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Arme de prédilection]] avec l'arme choisie</td>
    <td>Combat au corps à corps avec une arme à distance</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Flexibilité du carquois vide]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École du carquois vide]], [[Tir rapide]], [[Coup de flèche]], [[Arme de prédilection]] avec l'arme choisie
    </td>
    <td>Applique les dons de combat à distance sur les attaques au corps à corps</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Frénésie du carquois vide]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Flexibilité du carquois vide]], [[École du carquois vide]], [[Tir rapide]], [[Coup de flèche]], [[Arme de
      prédilection]] avec l'arme choisie
    </td>
    <td>Utilise les armes à distance pour porter des attaques au corps à corps et évite les attaques d'opportunité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du cogneur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Science du combat à mains nues]]; [[BBA]] +6, capacité de classe [[Lutteur#DELUGEDECOUPSDULUTTEUR|déluge de
      coups du lutteur]] ou [[Moine#DELUGEDECOUPS|déluge de coups]]
    </td>
    <td>Le personnage combines ensemble ses attaques à mains nues</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Charge du cogneur]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Science du combat à mains nues]], [[École du cogneur]]; [[BBA]] +12, [[lutteur]] de niveau 8, ou [[moine]]
      de niveau 8
    </td>
    <td>Le personnage peut cogner après une charge</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Cogneur tyrannique]]*</td>
    <td><sup>MCA</sup></td>
    <td>
      [[Science du repositionnement]], [[Science du croc-en-jambe]], [[Science du combat à mains nues]], [[École du
      cogneur]]; [[BBA]] +9, [[lutteur]] de niveau 5, ou [[moine]] de niveau 5
    </td>
    <td>
      Quand il utilise École du cogneur, le personnage peut tenter une manœuvre offensive de croc-en-jambe ou de
      repositionnement par une action libre
    </td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du djinn]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 13, [[Sag]] 15, [[Poing élémentaire]], [[Science du combat à mains nues]], [[BBA]] +9 ou [[moine]] de
      niveau 5
    </td>
    <td>1 utilisation quotidienne de Poing élémentaire de plus et bonus aux dégâts électriques</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Esprit du djinn]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 15, [[École du djinn]], [[poing élémentaire]], [[Science du combat à mains nues]], [[BBA]]
      +11 ou [[moine]] de niveau 9
    </td>
    <td>1 utilisation quotidienne de Poing élémentaire de plus et résistance aux dégâts électriques</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Tourbillon du djinn]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 17, [[École du djinn]], [[Esprit du djinn]], [[Poing élémentaire]], [[Science du combat à
      mains nues]], [[BBA]] +13 ou [[moine]] de niveau 11
    </td>
    <td>Le Poing élémentaire permet au personnage de s'entourer d'un halo d'électricité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du dragon]]*</td>
    <td><sup>AG</sup></td>
    <td>[[For]] 15, [[Science du combat à mains nues]], 3 rangs en [[Acrobaties]]</td>
    <td>Bonus de +2 contre le sommeil, la paralysie et l'étourdissement. Peut ignorer le terrain difficile</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Férocité du dragon]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[For]] 15, [[Science du combat à mains nues]], [[École du dragon]], [[Coup étourdissant]], 5 rangs en
      [[Acrobaties]]
    </td>
    <td>Bonus aux attaques à mains nues et adversaires secoués</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Rugissement du dragon]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[For]] 15, [[Science du combat à mains nues]], [[École du dragon]], [[Coup étourdissant]], 8 rangs en
      [[Acrobaties]]
    </td>
    <td>1 utilisation quotidienne de Poing étourdissant de plus et rugissement dévastateur</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du fer rapide]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[For]] 13, [[Dex]] 13, formation au port des armures intermédiaires</td>
    <td>Améliore la manœuvrabilité en armure</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Refuge du fer rapide]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[For]] 13, [[Dex]] 13, [[École du fer rapide]], formation au port des armures intermédiaires</td>
    <td>Réduit les dégâts des dés supplémentaires au minimum</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Sprint du fer rapide]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[For]] 13, [[Dex]] 13, [[École du fer rapide]], [[Refuge du fer rapide]], formation au port des armures
      intermédiaires
    </td>
    <td>Ignore la réduction de vitesse de l'armure</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du fonceur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13; [[Expertise du combat]] ou capacité de classe [[lutteur#RUSEDULUTTEUR|ruse du lutteur]]; [[Arme de
      prédilection]] avec l'arme choisie
    </td>
    <td>+1 à la CA et aux dégâts avec une arme après un pas de placement</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Louvoyage du fonceur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Fente]], [[École du fonceur]]; [[Expertise du combat]] ou capacité de classe
      [[lutteur#RUSEDULUTTEUR|ruse du lutteur]]; [[Arme de prédilection]] avec l'arme choisie
    </td>
    <td>
      Pas de malus à la CA en utilisant Fente avec École du fonceur, le bonus à la CA et aux dégâts d'École du
      fonceur passe à +2
    </td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Sprint du fonceur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Fente]], [[Louvoyage du fonceur]], [[École du fonceur]]; [[Expertise du combat]] ou capacité de
      classe [[lutteur#RUSEDULUTTEUR|ruse du lutteur]]; [[Arme de prédilection]] avec l'arme choisie
    </td>
    <td>Déplacement de 1.5 m supplémentaire lors d'un pas de placement avec École du fonceur</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du fracasseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[For]] 13, [[Science de la destruction]], [[Attaque en puissance]], [[Arme de prédilection]] avec l'arme
      choisie
    </td>
    <td>Tentative de bousculade ou de croc-en-jambe gratuite après une manœuvre de destruction contre une armure</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Écrasement du fracasseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[For]] 13, [[Science de la destruction]], [[École du fracasseur]], [[Arme de prédilection]] avec l'arme
      choisie
    </td>
    <td>Réduit la solidité des objets que le personnage tente de détruire</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Martelage du fracasseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[For]] 13, [[Science de la destruction]], [[École du fracasseur]], [[Arme de prédilection]] avec l'arme
      choisie, [[BBA]] +6
    </td>
    <td>Réduit le bonus d'armure et augment le malus d'armure des armures que le personnage tente de détruire</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du frondeur-disperseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Arme de prédilection]] (fronde) ou capacité de classe [[Guerrier#ENTRAINEMENTAUXARMES|entraînement aux
      armes]] (armes de jet), trait racial [[Halfelin#Traits_raciaux_alternatifs_7|guerrier à la fronde]]
    </td>
    <td>+1 aux dégâts avec les frondes, ne provoque pas d'attaque d'opportunité en les rechargeant</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Grenadier frondeur-disperseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École du frondeur-disperseur]], [[Lancer improvisé]], [[Arme de prédilection]] (fronde) ou capacité de
      classe [[Guerrier#ENTRAINEMENTAUXARMES|entraînement aux armes]] (armes de jet), trait racial
      [[Halfelin#Traits_raciaux_alternatifs_7|guerrier à la fronde]]
    </td>
    <td>Utilise la fronde pour lancer des armes alchimiques à aspersion</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Bombardement du frondeur-disperseur]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Arme en main]], [[Grenadier frondeur-disperseur]], [[École du frondeur-disperseur]], [[Lancer improvisé]],
      [[Arme de prédilection]] (fronde) ou capacité de classe [[Guerrier#ENTRAINEMENTAUXARMES|entraînement aux
      armes]] (armes de jet), trait racial [[Halfelin#Traits_raciaux_alternatifs_7|guerrier à la fronde]]
    </td>
    <td>Utilise la fronde pour lancer plusieurs armes alchimiques</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du gantelet-bouclier]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Arme de prédilection]] ([[Gantelet (arme)|gantelet]] ou [[Gantelet clouté (arme)|gantelet clouté]]),
      formation au port des [[rondache (armure)|rondaches]] et des [[targe (armure)|targes]]
    </td>
    <td>Considère le gantelet de la main non-directrice comme une targe</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Attaque du gantelet-bouclier]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Arme de prédilection]] ([[Gantelet (arme)|gantelet]] ou [[Gantelet clouté (arme)|gantelet clouté]]), [[École
      du gantelet-bouclier]], formation au port des [[targe (armure)|targes]] et des [[rondache (armure)|rondaches]]
    </td>
    <td>Conserve le bonus de bouclier du gantelet même après avoir attaqué avec</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Maître du gantelet-bouclier]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Arme de prédilection]] ([[Gantelet (arme)|gantelet]] ou [[Gantelet clouté (arme)|gantelet clouté]]),
      [[Attaque du gantelet-bouclier]], [[École du gantelet-bouclier]], formation au port des [[targe
      (armure)|targes]] et des [[rondache (armure)|rondaches]]
    </td>
    <td>Augmente les dégâts du gantelet et l'utilise pour désarmer ou subtiliser pendant une attaque d'opportunité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du gnome illusoire]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Expertise du combat]], [[Arme de prédilection gnome]], [[Science de la feinte]], [[BBA]] +1,
      Traits raciaux [[Gnome#Traits_raciaux_standards_6|armes familières]] et
      [[Gnome#Traits_raciaux_standards_6|magie gnome]]
    </td>
    <td>Sacrifie des sorts pour obtenir un bonus aux tests feinte</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Surprise du gnome illusoire]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Expertise du combat]], [[Arme de prédilection gnome]], [[École du gnome illusoire]], [[Science
      de la feinte]]
    </td>
    <td>+2 aux tests de sale coup et de Bluff pour feinter, nouveaux avantages avec École du gnome illusoire</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Confusion du gnome illusoire]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Expertise du combat]], [[Arme de prédilection gnome]], [[Surprise du gnome illusoire]], [[École
      du gnome illusoire]], [[Science de la feinte]], Traits raciaux [[Gnome#Traits_raciaux_standards_6|armes
      familières]] et [[Gnome#Traits_raciaux_standards_6|magie gnome]]
    </td>
    <td>Avantages spéciaux lors d'une feinte</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du guerrier elfique]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Entraînement guerrier elfique]], [[BBA]] +1, trait racial [[Elfe#Traits_raciaux_standards_6|armes
      familières]]
    </td>
    <td>Ne provoque pas d'attaque d'opportunité lors de manœuvres offensives portées avec des armes elfiques</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Concentration du guerrier elfique]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Entraînement guerrier elfique]], [[École du guerrier elfique]], [[Attaque en finesse]], [[BBA]]
      +4, trait racial [[Elfe#Traits_raciaux_standards_6|armes familières]]
    </td>
    <td>
      Quand il utilise École du guerrier elfique, le personnage ajoute le modificateur d'Intelligence aux dégâts des
      armes
    </td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Torrent du guerrier elfique]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Int]] 13, [[Entraînement guerrier elfique]], [[Concentration du guerrier elfique]], [[École du guerrier
      elfique]], [[Attaque en finesse]], [[BBA]] +10, trait racial d'[[Elfe#Traits_raciaux_standards_6|armes
      familières]]
    </td>
    <td>Les adversaires provoquent des attaques d'opportunité quand le personnage se bat sur la défensive</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du hibou]]*</td>
    <td><sup>*UI*</sup></td>
    <td>[[Dex]] 13, [[Talent]] (Discrétion), 1 rang en [[Discrétion]]</td>
    <td>Base la Discrétion sur l'entraînement martial et charge avec Discrétion</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Piqué du hibou]]*</td>
    <td><sup>*UI*</sup></td>
    <td>[[Dex]] 15, [[École du hibou]], [[Talent]] (Discrétion), 1 rang en [[Acrobaties]], 1 rang en [[Discrétion]]</td>
    <td>Base Acrobaties sur l'entraînement martial et charge avec Acrobaties</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Plongeon du hibou]]*</td>
    <td><sup>*UI*</sup></td>
    <td>
      [[Dex]] 17, [[École du hibou]], [[Piqué du hibou]], [[Talent]] (Discrétion), [[BBA]] +7 ou [[moine]] de niveau
      5, 1 rang en [[Acrobaties]], 1 rang en [[Discrétion]], 1 rang en [[Vol]]
    </td>
    <td>Base le Vol sur l'entraînement martial et charge à travers une créature</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du jann]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], 3 rangs en [[Acrobaties]], 3 rangs en [[Représentation]] (danse)</td>
    <td>
      -1 à la CA du personnage lorsqu'il charge et bonus de +1 seulement aux jets d'attaque des adversaires quand
      ils le prennent en tenaille
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Tempête du jann]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[École du jann]], 5 rangs en [[Acrobaties]], 5 rangs en
      [[Représentation]] (danse)
    </td>
    <td>Après une attaque à mains nues réussie, le personnage gagne +4 aux tests de bousculade ou de croc-en-jambe</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Ruée du jann]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[École du jann]], [[Tempête du jann]], 8 rangs en [[Acrobaties]], 8 rangs
      en [[Représentation]] (danse)
    </td>
    <td>
      Quand le personnage saute, on considère toujours qu'il a fait une course d'élan, dégâts doublés s'il saute
      lors d'une charge
    </td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du kirin]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], 6 rangs en [[Connaissances]] (Mystères), 1 rang en [[Connaissances]]
      (exploration souterraine, folklore local, nature, plans, ou religion)
    </td>
    <td>
      Le personnage peut faire des tests de Connaissances par une action rapide pour gagner un bonus contre un
      adversaire
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Frappe du kirin]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Int]] 13, [[École du kirin]], [[Science du combat à mains nues]], 9 rangs en [[Connaissances]] (Mystères), 3
      rangs en [[Connaissances]] (exploration souterraine, folklore local, nature, plans, ou religion)
    </td>
    <td>Bonus d'intuition de +2 pour identifier une créature</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Voie du kirin]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Int]] 13, [[Frappe du kirin]], [[École du kirin]], [[Science du combat à mains nues]], 12 rangs en
      [[Connaissances]] (Mystères), 5 rangs en [[Connaissances]] (exploration souterraine, folklore local, nature,
      plans, ou religion)
    </td>
    <td>
      Le personnage peut faire 10 à un test de Connaissances (folklore local, nature, plans ou religion) pour
      identifier
    </td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du kitsune]]*</td>
    <td><sup>*DTT*</sup></td>
    <td>[[Int]] 13, [[Expertise du combat]], [[Science du sale coup]]</td>
    <td>Effectue un sale coup après une charge</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Tours du kitsune]]*</td>
    <td><sup>*DTT*</sup></td>
    <td>
      [[Int]] 13; [[Expertise du combat]]; [[Science du sale coup]], [[École du kitsune]]; [[BBA]] +3 ou [[moine]]
      de niveau 3
    </td>
    <td>Applique deux états préjudiciables en utilisant l'école du kitsune</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Vengeance du kitsune]]*</td>
    <td><sup>*DTT*</sup></td>
    <td>
      [[Int]] 13; [[Expertise du combat]]; [[Science du sale coup]]; [[École du kitsune]]; [[Tours du kitsune]];
      [[BBA]] +6 ou [[moine]] de niveau 6
    </td>
    <td>Effecue un sale coup à la place d'une attaque d'opportunité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du lancer détoile|École du lancer d'étoile]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>[[Dex]] 13, [[Tir à bout portant]], [[Arme de prédilection]] avec l'arme choisie</td>
    <td>Gain de bonus aux dégâts avec un type d'armes de jet</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Comète du lancer détoile|Comète du lancer d'étoile]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Dex]] 13, [[Tir à bout portant]], [[École du lancer détoile|École du lancer d'étoile]], [[Arme de
      prédilection]] avec l'arme choisie
    </td>
    <td>Attaque supplémentaire avec une arme de jet par une action simple</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Pluie du lancer détoile|Pluie du lancer d'étoile]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[Dex]] 13, [[Tir à bout portant]], [[BBA]] +4, [[Comète du lancer détoile|Comète du lancer d'étoile]],
      [[École du lancer détoile|École du lancer d'étoile]], [[Arme de prédilection]] avec l'arme choisie
    </td>
    <td>Attaque d'autres adversaires proches de la cible initiale avec École du lancer d'étoile</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du marid]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 13, [[Sag]] 15, [[Poing élémentaire]], [[Science du combat à mains nues]], [[BBA]] +9 ou [[moine]] de
      niveau 5
    </td>
    <td>1 utilisation quotidienne du Poing élémentaire de plus et inflige des dégâts de froid</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Esprit du marid]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 15, [[Poing élémentaire]], [[École du marid]], [[Science du combat à mains nues]], [[BBA]]
      +11 ou [[moine]] de niveau 9
    </td>
    <td>1 utilisation quotidienne du Poing élémentaire de plus et une résistance au froid</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Froid du marid]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 17, [[Poing élémentaire]], [[Esprit du marid]], [[École du marid]], [[Science du combat à
      mains nues]], [[BBA]] +13 ou [[moine]] de niveau 11
    </td>
    <td>Projette un jet d'eau glacée sur une ligne de 9 m</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du rempart mobile]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[For]] 13, [[Art du bouclier]], [[Maniement du pavois]], [[BBA]] +1</td>
    <td>
      Ajoute le bonus de bouclier à la CA au DMD contre les manœuvres de bousculade et de renversement, utilise le
      pavois plus rapidement
    </td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Forteresse du rempart mobile]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>[[For]] 15, [[Art du bouclier]], [[École du rempart mobile]], [[Maniement du pavois]], [[BBA]] +4</td>
    <td>Ajoute la moitié du bonus de bouclier à la CA au contact</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Bastion du rempart mobile]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[For]] 17, [[Art du bouclier]], [[École du rempart mobile]], [[Forteresse du rempart mobile]], [[Maniement du
      pavois]], [[BBA]] +7
    </td>
    <td>Applique un abri partiel contre les sorts et un abri total contre une attaque par une action immédiate</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du renard]]*</td>
    <td><sup>*UI*</sup></td>
    <td>[[Int]] 13</td>
    <td>Feinte et distrait les adversaires grâce à un entraînement martial</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Intuition du renard]]*</td>
    <td><sup>*UI*</sup></td>
    <td>[[Int]] 13, [[École du renard]]</td>
    <td>Le personnage est plus difficile à feinter et à démoraliser</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Tromperie du renard]]*</td>
    <td><sup>*UI*</sup></td>
    <td>[[Int]] 13, [[École du renard]], [[Expertise du combat]], [[Intuition du renard]], [[Science du sale coup]]</td>
    <td>Fait des manœuvres de sale coup comme attaque d'opportunité</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du sanglier]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], 3 rangs en [[Intimidation]]</td>
    <td>Les attaques à mains nues infligent des dégâts contondants ou perforants</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Férocité du sanglier]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], [[École du sanglier]], 6 rangs en [[Intimidation]]</td>
    <td>Ajoute des dégâts perforants aux attaques à mains nues et démoralise les adversaires</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Déchiquetage du sanglier]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[Férocité du sanglier]], [[École du sanglier]], 9 rangs en
      [[Intimidation]]
    </td>
    <td>Les attaques à mains nues provoquent un saignement</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du serpent]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], 1 rang en [[Acrobaties]], 3 rangs en [[Psychologie]]</td>
    <td>+2 aux tests de Psychologie, dégâts perforants avec les attaques à mains nues</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Balancement du serpent]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[École du serpent]], 3 rangs en [[Acrobaties]], 6 rangs en
      [[Psychologie]]
    </td>
    <td>Bonus pour ne pas tomber à terre, test de psychologie pour confirmer un coup critique</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Croc du serpent]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Attaques réflexes]], [[Science du combat à mains nues]], [[Balancement du serpent]], [[École du serpent]], 6
      rangs en [[Acrobaties]], 9 rangs en [[Psychologie]]
    </td>
    <td>Si l'adversaire rate le personnage, ce dernier a droit à une attaque d'opportunité par une action immédiate</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du shaitan]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 13, [[Sag]] 15, [[Poing élémentaire]], [[Science du combat à mains nues]], [[BBA]] +9 ou [[moine]] de
      niveau 5
    </td>
    <td>1 utilisation quotidienne du Poing élémentaire de plus et inflige des dégâts d'acide</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Peau du shaitan]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 15, [[Poing élémentaire]], [[Science du combat à mains nues]], [[École du shaitan]],
      [[BBA]] +11 ou [[moine]] de niveau 9
    </td>
    <td>1 utilisation quotidienne du Poing élémentaire de plus et une résistance à l'acide</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Séisme du shaitan]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Con]] 15, [[Sag]] 17, [[Poing élémentaire]], [[Science du combat à mains nues]], [[Peau du shaitan]],
      [[École du shaitan]], [[BBA]] +13 ou [[moine]] de niveau 11
    </td>
    <td>Fait jaillir une colonne d'acide de 6 m</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du singe]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Sag]] 13, [[Science du combat à mains nues]], 5 rangs en [[Acrobaties]], 5 rangs en [[Escalade]]</td>
    <td>Le personnage ajoute son bonus de Sagesse aux tests d'Acrobatie et n'a pas de malus quand il attaque couché</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Mouvements du singe]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 13, [[Science du combat à mains nues]], [[École du singe]], 8 rangs en [[Acrobaties]], 8 rangs en
      [[Escalade]]
    </td>
    <td>
      Le personnage ajoute son bonus de Sagesse aux tests d'Escalade. Il grimpe et rampe à la moitié de sa vitesse
    </td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Éclat du singe]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Sag]] 13, [[Science du combat à mains nues]], [[Mouvements du singe]], [[École du singe]], [[Coup
      étourdissant]], 11 rangs en [[Acrobaties]], 11 rangs en [[Escalade]]
    </td>
    <td>Le personnage peut entrer dans une case adjacente après un Coup étourdissant</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du talon-à-ressorts]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 13, [[Esquive]], [[Souplesse du serpent]], [[Tir en mouvement]] ou [[Attaque éclair]], [[BBA]] +4,
      formation au port des armures légères
    </td>
    <td>Gain d'un bonus à l'attaque après un déplacement</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Sprint du talon-à-ressorts]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 15, [[École du talon-à-ressorts]], [[Esquive]], [[Souplesse du serpent]], [[Tir en mouvement]] ou
      [[Attaque éclair]], [[BBA]] +7, formation au port des armures légères
    </td>
    <td>Se déplace jusqu'au double de la vitesse pendant un Tir en mouvement ou une Attaque éclair</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Fauchage du talon-à-ressorts]]*</td>
    <td><sup>*AMH*</sup></td>
    <td>
      [[Dex]] 17, [[École du talon-à-ressorts]], [[Esquive]], [[Souplesse du serpent]], [[Tir en mouvement]] ou
      [[Attaque éclair]], [[Sprint du talon-à-ressorts]], [[BBA]] +11, formation au port des armures légères
    </td>
    <td>Attaque deux créatures pendant un Tir en mouvement ou une Attaque éclair</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École du tigre]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], [[BBA]] +3 ou [[moine]] de niveau 3</td>
    <td>+2 au DMD contre la bousculade, le renversement et le croc-en-jambe. Inflige des dégâts tranchants</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Griffes du tigre]]*</td>
    <td><sup>AG</sup></td>
    <td>[[Science du combat à mains nues]], [[École du tigre]], [[BBA]] +6 ou [[moine]] de niveau 5</td>
    <td>Le personnage porte une seule attaque avec les deux mains et additionne le résultat des deux</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Bond du tigre]]*</td>
    <td><sup>AG</sup></td>
    <td>
      [[Science du combat à mains nues]], [[Attaque en puissance]], [[Griffes du tigre]], [[École du tigre]],
      [[BBA]] +9 ou [[moine]] de niveau 8
    </td>
    <td>Peut appliquer le malus de l'Attaque en puissance à la CA</td>
  </tr>
  <tr CLASS="premier donprincipal">
    <td>[[École haineuse naine]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[BBA]] +1, traits raciaux [[Nain#Traits_raciaux_standards_6|entraînement défensif]] et
      [[Nain#Traits_raciaux_standards_6|haine]], taille M
    </td>
    <td>Applique la haine aux jets d'attaque et de dégâts, et son bonus passe à +2</td>
  </tr>
  <tr CLASS="donprérequis0">
    <td>&emsp;[[Irritation naine]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École haineuse naine]], [[BBA]] +5, Traits raciaux [[Nain#Traits_raciaux_standards_6|entraînement défensif]]
      et [[Nain#Traits_raciaux_standards_6|haine]], taille M
    </td>
    <td>Applique la haine et l'entraînement défensif à des types/sous-types différents</td>
  </tr>
  <tr CLASS="donprérequis1">
    <td>&emsp;&emsp;[[Fureur naine]]*</td>
    <td><sup>*WMH*</sup></td>
    <td>
      [[École haineuse naine]], [[Irritation naine]], [[BBA]] +7, traits raciaux
      [[Nain#Traits_raciaux_standards_6|entraînement défensif]] et [[Nain#Traits_raciaux_standards_6|haine]], taille
      M
    </td>
    <td>Utilise Irritation naine contre n'importe quel nombre d'adversaires</td>
  </tr>
</table>

</center>
