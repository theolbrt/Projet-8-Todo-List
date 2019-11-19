# PROJET 8 - TODO-LIST

L'objectif de ce projet était de reprndre un projet éxistant, de corriger les bugs, d'éffectuer des tests unitaires a l'aide de Jasmine et de créer une documentation fonctionnelle et un audit de performance.

## SCREENSHOT

<p align="center">
  <img src="https://raw.githubusercontent.com/DesignGreg/Projet8-OpenClassRooms/master/Documentations%20-%20%C3%A9tape%204/Doc%20utilisateur/assets/Screenshot%2001.jpg">
</p>

## INSTALLATION 

Pour récupérer le projet :
```bash
git clone https://github.com/theolbrt/ToDo-List.git
```
 

## DIAGRAMME UML

### DIAGRAMME DE CLASSE

![Diagramme de classe](https://github.com/theolbrt/ToDo-List/blob/master/UML/DiagrammeClasse.png)

### DIAGRAMME DE SEQUENCE

Cette application est basé sur le model MVC ( Model-Vue-Controller ) qui va permettre de séparer la logique du code en trois parties que l'on va retrouver dans des fichiers distincts.
<br/>
C'est le controller qui va recevoir les différentes requetes de l'utilisateur et qui va ensuite faire le lien avec les deux autres fichier ( model et vue ) pour echanger des informations avec ces derniers.<br/>
Le role du model va etre d'aller chercher les données dans une base de données qui vont ensuite etre traitées par le controller.<br/>
Enfin, la vue va essentiellement se concentrer sur la récupération de variable pour savoir ce qu'elle doit afficher. 

### AUDIT DE PERFORMANCE

[Suivez ce lien pour vous rendre sur l'audit de performance](https://github.com/theolbrt/ToDo-List.wiki.git)


## CORRECTION DE BUGS

La premiere correction de bugs a effectuer était de réctifier l'orthographe de la fonction 

![Correction bug 1](https://github.com/theolbrt/ToDo-List/blob/master/img/modif1.png)
img/modif1.png
