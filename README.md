# Démo de visualisation des Géonym

## Fonctionnement

C'est la librairie Leaflet qui est utilisé pour visualiser la carte et dessiner les zones correspondantes aux geonym.

Le dessin des zones (quasi rectangulaires) est fait de façon récursive par la fonction drawGrid appelée à chaque déplacement ou changement de zoom de la carte.

## Installation

`git clone https://github.com/geonym/visugeonym.git --recursive`

index.html contient tout le code javascript, aucun serveur particulier n'est nécessaire, on peut charger cette page HTML directement en local dans son navigateur.
