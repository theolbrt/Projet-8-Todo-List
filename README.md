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

![Diagramme de sequence](https://github.com/theolbrt/ToDo-List/blob/master/UML/SequenceTodo.png


Cette application est basé sur le model MVC ( Model-Vue-Controller ) qui va permettre de séparer la logique du code en trois parties que l'on va retrouver dans des fichiers distincts.
<br/>
C'est le controller qui va recevoir les différentes requetes de l'utilisateur et qui va ensuite faire le lien avec les deux autres fichier ( model et vue ) pour echanger des informations avec ces derniers.<br/>
Le role du model va etre d'aller chercher les données dans une base de données qui vont ensuite etre traitées par le controller.<br/>
Enfin, la vue va essentiellement se concentrer sur la récupération de variable pour savoir ce qu'elle doit afficher. 

### AUDIT DE PERFORMANCE

[Suivez ce lien pour vous rendre sur l'audit de performance](https://github.com/theolbrt/ToDo-List.wiki.git)


## CORRECTION DE BUGS

La premiere correction de bugs a effectuer était de réctifier l'orthographe de la fonction addItem().

![Correction bug 1](https://github.com/theolbrt/ToDo-List/blob/master/img/modif1.png)

La seconde modification était d'améliorer la méthode qui permet de généré un ID unique.

![Amelioration](https://github.com/theolbrt/ToDo-List/blob/master/img/Modif2.png)

### FONCTIONNEMENT DE L'APP

Le fonctionnement de cette application est tres simple :
- Pour commencer, il faut cloner le projet a l'aide du lien un peu plus en haut.

- Une fois cloner, lancer l'application. 

- Une fois l'application lancé, vous allez pouvoir crée un nouveau todo. Pour ce faire, il vous suffit de rentrer le nom de celui-ci et d'appuyer sur entré. Le nouveau todo va ensuite s'afficher sous forme de liste en dessous du champ de saisie.

- L'orsque le todo est enregistré, vous allez pouvoir sois supprimer cette tache en cliquant sur la croix qui se trouver a dorite lorque vous passez votre souris sur le todo. 
Ou alors vous pouvez cocher ce todo en cliquant a gauche de celui-ci afin d'indiquer que la tache est accompli.

- Vous pouvez remarquer 3 onglets en dessous de la liste de todo, "All", "Active" et "Completed".
Vous retrouverez respectivement, tout les todos inséré dans l'application, qu'ils soient complété ou non. Dans le 2e onglets, tout les todos actifs, donc qui ne sont pas terminer. Et enfin, tout les todos qui auront été complétés.

- Enfin, vous pourrez supprimer tout les todos complétés en cliquant sur l'onglet "Clear completeed".
