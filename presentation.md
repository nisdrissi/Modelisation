<div class="reveal">

<div class="slides"><script type="text/x-mathjax-config">MathJax.Hub.Config({ TeX: { equationNumbers: { autoNumber: "none" }, extensions: ["AMSmath.js", "AMSsymbols.js", "autobold.js", "color.js"] } });</script>

<section>

## PROJET DE MODELISATION ET DE STRUCTURATION D’UN SI

<center>**Le vignoble de Suresnes**</center>

<center>**Clémentine CHASLES, Nisrine DRISSI, Zakaria AÏT-OMAR**</center>

<center>**Master 2 Technologies des Systèmes d’Information, 2015-2016**</center>

<center>

![](fig-talk/acc.png)

</center>

</section>

<section>

## Plan

<table border="0">

<tbody>

<tr>

<td class="padding">Quel système d’information est le plus adéquat à un vignoble de petite taille, qui n’utilise à ce jour, pas l’informatique ?

*   PRESENTATION DU VIGNOBLE

*   BESOINS DU VIGNOBLE ET MODALITÉS DE TRAVAIL

*   SOLUTION MODELISÉE

</td>

</tr>

</tbody>

</table>

</section>

<section>

## PRESENTATION DU VIGNOBLE

<table border="0">

<tbody>

<tr>

<td class="padding">

*   Le plus grand d’Île-de-France (4500 pieds)

*   Seul vignoble ouvert à la vente

*   Géré par l’association « Le Clos du Pas Saint-Maurice »

*   Cépages : Chardonnay & Sauvignon

</td>

<td class="padding">

<div style="width: 95%; padding: 10px;">![](fig-talk/birmil.png)</div>

</td>

</tr>

</tbody>

</table>

</section>

<section>

## MODALITES DE TRAVAIL

<table border="0">

<tbody>

<tr>

<td class="padding">

Méthode SCRUM

*   3 Sprints sur 10 jours

Logiciels utilisés

*   ArgoUML

*   StarUML

Utilisation du GitHub

*   https://github.com/nisdrissi/Modelisation

</td>

<td class="padding">

<div style="width: 335%; padding: 100px;">![](fig-talk/tableau.png)</div>

</td>

</tr>

</tbody>

</table>

</section>

<section>

## L’EXISTANT

Diagramme de cas d'utilisations de l'existant

<center>

![](fig-talk/usercaseold.png)

</center>

<aside class="notes"></aside>

</section>

<section>

## L’EXISTANT

<table border="0">

<tbody>

<tr>

<td class="padding">*   Pas de Système d’Information*   Travail sur des tableaux Excel et papier*   Peu nombreux (1 vigneron)*   Pas de site internet*   Ventes uniquement à la cave ou Office du Tourisme  
</td>

</tr>

</tbody>

</table>

</section>

<section>

## L’EXISTANT

Diagramme d'activité de l'existant

<center>

![](fig-talk/activityold.png)

</center>

<aside class="notes"></aside>

</section>

<section>

## SOLUTION PROPOSEE

<table border="0">

<tbody>

<tr>

<td class="padding">

Choix de solution = application web

*   Gestion du vignoble

*   Gestion du stock

*   Gestion des commandes

*   Gestion des profils

*   Cartographie interactive, position des pieds de vigne

Architecture 4-tiers J2EE

</td>

</tr>

</tbody>

</table>

</section>

<section>

## SOLUTION PROPOSEE

Diagramme de cas d'utilisations

<center>

![](fig-talk/usernew.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Zoom sur les cas d'utilisations

<center>

![](fig-talk/zoomcase.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Diagramme de la base de données

<center>

![](fig-talk/base.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Diagramme de classes

<center>

![](fig-talk/classe.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Le diagramme de séquence représente le scenario de l’acteur Vigneron pour la gestion des données du vignoble lors de l’étape de Fermentation puis du Soutirage.

<center>

![](fig-talk/seq.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Maquette de la page d’accueil de l’application web

<center>

![](fig-talk/vigne.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Diagrame de navigation de l'acteur vigneron

<center>

![](fig-talk/arbovigneron.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE

Diagrame D'architecture

<center>

![](fig-talk/architecture.png)

</center>

</section>

<section>

## SOLUTION PROPOSEE : limites

<table border="0">

<tbody>

<tr>

<td class="padding">

Passage à l’informatique ==> la conduite du changement  

Multiplicité des rôles ==> « double-casquette » du vigneron et de l’administrateur  

Solution entièrement exploitable quand :

*   toute la donnée sera numérisée

*   récupération du positionnement de chaque pied de vigne + métadonnées

</td>

</tr>

</tbody>

</table>

</section>

<section>

## SOLUTION PROPOSEE : perspectives

*   Utilisation de drones pour le suivi de la vigne : exploitation des images et calculs d’indicateurs

*   Faire de l’application web un outil de communication important : publicité, ventes, promotions

</section>

<section>

## CONCLUSION

*   Meilleure gestion et connaissance du vignoble

*   Nouvel outil pratique et interactif pour l’association

*   Outil de communication important pour la commune de Suresnes

<span class="fragment highlight-red">Questions?</span>

</section>

<section>

## MERCI DE VOTRE ATTENTION

*   http://www.lirmm.fr/~ducour/M2R/2005/Memoires/Tuitete.pdf
*   https://www.youtube.com/watch?v=nlQnOWr9gpc
*   https://lipn.univ-paris13.fr/~gerard/docs/cours/uml-cours-support.pdf
*   http://www.vignevin.com
*   http://www.food-info.net/fr/products/wine/prod.htmL
*   http://www.observatoire-viti-france.com
*   http://www.lavilog.com

</section>

</div>

</div>
