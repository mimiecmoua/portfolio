---
title: JEU TETRIS
publishDate: 2023-07-18 00:00:00
img: /portfolio/assets/Tetris.png
img_alt: Iridescent ripples of a bright blue and pink liquid
description: |
  Une version ordinateur du jeu Tetris classique et addictif.
tags:
  - HTML
  - CSS
  - JavaScript
---

## Histoire du jeu Tetris

> Tetris est bien plus qu'un simple jeu vidéo. C'est un véritable classique intemporel.

Créé en 1984 par le programmeur russe Alexey Pajitnov, <a href="https://mimiecmoua.github.io/Tetris">JEU Tetris</a> rend les gens heureux. Alors qu'il travaillait au centre de recherche informatique Dorodnitsyn de l'académie des sciences de l'URSS à Moscou. Pajitnov a conçu le jeu pendant son temps libre en utilisant un ordinateur Electronic 60, un ordinateur IBM compatible, et le langage de programmation pascal.

le concept de tetris est inspiré d'un jeu de puzzle traditionnel russe appelé "Pentomino", qui utilise des formes géométrique conposées de cinq carrés adjacents. Pajitnov a simplifié le concept en utilisant des formes composées de quatre carrés, appelées tétriminos, et en les faisant tomber du haut de l'écran dans un champ de jeu.

Ce jeux met à l'épreuve les réflexes, le concentration et la capacité de planification des joueurs.

#### Comment jouer ?

Ce jeu est disponible uniquement sur ordinateur. Appuyez sur le bouton "Start" pour commencer. Lorsque le curseur descend, vous pouvez le faire pivoter avec la flèche "Haut" de votre clavier. Déplacez-le à gauche et à droite avec les flèches correspondantes. Accélérez la descente du curseur avec la flèche "Bas". Vous pouvez mettre le jeu en pause en cliquant sur le bouton "Start/Pause" et recommencer une partie en rafraîchissant la page.

### HTML5 Hyper text Markup Language

Le HTML est le langage de balisage utilisé pour structurer le contenu des pages web. Il repose sur le principe fondamental des balises, qui encadrent différents éléments pour indiquer leur type et leur fonction sur la page, permettant ainsi aux navigateurs web (ex: Google Chrome, Edge) de les interpréter et de les afficher correctement pour les utlilisateurs.

Dans le code HTML que j'ai créé, certains éléments sont marqués avec des identifiants qui agissent comme des étiquettes spéciales. ces identifiants aident mon code JavaScript à repérer ces éléments spécifiques sur le page. Par exemple, j'ai un élément de score qui est identifié par 'score', et un bouton de démarrage identifié par 'start-butoon'. De cette façon, lorsque mon code JavaScript recherche ces éléments, il peut les trouver facilement en utilisant leurs identifiants respectifs. Cele permet de créer des interactions dynamiques sur la page, comme démarrer ou arrêter le jeu en cliquant sur le bouton, ou afficher le score du joueur.

Cliquez sur le lien suivant pour explorer le code HTML => <a href="https://github.com/mimiecmoua/Tetris/blob/main/index.html">Code source HTML.</a>

### CSS 3 Cascading Style Sheets

Le CSS est un langage de feuilles de style utilisé pour styliser et mettre en forme les éléments HTML d'une page web. il repose sur le principe de la sélectivité et de la hiérarchie, permettant aux développeurs de définir des règles de style qui seront appliquées de manière sélective aux différents éléments, afin de contrôler leur apparence et leur mise en page sur le navigateur des utilisateurs.

Dans ce code CSS, j'ai défini différents styles pour personnaliser l'apparence et la mise en page d'une page web. Tout d'abord, j'ai spécifié une image de fond pour le corps de la page, créant ainsi un arrière-plan avec une image de galaxie. Ensuite, j'ai défini des styles pour les titres et les boutons, en utilisant la police 'Minecraft' pour donner à la page une ambiance de jeu. Les titres sont centrés et en majuscules, avec une couleur de texte vert vif pour un contraste saisissant. Le bouton de démarrage est stylisé avec une couleur de fond verte caractéristique de Minecraft, qui devient plus foncée au survol pour une interaction visuelle. Pour le tableau de jeu Tetris, j'ai défini des styles pour le conteneur, la grille et les différentes cellules, en leur donnant des dimensions et des couleurs appropriées pour recréer l'aspect du jeu original. Enfin, j'ai ajouté un pied de page fixe en bas de la page, affichant des crédits avec une police Minecraft et une couleur de texte verte pour une touche finale cohérente avec le thème du jeu.

Cliquez sur le lien suivant pour explorer le code CSS => <a href="https://github.com/mimiecmoua/Tetris/blob/main/style.css">Code source CSS.</a>

### JavaScript

Dans ce code JavaScript, j'ai écrit des instructions pour créer le jeu Tetris en utilisant les fonctionnalités du navigateur web. Tout d'abord, j'ai défini des variables pour sélectionner les éléments HTML pertinents, comme la grille de jeu, le bouton de démarrage, et le score affiché. Ensuite, j'ai défini les différentes formes de tétriminos et leurs rotations possibles, ainsi qu'un tableau de couleurs correspondant à chaque forme. En utilisant des fonctions, j'ai implémenté la logique pour dessiner et effacer les tétriminos sur la grille, les faire descendre automatiquement, les déplacer horizontalement, les faire tourner, et gérer les collisions avec les bords et les tétriminos déjà placés. J'ai également ajouté des fonctionnalités pour afficher le prochain tétrimino à l'écran, augmenter le score lorsqu'une ligne est complétée, et détecter la fin de partie lorsque les tétriminos atteignent le haut de la grille. Enfin, j'ai utilisé des événements pour contrôler le jeu à l'aide des touches du clavier, et j'ai ajouté un bouton pour démarrer ou arrêter le jeu. Ce code combine des concepts de manipulation du DOM, de gestion d'événements, de manipulation de tableaux, et de logique de jeu pour recréer l'expérience classique du jeu Tetris dans un navigateur web.

Cliquez sur le lien suivant pour explorer le code JavaScript => <a href="https://github.com/mimiecmoua/Tetris/blob/main/script.js">Code source JavaScript.</a>

#### Conclusion

Imaginez le HTML comme la structure d'une maison, le CSS comme la peinture et la décoration qui lui donnent son style, et le JavaScript comme l'électricité qui anime les différents appareils et rend la maison fonctionnelle. De la même manière, ces langages se combinent pour créer un site web complet et interactif. Le HTML définit la structure et le contenu de la page, le CSS lui donne son aspect visuel et attrayant, tandis que le JavaScript ajoute des fonctionnalités dynamiques et interactives. C'est cette synergie entre le HTML, le CSS et le JavaScript qui donne vie à mon jeu tetris que vous visitez et lui confère son unicité et sa fonctionnalité.

En somme, ce projet de création de jeu tetris illustre non seulement ma maîtrise technique en développement web, mais également à concevoir des expériences ludiques pour les utilisateurs. Je suis prête à mettre en oeuvre mon expérience pour réaliser vos projets les plus ambitieux.

> Contactez-moi dès aujourd'hui et ensemble, faisons de votre vision une réalité.
