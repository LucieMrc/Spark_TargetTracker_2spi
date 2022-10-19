# Spark_TargetTracker_2spi

**Ou comment créer rapidement un filtre Spark en réalité augmentée avec un Target Tracker.**

## Les ressources Spark

-> [Mettre en place un target tracking](https://sparkar.facebook.com/ar-studio/learn/articles/world-effects/target-tracker)

Ajouter le Target Tracker.

![Ajouter le target tracker](./images/img1.png)

Dans les paramètres du Target Tracker, ajouter une texture qui sera l'image trackée.

![Ajouter le target tracker](./images/img2.png)

![Ajouter le target tracker](./images/img3.png)

Pour ajouter un élement lié à l'image trackée, il faut le drag and drop par dessus le Target Tracker pour le mettre dedans.

![Ajouter le target tracker](./images/img5.png)

Ici le `plane0` n'apparaît donc que quand l'image trackée est detéctée.

![Ajouter le target tracker](./images/img4.png)

Dans les paramètres du Target Tracker, on peux choisir que la target est `Movable` ou `Fixed`. 

![Ajouter le target tracker](./images/img6.png)

Pour une target `Movable`, en mouvement, l'effet suit l'image trackée lorsqu'elle se déplace sur l'écran.
Pour une target `Fixed`, statique, l'effet apparaît à l'endroit où l'image trackée a été détectée.

<!--Faire des gifs. -->