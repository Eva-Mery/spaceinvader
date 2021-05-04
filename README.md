# spaceinvader

## Semaine n°1 : du 28 avril au 5 mai

### Sprints et fonctionnalités réalisées

**Fonctionnalité n°1 : Déplacer un vaisseau dans l'espace de jeu (fini)**
- Story n°1 : Créer un espace de jeu
1. Un espace de jeu est créé aux dimensions données (2D) 
2. Cet espace de jeu est vide

- Story n°2 : Positionner un nouveau vaisseau dans l’espace de jeu
1. Un nouveau vaisseau est créé 
2. Le vaisseau est positionné aux coordonnées transmises 
3. Si un nouveau vaisseau essaye d’être positionné en dehors des limites de l’espace jeu, alors une exception devra être levée. 
Contraintes : 
    1. La position souhaitée est transmise par ses coordonnées x et y. Le coin supérieur gauche de l’espace jeu (point en haut à gauche) a pour coordonnées (0,0) 
    2. La taille du vaisseau est réduite pour l'instant à son minimum (1 seul point)


### Fonctionnalité en cours d’implémentation 

Aucune

### Diagramme de classes

![seance1](https://user-images.githubusercontent.com/75761047/117060332-143cff80-ad21-11eb-8d45-bfafbe28df01.gif)

### Nuage de mots du projet spaceinvaders (séance n°1)



### Difficultés rencontrées

J'ai téléchargé le .zip de Source Code Word Cloud Generator, cependant, lorsque je lance l'exécutable, le programme ne répond pas.

### Remarques diverses
Pour pouvoir mettre en place les tests, il a été nécessaire d’ajouter une fonctionnalité supplémentaire qui permet de représenter l’espace de jeu dans une chaîne ASCII.



## Glossaire
**Vaisseau :** véhicule commandé par le joueur, pouvant se déplacer de droite à gauche et ayant la possibilité de lancer des missiles destinés à détruire le(s) envahisseurs.

**Envahisseur :** ennemi qui apparaît à l'écran, se déplace automatiquement et qui doit être détruit par un missile lancé depuis le vaisseau du joueur.

**Missile :** projectile envoyé à la verticale par le vaisseau vers l'envahisseur dans le but de le détruire.
