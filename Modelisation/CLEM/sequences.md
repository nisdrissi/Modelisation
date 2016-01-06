Commander une bouteille de vin
=====================================

Je suis un internaute qui navigue sur l'application online.

Je visite la page "Production du vin" qui me renseigne sur le processus de 
vinification une fois les vendanges faites.

Je souhaite ensuite acheter du vin.
Acheter
Pour cela, je réalise plusieurs étapes :
- je lis le texte qui m'explique comment commander ma bouteille de vin
- je choisis mon mode d'achat :
  - sur place au vignoble
  - sur les sites revendeurs (Twil, Comptoir Des Vignes, La Ruche qui dit Oui)
- si je choisis le mode d'achat sur place, je sélectionne la bouteille souhaitée
parmi une liste de choix de bouteilles en stock.
- si je choisi le mode d'achat en livraison par des revendeurs, je reçois une 
liste des liens des sites à consulter.
- je m'authentifie sur le site pour finaliser ma commande en :
  1. me créant un nouveau compte avec un login et un mot de passe si c'est ma 
première visite ;
  2. en entrant mes login et mot de passe si je suis déjà inscrit.
- je reçois ensuite un mail de confirmation de réservation de ma bouteille : je
pourrais venir la chercher au vignoble et la payer à ce moment-là.

Gérer les données sur le vignoble
=====================================

Analyser les données sur le vignoble
=====================================

Gérer le stock
=====================================

Manipuler la cartographie du vignoble
=====================================

L'utlisateur arrivant sur le site internet est directement dirigé vers la page 
d'accueil qui affiche une carte du vignoble.
Cette carte est faite à partir de Leaflet et contient plusieurs couches:
- les coordonnées x et y des pieds de vignes
- les parcelles dont le vignoble est composé
- le vignoble.
Chaque couche correspond à une classe qui contient des attributs et des méthodes
qui lui sont propres.
Les outils classiques de manipulation de la carte sont disponibles à n'importe
quel utilisateur non identifié : nous parlons ici des fonctionnalités de zoom/
dézoom, navigation, et sélection. Ce sont des fonctionnalités intégrées à Leaflet.
Lorsqu'un objet est sélectionné par un utilisateur non identifié, il est 
simplement mis en évidence sur la carte. L'utilisateur doit s'identifier pour avoir
accès aux informations relatives à l'objet.
Lorsqu'un objet est selectionné par un utilisateur identifié, une fenêtre pop-up 
apparaît à l'écran affichant les informations de l'objet.
choix année ?

Le diagramme de séquence ci-dessous représente le cas d'utilisation
*visualiser les caractéristiques du pied*.
Un utilisateur non identifié vient consulter le site et sélectionne un pied de 
vigne sur la carte. Il se trouve confronté à l'impossibilité de consulter les 
informations du pied de vigne sélectionné puisqu'il ne s'est pas identifié.

S'authentifier
==============







