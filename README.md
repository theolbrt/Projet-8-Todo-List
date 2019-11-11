# PROJET 8 - TODO-LIST

L'objectif de ce projet était de reprndre un projet éxistant, de corriger les bugs, d'éffectuer des tests unitaires a l'aide de Jasmine et de créer une documentation fonctionnelle et un audit de performance.

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
