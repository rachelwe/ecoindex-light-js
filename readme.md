# Ecoindex light javascript

WIP : fork créée pour permettre l'utilisation de styles et une intégration propre à chaque site web

Version bêta pour mesurer l'ecoindex de la page en cours.
Le but de ce script est de faire une mesure avec très peu de code javascript simple, pour se rapprocher le plus possible d'un indice similaire à ecoindex.
Pour informer l'utilisateur de l'impact de la page en cours.


## Installation

Ajouter à votre page html `<script src="https://cdn.jsdelivr.net/gh/simonvdfr/ecoindex-light-js@main/ecoindex.min.js"></script>`


## Marge d'erreur

Si un petit astérisque (*) apparaît à côté de la note c'est que le script n'a pas réussi à mesurer le poids de certaines ressources (souvent des ressources externes au domaine)


## Licences

Les fonctions de calcul viennent de [GreenIT-Analysis](https://github.com/cnumr/GreenIT-Analysis/).
`GNU Affero General Public License AGPL v3 / Copyright (C) 2019 didierfred@gmail.com`

L'algorithme [EcoIndex](http://www.ecoindex.fr/quest-ce-que-ecoindex/) est sous [Licence Creative Commons CC-By-NC-ND](https://creativecommons.org/licenses/by-nc-nd/2.0/fr/)

Le code additionnel pour donner les variables pour le calcul est sous `licence MIT` par Simon Vandaele [Translucide](http://www.translucide.net)
