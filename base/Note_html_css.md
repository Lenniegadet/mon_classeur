# HTML
## Texte

`<html>` : montre language de balise \
`<head>` : toujours derrière balise <html> , aide le navigateur à afficher la page mais rien à afficher \
`<meta>` : donne plus d'informations sur comment afficher la page \
`<title>` : titre de la page \
Ex: `<title>Les Grenouilles</title>` \
`<body>` : contient tout le reste après avoir fermé la balise `</head>` , tout ce qui est dans cette balise sera visible \
`<h1>` : ajoute un gros titre \
Ex: `<h1>`Tout sur les grenouilles !`</h1>` \
`<h1>`...`<h6>` = titre de niveau + important au - important \
`<p>` : paragraphe \
`<br>` : sauter une ligne

## Mise en évidence des textes

`<em>` : met un texte en italique \
`<strong>` : met un texte en gras

## Listes

`<ul>` : crée une lioste non numérotée \
`<li>` : marque chaque élements de la liste \
`<ol>` : crée une liste ordonnée/numérotée

## Images

`<img>` : ajouter une image \
Ajouter src="{insérez l'url de l'image}" à l'intérieur de la balise `<img>` permet d'identifier la source de l'image \
Ex: `<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.radiofrance.fr%2Ffranceculture%2Fpodcasts%2Fle-monde-vivant%2Fbenitier-et-meteo-la-grenouille-4363598&psig=AOvVaw2aQIKh0BtV8WJpqhpcAQlX&ust=1668507883541000&source=images&cd=vfe&ved=0CA0QjRxqFwoTCJjzhLC6rfsCFQAAAAAdAAAAABAD">` \
Ajouter alt="{insérez un texte}" dans la balise au dessus permet d'écrire un texte qui peut décrire l'image \
Ajouter width="{insérez une grandeur}" dans la même balise permet de définir la taille du texte

# CSS
## Mise en forme du texte

`<style>` : indique quelle partie de la page est mise en forme \
Entre les balises `<style>` : \
Indiquez le titre/texte/paragraphe à mettre en forme puis entre deux accolades : \
color:; : permet de changer la couleur d'un texte \
Ex: color: green; / color: rgb(0,127,23); \
background-color:; : permet de changer la couleur du fond \
Ex: background-color: green; / background-color: rgb(0,127,23);

## Séléction par identifiant

Dans la balise que vous souhaitez identifer, il faut y écrire id="{insérez un nom pour le paragraphe}" 
Puis écrivez #{identifiant de la balise} pour l'identifier lors de la mise en forme

Pour identifier plusieurs paragraphes, il faut écrire class="{insérez un nom en commun à tout les paragraphes}"
Puis écrivez .{identifiant des paragraphes}