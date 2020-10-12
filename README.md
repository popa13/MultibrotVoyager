# MultibrotVoyager

## SECTION PARAMÈTRES GÉNÉRAUX:

* Polynomial degree: permet de changer le degré de la formule (z^p+c) qui génère les ensembles. Ces avec ce paramètre
		    que tu peux changer l'allure des images. Il faut toujours insérer un nombre entier plus grand que
		    2. (2,3,4,5,6 par exemple)


## SECTION ACTIONS:

* M Generate: permet de générer l'image de gauche uniquement.
* J Generate: permet de générer l'ensemble de droite uniquement.
* Generate: permet de générer les deux images en même temps.
* Resize Axis: action à faire pour redimensionner correctement l'image (essentiel lorsque le degré de la formule est
	      changé.
* Quit: Quitter le programme.


## SECTION MULTIBROT et JULIA:

Paramètre Multibrot: 
	* minX: permet de fixer la valeur extrême gauche de l'image.
	* maxX: permet de fixer la valeur extrême droite de l'image.
	* minY: permet de fixer la valeur extrême bas de l'image.
	* maxY: permet de fixer la valeur extrême haut de l'image.
	* saveImg: permet de sauvegarder l'image afficher dans la section.


## ACTION SUPLÉMENTAIRE SUR LES IMAGES

Il est possible de générer les images de droite à partir de l'image de gauche en cliquant avec le bouton gauche de 
la souris à un endroit précis sur l'image de gauche. Pour ce faire, un clic de souris permet de changer les paramètres
de la section Julia (panneau de droit) et ensuite on appuie sur le bouton J Generate.

Il est aussi possible de générer dynamiquement les images de droite en garder appuyer le bouton droite et en bougeant
la souris sur l'image de gauche