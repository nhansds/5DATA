# Data Exploration

## Graphes exploratoires

Première chose à faire une fois les données en notre possession.

Avec les graphes exploratoires tu peux :

- avoir une idée plus précise des données
- vérifier les hypothèses de votre analyse 
- vérifier les anomalies 
- voir si les données suggèrent quelque chose de nouveau et d’inattendu

Pourquoi commencer avec des graphes ?

- Ils sont visuels
- Ils sont denses en terme d'informations
- Ils permettent de communiquer vite et bien

Les graphiques sont également le moyen le plus rapide de vérifier la forme de la distribution, les écarts et les valeurs aberrantes. Tout cela peut avoir un impact significatif sur votre analyse.

En terme de graphiques d'explorations :

- Une seule variable
- Associations entre plusieurs variables

Cela permet de repérer les cas particuliers, des valeurs particulières, des erreurs ou des oublis.

Comment faire des graphiques ?

- En codant (R, Python, JS)
- Avec des applications (Excel par ex)
- A la main

Typologies de graphiques :

- Graphiques en barres
  - Pour les catégories
  - Simple à lire
  - Valeurs descendantes
  - Différences entre des groupes
- Graphiques en boites
  - Pour des variables quantitatives / mesurables
  - Montre les quartiles, les valeurs médianes, les minimums et les maximums
- Histogrammes
  - Pour des variables quantitatives / mesurables
  - Montre la forme de la répartition
- Matrices de dispersion
  - Montre les associations entre plusieurs variables quantitatives
  - Plus simple à lire que les graphiques en 3D

Tu dois te poser 3 question ?

- Avez-vous ce qu'il vous faut pour répondre à vos questions?
- Existe-t-il des blocs ou des lacunes dans les données?
- Y a-t-il des cas exceptionnels? Et y a-t-il des erreurs dans les données?

Conclusion

- l'exploration est toujours une première étape essentielle dans toute bonne analyse de données. 
- En outre, vous souhaitez utiliser une méthode simple et rapide. Utilisez un outil qui lui convient bien. Quelque chose avec lequel vous êtes à l'aise et que vous pouvez explorer rapidement.
- Enfin, l'exploration graphique est un précurseur de l'exploration numérique, dont nous parlerons ensuite.

## Statistiques exploratoires

Le principe est le suivant : 

> En premier des graphiques, ensuite des chiffres

Nous sommes toujours dans une phase d'exploration, pas dans la modélisation. De plus nous utilisons toujours des estimations empiriques, et non théoriques.

Nous pouvons quand même vérifier les effets de la manipulation des données et regarder comment les données réagissent.

Il existe 3 catégories de méthodes utilisées dans l'exploration statistiques : 

- Statistiques robustes
- rééchantillonner les données ou les statistiques 
- transformer les données

Statistiques robustes :

- Stable en présence d'anomalies
- moins affectés par les valeurs aberrantes, l'asymétrie, les kurtoses, etc. 
- Beaucoup de choix disponibles (Valeurs médianes, quartiles, interquartiles...)
- Pas toujours simple

 En théorie des probabilités et en statistique, le kurtosis, aussi traduit par coefficient d’acuité, coefficient d’aplatissement et degré de voussure, est une mesure directe de l’acuité et une mesure indirecte de l'aplatissement de la distribution d’une variable aléatoire réelle. 

Le rééchantillonnage :

- estimations empiriques de la variabilité d'échantillonnage. 

  Au lieu d'essayer d'obtenir une erreur standard de population, vous obtenez plusieurs écarts-types en effectuant un échantillonnage à partir de vos données et en vous servant de cette estimation de la variabilité

- Jackknife, dans lequel vous utilisez des sous-ensembles de données aléatoires ou un échantillonnage sans remplacement.

- Bootstrap, où vous tirez des échantillons avec remplacement. 

- Permutation, en mélangeant les cas de différents groupes. 

- Validation croisée (processus d'apprentissage automatique ; moyen de vérifier la cohérence des résultats).

La transformation

- Vous recherchez des fonctions fluides sans grands sauts qui préservent l'ordre de vos données et vous permettent d'utiliser l'intégralité du jeu de données. 
- Souvent, les transformations sont utilisées pour corriger des données asymétriques ou pour tracer une ligne courbe dans un diagramme de dispersion.
- Une méthode courante est appelée "Tukey" pour "Ladder of Powers" de John Tukey.

Conclusion

- Il est bon d’obtenir plusieurs perspectives sur les données.
- Il est bon de vérifier la stabilité des données dans différentes circonstances. 
- Les statistiques exploratoires préparent le terrain pour la modélisation.

