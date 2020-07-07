# Parallaxe
[Amaury FAUVEL](https://github.com/AmauryFauvel) & [Rym OUENZAR](https://github.com/RymOUENZAR)

## Un projet Unity avec emguCV
https://www.youtube.com/watch?v=B_UIfFA77pk

![Demonstration](https://github.com/AmauryFauvel/Parallax/blob/master/Medias/Prototype.gif)

## Effet Parallaxe :
L'effet Parallaxe est l’impact d'un changement d'incidence d'observation, c'est-à-dire, la parallaxe est l'effet du changement de position de l'observateur sur ce qu'il perçoit. En d'autres termes, les objets qui sont au loin se déplacent plus vite des objets proches, du point de vue de l'observateur.
C'est un des effets qui nous permet de percevoir la 3D (avec la stéréoscopie, etc..).

## Traitement d'images :
- Détection d'un objet avec une couleur bien définie (pour filmer avec un téléphone), calcul du centre de l'objet et le tracking.
- Détection d'un visage grâce au classificateur cascade, calcul de la position de l'œil et tracking.

## Caméra :
Pour que l'effet fonctionne, la caméra doit utiliser un frustum asymétrique, afin de regarder toujours la même fenêtre quelque soit sa position.

## Références
[Calculating Stereo Pairs par Paul Bourke Juillet 1999](http://paulbourke.net/stereographics/stereorender/)

[Asymetric Frustum par Emerix 2015](https://github.com/Emerix/AsymFrustum)

[TheParallaxView par Peder Norrby / ALGOMYSTIC Février 2018](https://www.anxious-bored.com/blog/)
