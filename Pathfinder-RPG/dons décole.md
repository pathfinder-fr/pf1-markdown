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

Par une [action rapide](./Action rapide.md), le personnage peut adopter la posture de référence de l’école liée au don. Il ne peut pas utiliser de don d’école avant le début du combat mais il conserve la posture choisie jusqu’à ce qu’il dépense une action rapide pour changer d’école. Si une école particulière figure dans les conditions requises d’un don, le personnage doit obligatoirement se trouver dans la posture de cette école pour l’utiliser.
*Par exemple, si le personnage connaît des dons liés à l’École de la mante et à celle du tigre, il peut utiliser une action rapide pour adopter l’École du tigre au début de son tour puis utiliser d’autres dons qui exigent l’École du tigre comme condition requise. Au début du tour suivant, il peut dépenser une nouvelle action rapide pour adopter l’École de la mante et utiliser des dons associés à cette école.*

*Les dons marqués d'un astérisque (*) sont des dons de combat.*
<center>
{| CLASS="tablo autoalt toutgauche"
|+ Tableau récapitulatif des dons d'école
|- CLASS="titre"
| WIDTH="25%" | Dons
| WIDTH="3%" | Src
| WIDTH="36%" | Conditions
| WIDTH="36%" | Avantages

|- CLASS="premier donprincipal"
| [École de l'ascète](./École de lascète.md)* || <sup>*WMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) avec l'arme de corps à corps choisie, [BBA](./BBA.md) +1 ou [moine](./Moine.md) de niveau 1  || Utilise des armes dans le cadre des capacités à mains nues
|- CLASS="donprérequis0"
| &emsp;[Forme de l'ascète](./Forme de lascète.md)* || <sup>*WMH*</sup> || [École de l'ascète](./École de lascète.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme de corps à corps choisie, [BBA](./BBA.md) +5 ou [moine](./Moine.md) de niveau 5 || Utilise une nouvelle arme de corps à corps dans le cadre des capacités à mains nues
|- CLASS="donprérequis1"
| &emsp;&emsp;[Frappe de l'ascète](./Frappe de lascète.md)* || <sup>*WMH*</sup> || [Forme de l'ascète](./Forme de lascète.md), [École de l'ascète](./École de lascète.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +7 ou [moine](./Moine.md) de niveau 7 || Utilise les dégâts à mains nues d'un moine de niveau inférieur à la place des dés de dégâts de l'arme

|- CLASS="premier donprincipal"
| [École de l'avant-garde](./École de lavant-garde.md)* || <sup>*AMH*</sup> || [Attaques réflexes](./Attaques réflexes.md), [Garde du corps](./Garde du corps.md), maniement des [rondaches](./rondache (armure).md) ou des [écus](./écu (armure).md) || Utilise Garde du corps pour améliorer les jets de Réflexes des alliés
|- CLASS="donprérequis0"
| &emsp;[Protecteur de l'avant-garde](./Protecteur de lavant-garde.md)* || <sup>*AMH*</sup> || [Attaques réflexes](./Attaques réflexes.md), [École de l'avant-garde](./École de lavant-garde.md), [Garde du corps](./Garde du corps.md), maniement des [rondaches](./rondache (armure).md) ou des [écus](./écu (armure).md) || Utilise Garde du corps et École de l'avant-garde dans la même action
|- CLASS="donprérequis1"
| &emsp;&emsp;[Frénésie de l'avant-garde](./Frénésie de lavant-garde.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 13, [Attaques réflexes](./Attaques réflexes.md), [Bouclier salvateur](./Bouclier salvateur.md), [École de l'avant-garde](./École de lavant-garde.md), [Garde du corps](./Garde du corps.md), [Patrouille en combat](./Patrouille en combat.md), [Protecteur de l'avant-garde](./Protecteur de lavant-garde.md), [Souplesse du serpent](./Souplesse du serpent.md), maniement des [rondaches](./rondache (armure).md) ou des [écus](./écu (armure).md) || Ajoute la moitié du bonus d'altération du bouclier au bonus de Bouclier salvateur

|- CLASS="premier donprincipal"
| [École de la bulette renversante](./École de la bulette renversante.md)* || <sup>*AMH*</sup> || [For](./For.md) 13, [Attaque en puissance](./Attaque en puissance.md), [Science du renversement](./Science du renversement.md), formation au port des armures lourdes || +4 aux manœuvres de renversement
|- CLASS="donprérequis0"
| &emsp;[Bond de la bulette renversante](./Bond de la bulette renversante.md)* || <sup>*AMH*</sup> || [For](./For.md) 15, [Attaque en puissance](./Attaque en puissance.md), [École de la bulette renversante](./École de la bulette renversante.md), [Science du renversement](./Science du renversement.md), formation au port des armures lourdes || Renverse plusieurs adversaire et ajoute le modificateur de Force aux tests d'Acrobaties pour sauter
|- CLASS="donprérequis1"
| &emsp;&emsp;[Carnage de la bulette renversante](./Carnage de la bulette renversante.md)* || <sup>*AMH*</sup> || [For](./For.md) 15, [Attaque en puissance](./Attaque en puissance.md), [Bond de la bulette renversante](./Bond de la bulette renversante.md), [École de la bulette renversante](./École de la bulette renversante.md), [Science du renversement](./Science du renversement.md), formation au port des armures lourdes || Inflige des dégâts après un renversement réussi

|- CLASS="premier donprincipal"
| [École de l'efrit](./École de lefrit.md)* || <sup>AG</sup> || [Con](./Con.md) 13, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +9 ou [moine](./Moine.md) de niveau 5 || Une utilisation quotidienne de Poing élémentaire de plus et un bonus aux dégâts de feu
|- CLASS="donprérequis0"
| &emsp;[Posture de l'efrit](./Posture de lefrit.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 15, [École de l'efrit](./École de lefrit.md), [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +11 ou [moine](./Moine.md) de niveau 9 || Une utilisation quotidienne de Poing élémentaire de plus et résistance au feu
|- CLASS="donprérequis1"
| &emsp;&emsp;[Caresse de l'efrit](./Caresse de lefrit.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 17, [École de l'efrit](./École de lefrit.md), [Posture de l'efrit](./Posture de lefrit.md), [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +13 ou [moine](./Moine.md) de niveau 11 || Le personnage projette un cône de feu qui peut enflammer ses adversaires

|- CLASS="premier donprincipal"
| [École de l'empoigneur](./École de lempoigneur.md)* || <sup>MCA</sup> || [Science de la lutte](./Science de la lutte.md); [BBA](./BBA.md) +6, capacité de classe [déluge de coups du lutteur](./Lutteur.md#DELUGEDECOUPSDULUTTEUR) ou [déluge de coups](./Moine.md#DELUGEDECOUPS) || Le personnage ne reçoit aucun malus lorsqu'il agrippe un ennemi à une main et conserve son bonus de Dex à la CA quand il l'immobilise
|- CLASS="donprérequis0"
| &emsp;[Traction de l'empoigneur](./Traction de lempoigneur.md)* || <sup>MCA</sup> || [École de l'empoigneur](./École de lempoigneur.md), [Science de la lutte](./Science de la lutte.md); [BBA](./BBA.md) +8, [lutteur](./Lutteur.md) de niveau 4, ou [moine](./Moine.md) de niveau 4 || Le personnage se déplace plus loin avec les ennemis qu'il traîne
|- CLASS="donprérequis1"
| &emsp;&emsp;[Maître empoigneur](./Maître empoigneur.md)* || <sup>MCA</sup> || [Traction de l'empoigneur](./Traction de lempoigneur.md), [École de l'empoigneur](./École de lempoigneur.md), [Science de la lutte](./Science de la lutte.md); [BBA](./BBA.md) +12, [lutteur](./Lutteur.md) de niveau 8, ou [moine](./Moine.md) de niveau 8 || Le personnage agrippe deux ennemis au lieu d'un seul

|- CLASS="premier donprincipal"
| [École de l'enfant de la terre](./École de lenfant de la terre.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [nain](./Nain.md) ou [gnome](./Gnome.md), trait racial entraînement défensif, [Science du combat à mains nues](./Science du combat à mains nues.md), 3 rangs en [Acrobaties](./Acrobaties.md) || La CA de l'entraînement défensif passe à +6 contre les géants
|- CLASS="donprérequis0"
| &emsp;[Renversement de l'enfant de la terre](./Renversement de lenfant de la terre.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [nain](./Nain.md) ou [gnome](./Gnome.md), trait racial entraînement défensif, [École de l'enfant de la terre](./École de lenfant de la terre.md), [Science du croc-en-jambe](./Science du croc-en-jambe.md), [Science du combat à mains nues](./Science du combat à mains nues.md), 6 rangs en [Acrobaties](./Acrobaties.md) || Le personnage peut faire un croc-en-jambe à un géant de taille TG au maximum
|- CLASS="donprérequis1"
| &emsp;&emsp;[Lien de l'enfant de la terre](./Lien de lenfant de la terre.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [nain](./Nain.md) ou [gnome](./Gnome.md), trait racial entraînement défensif, [École de l'enfant de la terre](./École de lenfant de la terre.md), [Renversement de l'enfant de la terre](./Renversement de lenfant de la terre.md), [Croc-en-jambe supérieur](./Croc-en-jambe supérieur.md), [Science du croc-en-jambe](./Science du croc-en-jambe.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [Coup étourdissant](./Coup étourdissant.md), 9 rangs en [Acrobaties](./Acrobaties.md) || Le personnage peut faire un croc-en-jambe à un géant de n'importe quelle taille. Il peut décider d'appliquer le Coup étourdissant une fois qu'il sait que l'attaque d'opportunité portée contre un géant qui se relève a touché

|- CLASS="premier donprincipal"
| [École de l'escrimeur](./École de lescrimeur.md)* || <sup>*WMH*</sup> || [Expertise du combat](./Expertise du combat.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +3 || Bonus de bouclier de +1 à la CA en combat sur la défensive, évite le malus d'Expertise du combat sur la première attaque à chaque round
|- CLASS="donprérequis0"
| &emsp;[Moquerie de l'escrimeur](./Moquerie de lescrimeur.md)* || <sup>*WMH*</sup> || [Expertise du combat](./Expertise du combat.md), [Science de la feinte](./Science de la feinte.md), [École de l'escrimeur](./École de lescrimeur.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +5 || Feinte un adversaire qui rate une attaque contre le personnage
|- CLASS="donprérequis1"
| &emsp;&emsp;[Parade de l'escrimeur](./Parade de lescrimeur.md)* || <sup>*WMH*</sup> || [Expertise du combat](./Expertise du combat.md), [Science de la feinte](./Science de la feinte.md), [École de l'escrimeur](./École de lescrimeur.md), [Moquerie de l'escrimeur](./Moquerie de lescrimeur.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +7 || Abandonne une attaque pour perturber un adversaire

|- CLASS="premier donprincipal"
| [École de la furie orque](./École de la furie orque.md)* || <sup>*WMH*</sup> || [Coup de brute](./Coup de brute.md), [Force intimidante](./Force intimidante.md), 3 rangs en [Intimidation](./Intimidation.md), trait racial [apprentissage martial](./orque (race).md#Traits_raciaux_standards_7) || Utilise Coup de brute sur la première attaque à chaque round
|- CLASS="donprérequis0"
| &emsp;[Dévastation orque](./Dévastation orque.md)* || <sup>*WMH*</sup> || [Coup de brute](./Coup de brute.md), [Force intimidante](./Force intimidante.md), [École de la furie orque](./École de la furie orque.md), 5 rangs en [Intimidation](./Intimidation.md), trait racial [apprentissage martial](./orque (race).md#Traits_raciaux_standards_7) || Bonus à l'attaque et aux dégâts contre les adversaires secoués
|- CLASS="donprérequis1"
| &emsp;&emsp;[Grognement orque](./Grognement orque.md)* || <sup>*WMH*</sup> || [Coup de brute](./Coup de brute.md), [Force intimidante](./Force intimidante.md), [École de la furie orque](./École de la furie orque.md), [Dévastation orque](./Dévastation orque.md), 7 rangs en [Intimidation](./Intimidation.md), trait racial [apprentissage martial](./orque (race).md#Traits_raciaux_standards_7) || +4 aux jets de sauvegarde contre les effets créés par des adversaires secoués

|- CLASS="premier donprincipal"
| [École de la grue](./École de la grue.md)* || <sup>AG</sup> || [Esquive](./Esquive.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +2 ou [moine](./Moine.md) de niveau 1 || Malus de -2 quand le personnage se bat sur la défensive
|- CLASS="donprérequis0"
| &emsp;[Aile de la grue](./Aile de la grue.md)* || <sup>AG</sup> || [École de la grue](./École de la grue.md), [Esquive](./Esquive.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +5 ou [moine](./Moine.md) de niveau 5 || En cas de combat sur la défensive ou de défense totale, le personnage dévie une attaque par round
|- CLASS="donprérequis1"
| &emsp;&emsp;[Riposte de la grue](./Riposte de la grue.md)* || <sup>AG</sup> || [École de la grue](./École de la grue.md), [Aile de la grue](./Aile de la grue.md), [Esquive](./Esquive.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +8 ou [moine](./Moine.md) de niveau 7 || Quand le personnage dévie une attaque, il peut faire une attaque d'opportunité

|- CLASS="premier donprincipal"
| [École de la lance dansante](./École de la lance dansante.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 13, [Combat à deux armes](./Combat à deux armes.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Ajoute l'attribut double à un type d'arme d'hast
|- CLASS="donprérequis0"
| &emsp;[Spirale de la lance dansante](./Spirale de la lance dansante.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 15, [École de la lance dansante](./École de la lance dansante.md), [Attaque en finesse](./Attaque en finesse.md), [Combat à deux armes](./Combat à deux armes.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Avantages d'Attaque en finesse avec École de la lance dansante
|- CLASS="donprérequis1"
| &emsp;&emsp;[Allonge de la lance dansante](./Allonge de la lance dansante.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 17, [École de la lance dansante](./École de la lance dansante.md), [Spirale de la lance dansante](./Spirale de la lance dansante.md), [Attaque en finesse](./Attaque en finesse.md), [Combat à deux armes](./Combat à deux armes.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Allonge augmentée avec École de la lance dansante

|- CLASS="premier donprincipal"
| [École de la mante](./École de la mante.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [Coup étourdissant](./Coup étourdissant.md), 3 rangs en [Premiers secours](./Premiers secours.md) || 1 utilisation quotidienne de Coup étourdissant de plus, DD du Coup étourdissant augmenté de 2
|- CLASS="donprérequis0"
| &emsp;[Sagesse de la mante](./Sagesse de la mante.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École de la mante](./École de la mante.md), [Coup étourdissant](./Coup étourdissant.md), 6 rangs en [Premiers secours](./Premiers secours.md) || Pour les effets du Coup étourdissant, le personnage compte la moitié de ses niveaux d'autres classes comme des niveaux de moine
|- CLASS="donprérequis1"
| &emsp;&emsp;[Tourment de la mante](./Tourment de la mante.md)* || <sup>AG</sup> || 9 rangs en [Premiers secours](./Premiers secours.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [École de la mante](./École de la mante.md), [Sagesse de la mante](./Sagesse de la mante.md), [Coup étourdissant](./Coup étourdissant.md) || 1 utilisation quotidienne de Coup étourdissant de plus, possibilité d'éblouir l'adversaire et de le rendre chancelant avant de le fatiguer

|- CLASS="premier donprincipal"
| [École de la panthère](./École de la panthère.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [Attaques réflexes](./Attaques réflexes.md), [Science du combat à mains nues](./Science du combat à mains nues.md). || Le personnage riposte contre un adversaire qui fait une attaque d'opportunité contre lui
|- CLASS="donprérequis0"
| &emsp;[Griffe de la panthère](./Griffe de la panthère.md)* || <sup>AG</sup> || [Sag](./Sag.md) 15, [Attaques réflexes](./Attaques réflexes.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [École de la panthère](./École de la panthère.md) || La riposte est une action libre et non rapide
|- CLASS="donprérequis1"
| &emsp;&emsp;[Parade de la panthère](./Parade de la panthère.md)* || <sup>AG</sup> || [Sag](./Sag.md) 15, [Attaques réflexes](./Attaques réflexes.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [Griffe de la panthère](./Griffe de la panthère.md), [École de la panthère](./École de la panthère.md) || La riposte se produit avant l'attaque qui l'a provoquée

|- CLASS="premier donprincipal"
| [École de la rue](./École de la rue.md)* || <sup>*UI*</sup> || [For](./For.md) 15, [Attaque en puissance](./Attaque en puissance.md), [Science de la bousculade](./Science de la bousculade.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +4 ou [moine](./Moine.md) de niveau 3 || Inflige des dégâts supplémentaires et bouscule facilement en milieu urbain
|- CLASS="donprérequis0"
| &emsp;[Balayage de la rue](./Balayage de la rue.md)* || <sup>*UI*</sup> || [For](./For.md) 15, [Attaque en puissance](./Attaque en puissance.md), [École de la rue](./École de la rue.md), [Science de la bousculade](./Science de la bousculade.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +6 ou [moine](./Moine.md) de niveau 5 || Attaquer un adversaire bousculé le fait tomber
|- CLASS="donprérequis1"
| &emsp;&emsp;[Tuerie de la rue](./Tuerie de la rue.md)* || <sup>*UI*</sup> || [For](./For.md) 15, [Attaque en puissance](./Attaque en puissance.md), [Balayage de la rue](./Balayage de la rue.md), [École de la rue](./École de la rue.md), [Science de la bousculade](./Science de la bousculade.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +8 ou [moine](./Moine.md) de niveau 7 || Le facteur de critique des attaques à mains nues passe à ×3

|- CLASS="premier donprincipal"
| [École de la sentinelle](./École de la sentinelle.md)* || <sup>*WMH*</sup> || [Tir de précision](./Tir de précision.md), [Tir rapide](./Tir rapide.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Prépare deux attaques à distance
|- CLASS="donprérequis0"
| &emsp;[Tactique de sentinelle](./Tactique de sentinelle.md)* || <sup>*WMH*</sup> || [École de la sentinelle](./École de la sentinelle.md), [Tir de précision](./Tir de précision.md), [Tir rapide](./Tir rapide.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie. || Prépare deux attaques à distance par une action simple au lieu d'une action complexe
|- CLASS="donprérequis0"
| &emsp;[Tourbillon de la sentinelle](./Tourbillon de la sentinelle.md)* || <sup>*WMH*</sup> || [Tactique de la sentinelle](./Tactique de la sentinelle.md), [École de la sentinelle](./École de la sentinelle.md), [Tir de précision](./Tir de précision.md), [Tir rapide](./Tir rapide.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +11 || Prépare jusqu'à quatre attaques à distance au lieu de deux avec École de la sentinelle

|- CLASS="premier donprincipal"
| [École de la tortue alligator](./École de la tortue alligator.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +1 ou [moine](./Moine.md) de niveau 1 || Quand le personnage a une main libre, il gagne un bonus de bouclier de +1 à la CA
|- CLASS="donprérequis0"
| &emsp;[Étreinte de la tortue alligator](./Étreinte de la tortue alligator.md)* || <sup>AG</sup> || [École de la tortue alligator](./École de la tortue alligator.md), [Science de la lutte](./Science de la lutte.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +3 ou [moine](./Moine.md) de niveau 3 || Le bonus de bouclier s'applique au DMD et à la CA au contact
|- CLASS="donprérequis1"
| &emsp;&emsp;[Carapace de la tortue alligator](./Carapace de la tortue alligator.md)* || <sup>AG</sup> || [Étreinte de la tortue alligator](./Étreinte de la tortue alligator.md), [École de la tortue alligator](./École de la tortue alligator.md), [Science de la lutte](./Science de la lutte.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +5 ou [moine](./Moine.md) de niveau 5 || Le bonus de CA augmente de 2 et les adversaires ont un malus de -4 aux confirmations de coup critique

|- CLASS="premier donprincipal"
| [École du bouclier bouleversant](./École du bouclier bouleversant.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 13, maniement des [targes](./targe (armure).md) || Utilise une targe pour effectuer des coups de bouclier
|- CLASS="donprérequis0"
| &emsp;[Frappe du bouclier bouleversant](./Frappe du bouclier bouleversant.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 15, [Attaques réflexes](./Attaques réflexes.md), [École du bouclier bouleversant](./École du bouclier bouleversant.md), [Science du coup de bouclier](./Science du coup de bouclier.md), maniement des [targes](./targe (armure).md) || Les adversaires qui ratent le personnage provoquent une attaque d'opportunité
|- CLASS="donprérequis1"
| &emsp;&emsp;[Vengeance du bouclier bouleversant](./Vengeance du bouclier bouleversant.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 13, [Attaques réflexes](./Attaques réflexes.md), [École du bouclier bouleversant](./École du bouclier bouleversant.md), [Frappe du bouclier bouleversant](./Frappe du bouclier bouleversant.md), [Science du coup de bouclier](./Science du coup de bouclier.md), maniement des [targes](./targe (armure).md) || Utilise Frappe du bouclier bouleversant contre les adversaires qui attaquent les alliés

|- CLASS="premier donprincipal"
| [École du boxeur](./École du boxeur.md)* || <sup>MCA</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md); [BBA](./BBA.md) +6, capacité de classe [déluge de coups du lutteur](./Lutteur.md#DELUGEDECOUPSDULUTTEUR) ou [déluge de coups](./Moine.md#DELUGEDECOUPS) || Gain d'un bonus aux dégâts quand deux attaques à mains nues ou plus touchent le même adversaire lors du tour
|- CLASS="donprérequis0"
| &emsp;[Danse du boxeur](./Danse du boxeur.md)* || <sup>MCA</sup> || [Esquive](./Esquive.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [École du boxeur](./École du boxeur.md), [Souplesse du serpent](./Souplesse du serpent.md); [BBA](./BBA.md) +9, [lutteur](./Lutteur.md) de nvieau 5, ou [moine](./Moine.md) de niveau 5 || Le personnage se déplace de 1,50 mètre sans provoquer d'attaque d'opportunité chaque fois qu'il touche avec une attaque à mains nues
|- CLASS="donprérequis1"
| &emsp;&emsp;[Maître boxeur](./Maître boxeur.md)* || <sup>MCA</sup> || [Esquive](./Esquive.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [Danse du boxeur](./Danse du boxeur.md), [École du boxeur](./École du boxeur.md), [Souplesse du serpent](./Souplesse du serpent.md), [Attaque en puissance](./Attaque en puissance.md); [BBA](./BBA.md) +12, [lutteur](./Lutteur.md) de niveau 8, ou [moine](./Moine.md) de niveau 8 || Augmente les dégâts infligés avec École du boxeur

|- CLASS="premier donprincipal"
| [École du carquois vide](./École du carquois vide.md)* || <sup>*WMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Combat au corps à corps avec une arme à distance
|- CLASS="donprérequis0"
| &emsp;[Flexibilité du carquois vide](./Flexibilité du carquois vide.md)* || <sup>*WMH*</sup> || [École du carquois vide](./École du carquois vide.md), [Tir rapide](./Tir rapide.md), [Coup de flèche](./Coup de flèche.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Applique les dons de combat à distance sur les attaques au corps à corps
|- CLASS="donprérequis1"
| &emsp;&emsp;[Frénésie du carquois vide](./Frénésie du carquois vide.md)* || <sup>*WMH*</sup> || [Flexibilité du carquois vide](./Flexibilité du carquois vide.md), [École du carquois vide](./École du carquois vide.md), [Tir rapide](./Tir rapide.md), [Coup de flèche](./Coup de flèche.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Utilise les armes à distance pour porter des attaques au corps à corps et évite les attaques d'opportunité

|- CLASS="premier donprincipal"
| [École du cogneur](./École du cogneur.md)* || <sup>MCA</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md); [BBA](./BBA.md) +6, capacité de classe [déluge de coups du lutteur](./Lutteur.md#DELUGEDECOUPSDULUTTEUR) ou [déluge de coups](./Moine.md#DELUGEDECOUPS) || Le personnage combines ensemble ses attaques à mains nues
|- CLASS="donprérequis0"
| &emsp;[Charge du cogneur](./Charge du cogneur.md)* || <sup>MCA</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du cogneur](./École du cogneur.md); [BBA](./BBA.md) +12, [lutteur](./Lutteur.md) de niveau 8, ou [moine](./Moine.md) de niveau 8 || Le personnage peut cogner après une charge
|- CLASS="donprérequis0"
| &emsp;[Cogneur tyrannique](./Cogneur tyrannique.md)* || <sup>MCA</sup> || [Science du repositionnement](./Science du repositionnement.md), [Science du croc-en-jambe](./Science du croc-en-jambe.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [École du cogneur](./École du cogneur.md); [BBA](./BBA.md) +9, [lutteur](./Lutteur.md) de niveau 5, ou [moine](./Moine.md) de niveau 5 || Quand il utilise École du cogneur, le personnage peut tenter une manœuvre offensive de croc-en-jambe ou de repositionnement par une action libre

|- CLASS="premier donprincipal"
| [École du djinn](./École du djinn.md)* || <sup>AG</sup> || [Con](./Con.md) 13, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +9 ou [moine](./Moine.md) de niveau 5 || 1 utilisation quotidienne de Poing élémentaire de plus et bonus aux dégâts électriques
|- CLASS="donprérequis0"
| &emsp;[Esprit du djinn](./Esprit du djinn.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 15, [École du djinn](./École du djinn.md), [poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +11 ou [moine](./Moine.md) de niveau 9 || 1 utilisation quotidienne de Poing élémentaire de plus et résistance aux dégâts électriques
|- CLASS="donprérequis1"
| &emsp;&emsp;[Tourbillon du djinn](./Tourbillon du djinn.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 17, [École du djinn](./École du djinn.md), [Esprit du djinn](./Esprit du djinn.md), [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +13 ou [moine](./Moine.md) de niveau 11 || Le Poing élémentaire permet au personnage de s'entourer d'un halo d'électricité

|- CLASS="premier donprincipal"
| [École du dragon](./École du dragon.md)* || <sup>AG</sup> || [For](./For.md) 15, [Science du combat à mains nues](./Science du combat à mains nues.md), 3 rangs en [Acrobaties](./Acrobaties.md) || Bonus de +2 contre le sommeil, la paralysie et l'étourdissement. Peut ignorer le terrain difficile
|- CLASS="donprérequis0"
| &emsp;[Férocité du dragon](./Férocité du dragon.md)* || <sup>AG</sup> || [For](./For.md) 15, [Science du combat à mains nues](./Science du combat à mains nues.md), [École du dragon](./École du dragon.md), [Coup étourdissant](./Coup étourdissant.md), 5 rangs en [Acrobaties](./Acrobaties.md) || Bonus aux attaques à mains nues et adversaires secoués
|- CLASS="donprérequis0"
| &emsp;[Rugissement du dragon](./Rugissement du dragon.md)* || <sup>AG</sup> || [For](./For.md) 15, [Science du combat à mains nues](./Science du combat à mains nues.md), [École du dragon](./École du dragon.md), [Coup étourdissant](./Coup étourdissant.md), 8 rangs en [Acrobaties](./Acrobaties.md) || 1 utilisation quotidienne de Poing étourdissant de plus et rugissement dévastateur

|- CLASS="premier donprincipal"
| [École du fer rapide](./École du fer rapide.md)* || <sup>*AMH*</sup> || [For](./For.md) 13, [Dex](./Dex.md) 13, formation au port des armures intermédiaires || Améliore la manœuvrabilité en armure
|- CLASS="donprérequis0"
| &emsp;[Refuge du fer rapide](./Refuge du fer rapide.md)* || <sup>*AMH*</sup> || [For](./For.md) 13, [Dex](./Dex.md) 13, [École du fer rapide](./École du fer rapide.md), formation au port des armures intermédiaires || Réduit les dégâts des dés supplémentaires au minimum
|- CLASS="donprérequis1"
| &emsp;&emsp;[Sprint du fer rapide](./Sprint du fer rapide.md)* || <sup>*AMH*</sup> || [For](./For.md) 13, [Dex](./Dex.md) 13, [École du fer rapide](./École du fer rapide.md), [Refuge du fer rapide](./Refuge du fer rapide.md), formation au port des armures intermédiaires || Ignore la réduction de vitesse de l'armure

|- CLASS="premier donprincipal"
| [École du fonceur](./École du fonceur.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13; [Expertise du combat](./Expertise du combat.md) ou capacité de classe [ruse du lutteur](./Lutteur.md#RUSEDULUTTEUR); [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || +1 à la CA et aux dégâts avec une arme après un pas de placement
|- CLASS="donprérequis0"
| &emsp;[Louvoyage du fonceur](./Louvoyage du fonceur.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Fente](./Fente.md), [École du fonceur](./École du fonceur.md); [Expertise du combat](./Expertise du combat.md) ou capacité de classe [ruse du lutteur](./Lutteur.md#RUSEDULUTTEUR); [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Pas de malus à la CA en utilisant Fente avec École du fonceur, le bonus à la CA et aux dégâts d'École du fonceur passe à +2
|- CLASS="donprérequis1"
| &emsp;&emsp;[Sprint du fonceur](./Sprint du fonceur.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Fente](./Fente.md), [Louvoyage du fonceur](./Louvoyage du fonceur.md), [École du fonceur](./École du fonceur.md); [Expertise du combat](./Expertise du combat.md) ou capacité de classe [ruse du lutteur](./Lutteur.md#RUSEDULUTTEUR); [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Déplacement de 1.5 m supplémentaire lors d'un pas de placement avec École du fonceur

|- CLASS="premier donprincipal"
| [École du fracasseur](./École du fracasseur.md)* || <sup>*WMH*</sup> || [For](./For.md) 13, [Science de la destruction](./Science de la destruction.md), [Attaque en puissance](./Attaque en puissance.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Tentative de bousculade ou de croc-en-jambe gratuite après une manœuvre de destruction contre une armure
|- CLASS="donprérequis0"
| &emsp;[Écrasement du fracasseur](./Écrasement du fracasseur.md)* || <sup>*WMH*</sup> || [For](./For.md) 13, [Science de la destruction](./Science de la destruction.md), [École du fracasseur](./École du fracasseur.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Réduit la solidité des objets que le personnage tente de détruire
|- CLASS="donprérequis0"
| &emsp;[Martelage du fracasseur](./Martelage du fracasseur.md)* || <sup>*WMH*</sup> || [For](./For.md) 13, [Science de la destruction](./Science de la destruction.md), [École du fracasseur](./École du fracasseur.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie, [BBA](./BBA.md) +6 || Réduit le bonus d'armure et augment le malus d'armure des armures que le personnage tente de détruire

|- CLASS="premier donprincipal"
| [École du frondeur-disperseur](./École du frondeur-disperseur.md)* || <sup>*WMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) (fronde) ou capacité de classe [entraînement aux armes](./Guerrier.md#ENTRAINEMENTAUXARMES) (armes de jet), trait racial [guerrier à la fronde](./Halfelin.md#Traits_raciaux_alternatifs_7) || +1 aux dégâts avec les frondes, ne provoque pas d'attaque d'opportunité en les rechargeant
|- CLASS="donprérequis0"
| &emsp;[Grenadier frondeur-disperseur](./Grenadier frondeur-disperseur.md)* || <sup>*WMH*</sup> || [École du frondeur-disperseur](./École du frondeur-disperseur.md), [Lancer improvisé](./Lancer improvisé.md), [Arme de prédilection](./Arme de prédilection.md) (fronde) ou capacité de classe [entraînement aux armes](./Guerrier.md#ENTRAINEMENTAUXARMES) (armes de jet), trait racial [guerrier à la fronde](./Halfelin.md#Traits_raciaux_alternatifs_7) || Utilise la fronde pour lancer des armes alchimiques à aspersion
|- CLASS="donprérequis1"
| &emsp;&emsp;[Bombardement du frondeur-disperseur](./Bombardement du frondeur-disperseur.md)* || <sup>*WMH*</sup> || [Arme en main](./Arme en main.md), [Grenadier frondeur-disperseur](./Grenadier frondeur-disperseur.md), [École du frondeur-disperseur](./École du frondeur-disperseur.md), [Lancer improvisé](./Lancer improvisé.md), [Arme de prédilection](./Arme de prédilection.md) (fronde) ou capacité de classe [entraînement aux armes](./Guerrier.md#ENTRAINEMENTAUXARMES) (armes de jet), trait racial [guerrier à la fronde](./Halfelin.md#Traits_raciaux_alternatifs_7) || Utilise la fronde pour lancer plusieurs armes alchimiques

|- CLASS="premier donprincipal"
| [École du gantelet-bouclier](./École du gantelet-bouclier.md)* || <sup>*AMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) ([gantelet](./Gantelet (arme).md) ou [gantelet clouté](./Gantelet clouté (arme).md)), formation au port des [rondaches](./rondache (armure).md) et des [targes](./targe (armure).md) || Considère le gantelet de la main non-directrice comme une targe
|- CLASS="donprérequis0"
| &emsp;[Attaque du gantelet-bouclier](./Attaque du gantelet-bouclier.md)* || <sup>*AMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) ([gantelet](./Gantelet (arme).md) ou [gantelet clouté](./Gantelet clouté (arme).md)), [École du gantelet-bouclier](./École du gantelet-bouclier.md), formation au port des [targes](./targe (armure).md) et des [rondaches](./rondache (armure).md) || Conserve le bonus de bouclier du gantelet même après avoir attaqué avec
|- CLASS="donprérequis1"
| &emsp;&emsp;[Maître du gantelet-bouclier](./Maître du gantelet-bouclier.md)* || <sup>*AMH*</sup> || [Arme de prédilection](./Arme de prédilection.md) ([gantelet](./Gantelet (arme).md) ou [gantelet clouté](./Gantelet clouté (arme).md)), [Attaque du gantelet-bouclier](./Attaque du gantelet-bouclier.md), [École du gantelet-bouclier](./École du gantelet-bouclier.md), formation au port des [targes](./targe (armure).md) et des [rondaches](./rondache (armure).md) || Augmente les dégâts du gantelet et l'utilise pour désarmer ou subtiliser pendant une attaque d'opportunité

|- CLASS="premier donprincipal"
| [École du gnome illusoire](./École du gnome illusoire.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Expertise du combat](./Expertise du combat.md), [Arme de prédilection gnome](./Arme de prédilection gnome.md), [Science de la feinte](./Science de la feinte.md), [BBA](./BBA.md) +1, Traits raciaux [armes familières](./Gnome.md#Traits_raciaux_standards_6) et [magie gnome](./Gnome.md#Traits_raciaux_standards_6) || Sacrifie des sorts pour obtenir un bonus aux tests feinte
|- CLASS="donprérequis0"
| &emsp;[Surprise du gnome illusoire](./Surprise du gnome illusoire.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Expertise du combat](./Expertise du combat.md), [Arme de prédilection gnome](./Arme de prédilection gnome.md), [École du gnome illusoire](./École du gnome illusoire.md), [Science de la feinte](./Science de la feinte.md) || +2 aux tests de sale coup et de Bluff pour feinter, nouveaux avantages avec École du gnome illusoire
|- CLASS="donprérequis1"
| &emsp;&emsp;[Confusion du gnome illusoire](./Confusion du gnome illusoire.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Expertise du combat](./Expertise du combat.md), [Arme de prédilection gnome](./Arme de prédilection gnome.md), [Surprise du gnome illusoire](./Surprise du gnome illusoire.md), [École du gnome illusoire](./École du gnome illusoire.md), [Science de la feinte](./Science de la feinte.md), Traits raciaux [armes familières](./Gnome.md#Traits_raciaux_standards_6) et [magie gnome](./Gnome.md#Traits_raciaux_standards_6) || Avantages spéciaux lors d'une feinte

|- CLASS="premier donprincipal"
| [École du guerrier elfique](./École du guerrier elfique.md)* || <sup>*WMH*</sup> || [Entraînement guerrier elfique](./Entraînement guerrier elfique.md), [BBA](./BBA.md) +1, trait racial [armes familières](./Elfe.md#Traits_raciaux_standards_6) || Ne provoque pas d'attaque d'opportunité lors de manœuvres offensives portées avec des armes elfiques
|- CLASS="donprérequis0"
| &emsp;[Concentration du guerrier elfique](./Concentration du guerrier elfique.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Entraînement guerrier elfique](./Entraînement guerrier elfique.md), [École du guerrier elfique](./École du guerrier elfique.md), [Attaque en finesse](./Attaque en finesse.md), [BBA](./BBA.md) +4, trait racial [armes familières](./Elfe.md#Traits_raciaux_standards_6) || Quand il utilise École du guerrier elfique, le personnage ajoute le modificateur d'Intelligence aux dégâts des armes
|- CLASS="donprérequis1"
| &emsp;&emsp;[Torrent du guerrier elfique](./Torrent du guerrier elfique.md)* || <sup>*WMH*</sup> || [Int](./Int.md) 13, [Entraînement guerrier elfique](./Entraînement guerrier elfique.md), [Concentration du guerrier elfique](./Concentration du guerrier elfique.md), [École du guerrier elfique](./École du guerrier elfique.md), [Attaque en finesse](./Attaque en finesse.md), [BBA](./BBA.md) +10, trait racial d'[armes familières](./Elfe.md#Traits_raciaux_standards_6) || Les adversaires provoquent des attaques d'opportunité quand le personnage se bat sur la défensive

|- CLASS="premier donprincipal"
| [École du hibou](./École du hibou.md)* || <sup>*UI*</sup> || [Dex](./Dex.md) 13, [Talent](./Talent.md) (Discrétion), 1 rang en [Discrétion](./Discrétion.md) || Base la Discrétion sur l'entraînement martial et charge avec Discrétion
|- CLASS="donprérequis0"
| &emsp;[Piqué du hibou](./Piqué du hibou.md)* || <sup>*UI*</sup> || [Dex](./Dex.md) 15, [École du hibou](./École du hibou.md), [Talent](./Talent.md) (Discrétion), 1 rang en [Acrobaties](./Acrobaties.md), 1 rang en [Discrétion](./Discrétion.md) || Base Acrobaties sur l'entraînement martial et charge avec Acrobaties
|- CLASS="donprérequis1"
| &emsp;&emsp;[Plongeon du hibou](./Plongeon du hibou.md)* || <sup>*UI*</sup> || [Dex](./Dex.md) 17, [École du hibou](./École du hibou.md), [Piqué du hibou](./Piqué du hibou.md), [Talent](./Talent.md) (Discrétion), [BBA](./BBA.md) +7 ou [moine](./Moine.md) de niveau 5, 1 rang en [Acrobaties](./Acrobaties.md), 1 rang en [Discrétion](./Discrétion.md), 1 rang en [Vol](./Vol.md) || Base le Vol sur l'entraînement martial et charge à travers une créature

|- CLASS="premier donprincipal"
| [École du jann](./École du jann.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), 3 rangs en [Acrobaties](./Acrobaties.md), 3 rangs en [Représentation](./Représentation.md) (danse) || -1 à la CA du personnage lorsqu'il charge et bonus de +1 seulement aux jets d'attaque des adversaires quand ils le prennent en tenaille
|- CLASS="donprérequis0"
| &emsp;[Tempête du jann](./Tempête du jann.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du jann](./École du jann.md), 5 rangs en [Acrobaties](./Acrobaties.md), 5 rangs en [Représentation](./Représentation.md) (danse) || Après une attaque à mains nues réussie, le personnage gagne +4 aux tests de bousculade ou de croc-en-jambe
|- CLASS="donprérequis1"
| &emsp;&emsp;[Ruée du jann](./Ruée du jann.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du jann](./École du jann.md), [Tempête du jann](./Tempête du jann.md), 8 rangs en [Acrobaties](./Acrobaties.md), 8 rangs en [Représentation](./Représentation.md) (danse) || Quand le personnage saute, on considère toujours qu'il a fait une course d'élan, dégâts doublés s'il saute lors d'une charge

|- CLASS="premier donprincipal"
| [École du kirin](./École du kirin.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), 6 rangs en [Connaissances](./Connaissances.md) (Mystères), 1 rang en [Connaissances](./Connaissances.md) (exploration souterraine, folklore local, nature, plans, ou religion) || Le personnage peut faire des tests de Connaissances par une action rapide pour gagner un bonus contre un adversaire
|- CLASS="donprérequis0"
| &emsp;[Frappe du kirin](./Frappe du kirin.md)* || <sup>AG</sup> || [Int](./Int.md) 13, [École du kirin](./École du kirin.md), [Science du combat à mains nues](./Science du combat à mains nues.md), 9 rangs en [Connaissances](./Connaissances.md) (Mystères), 3 rangs en [Connaissances](./Connaissances.md) (exploration souterraine, folklore local, nature, plans, ou religion) || Bonus d'intuition de +2 pour identifier une créature
|- CLASS="donprérequis1"
| &emsp;&emsp;[Voie du kirin](./Voie du kirin.md)* || <sup>AG</sup> || [Int](./Int.md) 13, [Frappe du kirin](./Frappe du kirin.md), [École du kirin](./École du kirin.md), [Science du combat à mains nues](./Science du combat à mains nues.md), 12 rangs en [Connaissances](./Connaissances.md) (Mystères), 5 rangs en [Connaissances](./Connaissances.md) (exploration souterraine, folklore local, nature, plans, ou religion) || Le personnage peut faire 10 à un test de Connaissances (folklore local, nature, plans ou religion) pour identifier

|- CLASS="premier donprincipal"
| [École du kitsune](./École du kitsune.md)* || <sup>*DTT*</sup> || [Int](./Int.md) 13, [Expertise du combat](./Expertise du combat.md), [Science du sale coup](./Science du sale coup.md) || Effectue un sale coup après une charge
|- CLASS="donprérequis0"
| &emsp;[Tours du kitsune](./Tours du kitsune.md)* || <sup>*DTT*</sup> || [Int](./Int.md) 13; [Expertise du combat](./Expertise du combat.md); [Science du sale coup](./Science du sale coup.md), [École du kitsune](./École du kitsune.md); [BBA](./BBA.md) +3 ou [moine](./Moine.md) de niveau 3 || Applique deux états préjudiciables en utilisant l'école du kitsune
|- CLASS="donprérequis1"
| &emsp;&emsp;[Vengeance du kitsune](./Vengeance du kitsune.md)* || <sup>*DTT*</sup> || [Int](./Int.md) 13; [Expertise du combat](./Expertise du combat.md); [Science du sale coup](./Science du sale coup.md); [École du kitsune](./École du kitsune.md); [Tours du kitsune](./Tours du kitsune.md); [BBA](./BBA.md) +6 ou [moine](./Moine.md) de niveau 6 || Effecue un sale coup à la place d'une attaque d'opportunité

|- CLASS="premier donprincipal"
| [École du lancer d'étoile](./École du lancer détoile.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 13, [Tir à bout portant](./Tir à bout portant.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Gain de bonus aux dégâts avec un type d'armes de jet
|- CLASS="donprérequis0"
| &emsp;[Comète du lancer d'étoile](./Comète du lancer détoile.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 13, [Tir à bout portant](./Tir à bout portant.md), [École du lancer d'étoile](./École du lancer détoile.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Attaque supplémentaire avec une arme de jet par une action simple
|- CLASS="donprérequis1"
| &emsp;&emsp;[Pluie du lancer d'étoile](./Pluie du lancer détoile.md)* || <sup>*WMH*</sup> || [Dex](./Dex.md) 13, [Tir à bout portant](./Tir à bout portant.md), [BBA](./BBA.md) +4, [Comète du lancer d'étoile](./Comète du lancer détoile.md), [École du lancer d'étoile](./École du lancer détoile.md), [Arme de prédilection](./Arme de prédilection.md) avec l'arme choisie || Attaque d'autres adversaires proches de la cible initiale avec École du lancer d'étoile

|- CLASS="premier donprincipal"
| [École du marid](./École du marid.md)* || <sup>AG</sup> || [Con](./Con.md) 13, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +9 ou [moine](./Moine.md) de niveau 5 || 1 utilisation quotidienne du Poing élémentaire de plus et inflige des dégâts de froid
|- CLASS="donprérequis0"
| &emsp;[Esprit du marid](./Esprit du marid.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [École du marid](./École du marid.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +11 ou [moine](./Moine.md) de niveau 9 || 1 utilisation quotidienne du Poing élémentaire de plus et une résistance au froid
|- CLASS="donprérequis1"
| &emsp;&emsp;[Froid du marid](./Froid du marid.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 17, [Poing élémentaire](./Poing élémentaire.md), [Esprit du marid](./Esprit du marid.md), [École du marid](./École du marid.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +13 ou [moine](./Moine.md) de niveau 11 || Projette un jet d'eau glacée sur une ligne de 9 m

|- CLASS="premier donprincipal"
| [École du rempart mobile](./École du rempart mobile.md)* || <sup>*AMH*</sup> || [For](./For.md) 13, [Art du bouclier](./Art du bouclier.md), [Maniement du pavois](./Maniement du pavois.md), [BBA](./BBA.md) +1 || Ajoute le bonus de bouclier à la CA au DMD contre les manœuvres de bousculade et de renversement, utilise le pavois plus rapidement
|- CLASS="donprérequis0"
| &emsp;[Forteresse du rempart mobile](./Forteresse du rempart mobile.md)* || <sup>*AMH*</sup> || [For](./For.md) 15, [Art du bouclier](./Art du bouclier.md), [École du rempart mobile](./École du rempart mobile.md), [Maniement du pavois](./Maniement du pavois.md), [BBA](./BBA.md) +4 || Ajoute la moitié du bonus de bouclier à la CA au contact
|- CLASS="donprérequis1"
| &emsp;&emsp;[Bastion du rempart mobile](./Bastion du rempart mobile.md)* || <sup>*AMH*</sup> || [For](./For.md) 17, [Art du bouclier](./Art du bouclier.md), [École du rempart mobile](./École du rempart mobile.md), [Forteresse du rempart mobile](./Forteresse du rempart mobile.md), [Maniement du pavois](./Maniement du pavois.md), [BBA](./BBA.md) +7 || Applique un abri partiel contre les sorts et un abri total contre une attaque par une action immédiate

|- CLASS="premier donprincipal"
| [École du renard](./École du renard.md)* || <sup>*UI*</sup> || [Int](./Int.md) 13 || Feinte et distrait les adversaires grâce à un entraînement martial
|- CLASS="donprérequis0"
| &emsp;[Intuition du renard](./Intuition du renard.md)* || <sup>*UI*</sup> || [Int](./Int.md) 13, [École du renard](./École du renard.md) || Le personnage est plus difficile à feinter et à démoraliser
|- CLASS="donprérequis1"
| &emsp;&emsp;[Tromperie du renard](./Tromperie du renard.md)* || <sup>*UI*</sup> || [Int](./Int.md) 13, [École du renard](./École du renard.md), [Expertise du combat](./Expertise du combat.md), [Intuition du renard](./Intuition du renard.md), [Science du sale coup](./Science du sale coup.md) || Fait des manœuvres de sale coup comme attaque d'opportunité

|- CLASS="premier donprincipal"
| [École du sanglier](./École du sanglier.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), 3 rangs en [Intimidation](./Intimidation.md) || Les attaques à mains nues infligent des dégâts contondants ou perforants
|- CLASS="donprérequis0"
| &emsp;[Férocité du sanglier](./Férocité du sanglier.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du sanglier](./École du sanglier.md), 6 rangs en [Intimidation](./Intimidation.md) || Ajoute des dégâts perforants aux attaques à mains nues et démoralise les adversaires
|- CLASS="donprérequis1"
| &emsp;&emsp;[Déchiquetage du sanglier](./Déchiquetage du sanglier.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [Férocité du sanglier](./Férocité du sanglier.md), [École du sanglier](./École du sanglier.md), 9 rangs en [Intimidation](./Intimidation.md) || Les attaques à mains nues provoquent un saignement

|- CLASS="premier donprincipal"
| [École du serpent](./École du serpent.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), 1 rang en [Acrobaties](./Acrobaties.md), 3 rangs en [Psychologie](./Psychologie.md) || +2 aux tests de Psychologie, dégâts perforants avec les attaques à mains nues
|- CLASS="donprérequis0"
| &emsp;[Balancement du serpent](./Balancement du serpent.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du serpent](./École du serpent.md), 3 rangs en [Acrobaties](./Acrobaties.md), 6 rangs en [Psychologie](./Psychologie.md) || Bonus pour ne pas tomber à terre, test de psychologie pour confirmer un coup critique
|- CLASS="donprérequis1"
| &emsp;&emsp;[Croc du serpent](./Croc du serpent.md)* || <sup>AG</sup> || [Attaques réflexes](./Attaques réflexes.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [Balancement du serpent](./Balancement du serpent.md), [École du serpent](./École du serpent.md), 6 rangs en [Acrobaties](./Acrobaties.md), 9 rangs en [Psychologie](./Psychologie.md) || Si l'adversaire rate le personnage, ce dernier a droit à une attaque d'opportunité par une action immédiate

|- CLASS="premier donprincipal"
| [École du shaitan](./École du shaitan.md)* || <sup>AG</sup> || [Con](./Con.md) 13, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +9 ou [moine](./Moine.md) de niveau 5 || 1 utilisation quotidienne du Poing élémentaire de plus et inflige des dégâts d'acide
|- CLASS="donprérequis0"
| &emsp;[Peau du shaitan](./Peau du shaitan.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 15, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [École du shaitan](./École du shaitan.md), [BBA](./BBA.md) +11 ou [moine](./Moine.md) de niveau 9 || 1 utilisation quotidienne du Poing élémentaire de plus et une résistance à l'acide
|- CLASS="donprérequis1"
| &emsp;&emsp;[Séisme du shaitan](./Séisme du shaitan.md)* || <sup>AG</sup> || [Con](./Con.md) 15, [Sag](./Sag.md) 17, [Poing élémentaire](./Poing élémentaire.md), [Science du combat à mains nues](./Science du combat à mains nues.md), [Peau du shaitan](./Peau du shaitan.md), [École du shaitan](./École du shaitan.md), [BBA](./BBA.md) +13 ou [moine](./Moine.md) de niveau 11 || Fait jaillir une colonne d'acide de 6 m

|- CLASS="premier donprincipal"
| [École du singe](./École du singe.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [Science du combat à mains nues](./Science du combat à mains nues.md), 5 rangs en [Acrobaties](./Acrobaties.md), 5 rangs en [Escalade](./Escalade.md) || Le personnage ajoute son bonus de Sagesse aux tests d'Acrobatie et n'a pas de malus quand il attaque couché
|- CLASS="donprérequis0"
| &emsp;[Mouvements du singe](./Mouvements du singe.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [Science du combat à mains nues](./Science du combat à mains nues.md), [École du singe](./École du singe.md), 8 rangs en [Acrobaties](./Acrobaties.md), 8 rangs en [Escalade](./Escalade.md) || Le personnage ajoute son bonus de Sagesse aux tests d'Escalade. Il grimpe et rampe à la moitié de sa vitesse
|- CLASS="donprérequis1"
| &emsp;&emsp;[Éclat du singe](./Éclat du singe.md)* || <sup>AG</sup> || [Sag](./Sag.md) 13, [Science du combat à mains nues](./Science du combat à mains nues.md), [Mouvements du singe](./Mouvements du singe.md), [École du singe](./École du singe.md), [Coup étourdissant](./Coup étourdissant.md), 11 rangs en [Acrobaties](./Acrobaties.md), 11 rangs en [Escalade](./Escalade.md) || Le personnage peut entrer dans une case adjacente après un Coup étourdissant

|- CLASS="premier donprincipal"
| [École du talon-à-ressorts](./École du talon-à-ressorts.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 13, [Esquive](./Esquive.md), [Souplesse du serpent](./Souplesse du serpent.md), [Tir en mouvement](./Tir en mouvement.md) ou [Attaque éclair](./Attaque éclair.md), [BBA](./BBA.md) +4, formation au port des armures légères || Gain d'un bonus à l'attaque après un déplacement
|- CLASS="donprérequis0"
| &emsp;[Sprint du talon-à-ressorts](./Sprint du talon-à-ressorts.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 15, [École du talon-à-ressorts](./École du talon-à-ressorts.md), [Esquive](./Esquive.md), [Souplesse du serpent](./Souplesse du serpent.md), [Tir en mouvement](./Tir en mouvement.md) ou [Attaque éclair](./Attaque éclair.md), [BBA](./BBA.md) +7, formation au port des armures légères || Se déplace jusqu'au double de la vitesse pendant un Tir en mouvement ou une Attaque éclair
|- CLASS="donprérequis1"
| &emsp;&emsp;[Fauchage du talon-à-ressorts](./Fauchage du talon-à-ressorts.md)* || <sup>*AMH*</sup> || [Dex](./Dex.md) 17, [École du talon-à-ressorts](./École du talon-à-ressorts.md), [Esquive](./Esquive.md), [Souplesse du serpent](./Souplesse du serpent.md), [Tir en mouvement](./Tir en mouvement.md) ou [Attaque éclair](./Attaque éclair.md), [Sprint du talon-à-ressorts](./Sprint du talon-à-ressorts.md), [BBA](./BBA.md) +11, formation au port des armures légères || Attaque deux créatures pendant un Tir en mouvement ou une Attaque éclair

|- CLASS="premier donprincipal"
| [École du tigre](./École du tigre.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [BBA](./BBA.md) +3 ou [moine](./Moine.md) de niveau 3 || +2 au DMD contre la bousculade, le renversement et le croc-en-jambe. Inflige des dégâts tranchants
|- CLASS="donprérequis0"
| &emsp;[Griffes du tigre](./Griffes du tigre.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [École du tigre](./École du tigre.md), [BBA](./BBA.md) +6 ou [moine](./Moine.md) de niveau 5 || Le personnage porte une seule attaque avec les deux mains et additionne le résultat des deux
|- CLASS="donprérequis1"
| &emsp;&emsp;[Bond du tigre](./Bond du tigre.md)* || <sup>AG</sup> || [Science du combat à mains nues](./Science du combat à mains nues.md), [Attaque en puissance](./Attaque en puissance.md), [Griffes du tigre](./Griffes du tigre.md), [École du tigre](./École du tigre.md), [BBA](./BBA.md) +9 ou [moine](./Moine.md) de niveau 8 || Peut appliquer le malus de l'Attaque en puissance à la CA

|- CLASS="premier donprincipal"
| [École haineuse naine](./École haineuse naine.md)* || <sup>*WMH*</sup> || [BBA](./BBA.md) +1, traits raciaux [entraînement défensif](./Nain.md#Traits_raciaux_standards_6) et [haine](./Nain.md#Traits_raciaux_standards_6), taille M || Applique la haine aux jets d'attaque et de dégâts, et son bonus passe à +2
|- CLASS="donprérequis0"
| &emsp;[Irritation naine](./Irritation naine.md)* || <sup>*WMH*</sup> || [École haineuse naine](./École haineuse naine.md), [BBA](./BBA.md) +5, Traits raciaux [entraînement défensif](./Nain.md#Traits_raciaux_standards_6) et [haine](./Nain.md#Traits_raciaux_standards_6), taille M || Applique la haine et l'entraînement défensif à des types/sous-types différents
|- CLASS="donprérequis1"
| &emsp;&emsp;[Fureur naine](./Fureur naine.md)* || <sup>*WMH*</sup> || [École haineuse naine](./École haineuse naine.md), [Irritation naine](./Irritation naine.md), [BBA](./BBA.md) +7, traits raciaux [entraînement défensif](./Nain.md#Traits_raciaux_standards_6) et [haine](./Nain.md#Traits_raciaux_standards_6), taille M || Utilise Irritation naine contre n'importe quel nombre d'adversaires
|}
</center>
