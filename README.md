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


## Semaine n°2 : du 5 au 17 mai

### Sprints et fonctionnalités réalisées

**Fonctionnalité n°1 : Déplacer un vaisseau dans l'espace de jeu (fini)**
- Story n°3 : Déplacer le vaisseau vers la droite dans l'espace de jeu
1. Le vaisseau se déplace d'un pas vers la droite 
2. Si le vaisseau se trouve sur la bordure droite de l'espace de jeu, le vaisseau doit rester immobile (aucun déplacement, aucune exception levée : le vaisseau reste juste à sa position actuelle).

- Story n°4 : Déplacer le vaisseau vers la gauche dans l'espace de jeu
1. Le vaisseau se déplace d'un pas vers la gauche 
2. Si le vaisseau se trouve sur la bordure gauche de l'espace de jeu, le vaisseau doit rester immobile (aucun déplacement, aucune exception levée : le vaisseau reste juste à sa position actuelle).

### Fonctionnalité en cours d’implémentation 
**Fonctionnalité n°2 : Déplacer un vaisseau dans l'espace de jeu (commencé)**
A faire la prochaine fois : Refactoring sur la classe Vaisseau 

### Diagramme de classes

![seance2](https://user-images.githubusercontent.com/75761047/118392759-7e1baa00-b63b-11eb-8fd5-2033bd1a4472.gif)

### Nuage de mots du projet spaceinvaders (séance n°2)

![Nuage seance2](https://user-images.githubusercontent.com/75761047/118392754-73611500-b63b-11eb-82fe-9663c5d02f04.png)

### Difficultés rencontrées
Aucune

### Remarques diverses
Aucune


## Semaine n°3 : du 17 au ? mai

### Sprints et fonctionnalités réalisées
**Fonctionnalité n°2 : Déplacer un vaisseau dans l'espace de jeu (commencé)**
- Étape n°1 : Positionner un nouveau vaisseau avec une dimension donnée.
1. Refactoring sur la classe Vaisseau.
- Étape n°2 : Faire en sorte qu'il soit impossible de positionner un nouveau vaisseau qui déborde de l'espace de jeu.
- Étape n°3 : Déplacer un vaisseau vers la droite en tenant compte de sa dimension.
- Étape n°4 : Déplacer un vaisseau vers la gauche en tenant compte de sa dimension.
- Zoom sur le Refactoring de la classe de test SpaceInvadersTest.
1. Mise en place du refatoring dans une méthode de test
2. Généralisation de ce refatoring à toutes les méthodes de test (en pas à pas)
3. Suppression de la surcharge pour ne conserver que la méthode positionnerUnNouveauVaisseau(Dimension dimension, Position position)
4. Quelques mots sur le code smell Primitive Obsession et le refactoring Introduce Parameter Object

### Fonctionnalité en cours d’implémentation 
**Fonctionnalité n°2 : Déplacer un vaisseau dans l'espace de jeu (commencé)**
A faire la prochaine fois : Refactorer la classe Vaisseau 

### Diagramme de classes

![seance3](https://user-images.githubusercontent.com/75761047/118621672-e1861300-b7c6-11eb-86ba-bbd3d985376b.gif)

### Nuage de mots du projet spaceinvaders (séance n°3)

![image](https://user-images.githubusercontent.com/75761047/118623416-83f2c600-b7c8-11eb-94f0-630b42e15f75.png)

![image](https://user-images.githubusercontent.com/75761047/118623595-b13f7400-b7c8-11eb-8027-5489c8b05fbc.png)

### Difficultés rencontrées
Je n'ai encore une fois pas réussi à ouvrir le logiciel pour créer le nuage de mots, qui pourtant avait fonctionné lors de la scéance précédente lorsque j'étais à l'IUT.

### Remarques diverses
Aucune


## Glossaire
**Vaisseau :** véhicule commandé par le joueur, pouvant se déplacer de droite à gauche et ayant la possibilité de lancer des missiles destinés à détruire le(s) envahisseurs.

**Envahisseur :** ennemi qui apparaît à l'écran, se déplace automatiquement et qui doit être détruit par un missile lancé depuis le vaisseau du joueur.

**Missile :** projectile envoyé à la verticale par le vaisseau vers l'envahisseur dans le but de le détruire.
