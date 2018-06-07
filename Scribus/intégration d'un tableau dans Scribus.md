Intégration d'un tableau dans Scribus
=====================================


Introduction
------------

Le logiciel Open Source Scribus est spécialisé dans la PAO (Pagination Assistée par Ordinateur).

On peut le comparer sans problème à QuarkXpress ou Adobe InDesign. Il est très puissant pour mettre en page tout type d'image ou de texte et d'en générer des fichiers imprimables ou des PDF de qualité. Des magazines et des livres professionnels sont réalisés avec Scribus.

Par contre, l'intégration d'un tableau avec une mise en page complexe est réellement problématique. Scribus ne possède pas de fonction évolué de gestion des tableaux.

L'idée est de s'appuyer sur la suite Libre Office pour combler ce manque. Nous allons vous montrer pas à pas les étapes à réaliser pour intégrer un tableau dans Scribus.


Pré-requis
----------

Une machine sous Windows ou Linux avec les logiciels suivant :

- La suite Libre Office : <https://fr.libreoffice.org/>

- Scribus : <https://www.scribus.net/>



Création du tableau sous Calc
-----------------------------

Tout d'abord, il faut réaliser son tableau sous Calc de Libre Office.

![Création du tableau sans mise en page](images/Tab_Scribus_001.png)

Vous pouvez ajuster toute la mise en page du tableau avec Calc.

![Gestion de la mise en page du tableau](images/Tab_Scribus_002.png)

Pour obtenir par exemple, le résultat suivant

![Tableau finalisé sous Calc](images/Tab_Scribus_003.png)

Maintenant que vous avez finalisé la mise en page de votre tableau sous Calc. Vous enregistrez bien votre fichier pour ne pas le perdre.
Puis vous sélectionnez et copiez l'ensemble des cellules qui vous intéressent.

![Sélection et copie des cellules](images/Tab_Scribus_004.png)

Ensuite vous ouvrez un nouveau document de Dessin (Libre Office Draw)

![ Ouverture d'un nouveau document Draw](images/Tab_Scribus_005.png)

Dans la page vide qui s'est ouverte sous Draw, allez dans le menu Edition &gt; Collage Spécial... pour importer le tableau que vous avez réalisé sous Calc.

![Import du tableau Calc dans Draw](images/Tab_Scribus_006.png)

Dans la fenêtre de Collage spécial choisir : Métafichier GDI

![Choix du type de collage spécial](images/Tab_Scribus_007.png)



Passage par Draw pour générer le fichier EPS
--------------------------------------------

Vous retrouvez maintenant le tableau que vous avez créé sous Calc directement dans Draw réalisé en éléments vectorisés.

![Résultat du collage spécial dans Draw](images/Tab_Scribus_008.png)

Maintenant nous allons adapter le document Draw au tableau pour qu'il puisse être facilement intégré dans Scribus.
Nous commençons par adapter la taille de la page du document Draw. Allez dans le menu Format &gt; Propriété de la page

![Paramétrage des propriétés de la page](images/Tab_Scribus_009.png)

Configurez ensuite les propriétés de la page pour qu'elles correspondent au format de tableau. Ajustez également les marges du document pour qu'elles soient fines tout en étant à l'extérieur du tableau.

![Choix du format et des marges](images/Tab_Scribus_010.png)

Ensuite, vous pouvez affiner l'ajustement en modifiant la taille du tableau.

![Modification de la taille du tableau](images/Tab_Scribus_011.png)

Gardez bien les proportions du tableau pour ne pas le déformer.

![Configuration de la largeur et de la hauteur du tableau](images/Tab_Scribus_012.png)

On termine par l'alignement centré en hauteur et en largeur du tableau dans le document.

![Configuration de l'alignement du tableau](images/Tab_Scribus_013.png)

Maintenant que l'ensemble est bien calé, pensez bien à sauvegarder votre document.
Nous allons maintenant exporter notre document pour pouvoir l'intégrer dans Scribus.

![Exportation du document](images/Tab_Scribus_014.png)

Dans la fenêtre d'exportation, il faut choisir le format EPS ce qui permet de garder des éléments vectoriels qui pourront être transformés sous Scribus sans perte de qualité.

![Choix du type d'export](images/Tab_Scribus_015.png)

Voici les paramètres à configurer pour l'export EPS

![Paramétrage de l'export](images/Tab_Scribus_016.png)



Intégration du Fichier EPS dans Scribus
---------------------------------------

Pour finir, ouvrez Scribus avec un document vide ou le document en cours de création de votre choix. Allez dans le menu Fichier &gt; Importer &gt; Importer un fichier vectoriel

![Importation du fichier dans Scribus](images/Tab_Scribus_017.png)

Cliquez à l'endroit où vous désirez intégrer le tableau. Celui-ci va apparaître dans votre document avec la même mise en page que sous Calc.

![Résultat du tableau sous Scribus](images/Tab_Scribus_018.png)

Comme c'est un format vectoriel, vous pouvez modifier sa taille sous Scribus sans perte de qualité. Vous pouvez également éclater l'ensemble de ses éléments avec la fonction dégrouper pour modifier tout ce que vous voulez.


source : 

- <https://www.opensolus.fr/news/tutoriel/tuto-integrer-tableau-dans-scribus/>

---

*[OpenSolus &reg;](https://opensolus.fr) - juin 2018 - v1.1*
