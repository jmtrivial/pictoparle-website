# Conception des planches

[=50% "Développé à 50%"]

## La fabrique de PictoParle

La conception des [planches](planches.md) se fait grâce à la [fabrique de PictoParle](https://jmtrivial.github.io/pictoparle-fabrique/web/index.html).
Après avoir choisi le modèle de [tablette](materiel.md), et fait le choix d'une mise en page, on associe à chaque emplacement une image et un texte :


<div class="center"><iframe width="710" height="400" src="https://www.youtube.com/embed/AvcH3Rek4Jo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

On exporte alors trois fichiers distincts:

- un fichier au format ``zip``, que l'on **chargera dans la tablette**, pour que celle-ci puisse prendre en charge la nouvelle planche.
- un fichier au format ``pdf``, prêt à l'impression puis thermogonflage, pour que les [pictogrammes](pictogrammes.md) soient **accessibles au toucher** à l'utilisateur.
- un fichier au format ``dxf`` ou ``pdf`` servant à la fabrication  du cadre rigide de la planche, qui **matérialise l'espace** entre les pictogrammes.

![boîtier 3D](img/boitier-3d-planche.png)

Chaque concepteur de planche sera libre d'intégrer ses propres représentations de pictogrammes. Nous partageons cependant à titre d'information la [démarche que nous explorons](http://cln.jmfavreau.info/pictogrammes-tactiles.html) pour cette conception.

## État du développement

Dans sa version actuelle, la fabrique de Pictoparle ne génère que le premier fichier. Les prochains viendront bientôt, puis on améliorera suivant les besoins l'application en prenant en charge plus de modèles de tablettes, ou encore en ajoutant la possibilité de concevoir soi-même de nouvelles mises en page.
