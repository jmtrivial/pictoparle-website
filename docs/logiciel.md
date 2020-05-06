# Logiciel

![L'interface de l'application sur une tablette](img/tablette.jpg){.float-right .medium}

L'application développée pour faire fonctionner la tablette dans Pictoparle est conçue pour fonctionner sur une tablette Android. Le code source est disponible [sur le github du projet](https://github.com/jmtrivial/pictoparle), il est écrit en java, et s'appuie au maximum sur des versions éprouvées de l'API. Si l'application pourrait a priori fonctionner sur de nombreuses tablettes, elle a pour l'instant été uniquement utilisée sur une tablette Lenovo 10 pouces équipée d'une version d'Android 8.1.

L'interface est pour l'instant rudimentaire, mais s'étoffe progressivement. Voici une description non exhausive de son fonctionnement.

* L'application utilise la caméra côté écran pour détecter la présence d'une [planche](planches.md) sur sa surface. S'il y a une planche, l'interaction est proposée par double tap. S'il n'y a pas de planche, la tablette permet de choisir la prochaine planche à utiliser. Dans la version actuelle, l'utilisateur doit choisir la planche dans une liste. Très prochainement, ce choix se fera automatiquement grâce à un [QR code](https://fr.wikipedia.org/wiki/Code_QR) unique dessiné au verso de chaque planche.
* Les paramètres de l'application permettront d'ajuster le fonctionnement de l'outil en fonction de l'utilisateur et du matériel utilisé: densité de la verbalisation des actions (changements de planches), taille de l'écran, ajustement du double tap, etc.
* Les pictogrammes sont décrits dans des fichiers indépendants, et les planches sont décrites par un fichier facilement modifiable, au format xml.

## Compléments

Dans un futur proche, un outil sera également proposé pour générer automatiquement les planches de pictogrammes prêts à l'impression pour le thermogonflage.
