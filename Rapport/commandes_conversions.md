- En fonction de votre système d'exploitation, installez **Pandoc** à partir du lien ci-dessous :

**<http://pandoc.org/installing.html>**

- Ensuite, tapez la ligne de commande suivante pour convertir les fichiers ".md" (markdown) en autre format :

**latex** : *pandoc rapportFinal.md -f markdown -t latex -s -o rapportFinal.html*
**pdf** : *pandoc rapportFinal.md -o rapportFinal.pdf*


-f = from
-t = to
-s = standalone : one entire file with header and footer.

***Il est à noter que nous avons en premier lieu créé un fichier rapport.md que nous avons converti en .tex grâce à Pandoc. Ensuite, nous avons retouché le .tex directement dans l'éditeur LaTex Texmaker afin d'avoir plus de souplesse dans la mise en page, et depuis Texmaker, nous avons converti en pdf le rapport finalisé.C'est ce dernier fichier, rapportFinal.pdf qui contient notre rapport finalisé.***

Le fichier rapportFinal.md est une version "light" de notre rapportFinal.tex ou rapportFinal.pdf mais peut-être convertie dans l'un ou l'autre des formats grâce aux commandes ci-dessus.


