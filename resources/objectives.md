# Bacon Ipsum
## Générateur de Lorem ipsum
L'objectif est de créer un générateur de Lorem ipsum.
Pour cela nous utiliserons une API externe qui nous fournira le lorem ipsum, ou plus exactement... le Bacon Ipsum !

Une API est un service qui va nous founir des données et qui peut être interrogé comme une page web, via une URL
et en utilisant le protocole HTTP. On peut donc interroger une telle API simplement en faisant une requête Ajax.

L'API qui va nous aider est <a href="https://baconipsum.com/json-api/">Bacon Ipsum</a>.

## Interface Utilisateur
L'interface est très simple et s'inspirera de celle du site de l'API Bacon Ipsum.
Elle sera composée :

 - d'une liste déroulante pour choisir le **nombre de pragraphes** souhaités (entre 1 et 10)
 - d'un **bouton** "Générer" pour lancer la génération des paragraphes
 - d'un espace où les paragraphes générés vont être affichés (chaque paragraphes devra être affiché dans une balise \<p>)

## Choix techniques
Il existe plusieurs solutions techniques pour envoyer une requête AJAX.
Vous découvrirez ici la méthode historique en JavaScript : la classe ***XMLHttpRequest*** !

## Indications
Il peut être utile de créer une ***fonction utilitaire*** pour envoyer une requête AJAX ! 

## Mockups

![Mockup 1](resources/mockups/mockup1.jpg)
![Mockup 2](resources/mockups/mockup2.jpg)