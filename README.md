# Detection du langage des signes (alphabet)


## Content
* _Tensorflow_ : Dossier de travail
* _signe_detection_model_creation_ : Notebook de la creation du model
* _signe_detection_ : Notebook de la detection des signes sur une image ou en temps réel
* _ressources_ : Ressource pour le readme

## Explications

Dans ce brief nous allons devoir détecter les lettres de l'alphabet en langage des signes.
Pour ce faire nous avons choisi d'utiliser le transfer learning avec le modele SSD mobilenet 320X320 de Tensorflow Zoo et l'api d'object detection de Tensorflow (notebook signe_detection_model_creation)

Nous allons ensuite tester ce model sur une ou plusieurs images et en temps réel avec une camera (notebook signe_detection)

## Dataset 
Le dataset est constitué de photos prises par nous-même.
Il est formé d'environ 227 photos de signes qui correspondent aux lettres de l'aphabet de A-Z __sans__ J et Z
