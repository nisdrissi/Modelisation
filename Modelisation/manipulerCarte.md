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


