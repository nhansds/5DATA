## Algebra

Trois types d'algèbres utilisés pour les data sciences :

- Algèbre élementaire
- Algèbre linéaire
- Les systèmes d'équations linéaires

Structures de l'algèbre :

- Scalaire (un nombre)
- Vecteur (une ligne ou une colonne de nombres et traitée comme une seule unité)
- Matrice (plusieurs lignes et colonnes de données dans un seul objet)

Les matrices simplifient la notation.

L’algèbre linéaire est au cœur de nombreuses procédures utilisées dans les data sciences.

## Systems of Linear equations

Comment travaillé avec plusieurs inconnus ?

Problème de dépendance mutuelle

- X dépend de Y
- Y dépend de X

Peut être résolu à la main - On peut utilisé l'algèbre linéaire ou matriciel

Conclusion

- Les systèmes d'équations linéaires sont une partie essentielle du travail avec les données.
- C'est une méthode importante pour équilibrer plusieurs inconnues afin de trouver une solution unique.
- En outre, ils reposent sur l’algèbre linéaire ou matricielle, bien qu’ils puissent même souvent être réalisés à la main.

## Calculus

Il y a trois cas en particulier où il intervient : 

- cela fait partie des fondements des pratiques des statistiques, pour des choses comme la régression des moindres carrés, les distributions de probabilité,
- Pour le changement, c'est-à-dire mesurer des quantités ou des taux qui changent avec le temps 
- Maximum et minimum, chaque fois que vous essayez de maximiser ou de minimiser quelque chose, vous aurez généralement à faire des calculs.

Deux types de calculs :

- le calcul différentiel (pour les taux de changement à un moment donné)
- le calcul intégral, dans lequel vous déterminez une quantité de quelque chose à un moment donné en fonction du taux de changement

Conclusion :

- le calcul est vital pour les data sciences
- c'est le fondement des analyses statistiques
- il est utilisé directement pour des problèmes d'optimisation

## Big O and function performance

Le problème est que les fonctions que vous pouvez exécuter sur vos données varient en vitesse. Le taux de croissance d'une fonction, c'est-à-dire combien de temps cela prend plus longtemps, s'appelle son ordre.

C'est pourquoi on l'appelle big O, O est pour l'ordre. Big O décrit les taux de croissance et met en évidence que les différences de taux de croissance peuvent être dramatiques et parfois contre-intuitives. Ainsi, par exemple, certaines fonctions sont très rapides. Vous avez ce qu'on appelle O (1), c'est un déterminant constant des nombres binaires, pairs ou impairs. O (log (n)) qui est une fonction logarithmique.

Conclusion :

- la vitesse des fonctions varie considérablement.
- Les fonctions peuvent également varier de manière inattendue selon les tâches. Et vous devez toujours être conscient des exigences informatiques qui vont devenir une fonction, à la fois la taille de l'ensemble de données et des tâches particulières que vous essayez d'exécuter.

## Bayes probability

Le théorème de Bayes est un outil important qui vous permet de regarder différement les choses lorsque vous analysez des données. Plus spécifiquement, cela vous aide souvent à répondre à la bonne question. La plupart des tests d'inférence vous donnent généralement la probabilité des données, l'effet observé, en supposant une cause ou une hypothèse particulière. Mais ce que la plupart des gens veulent, c’est le contraire. Ils veulent la probabilité de l'hypothèse ou de la cause en fonction des données observées, et ces deux réponses peuvent avoir des réponses très différentes.

Le théorème de Bayes utilise les probabilités antérieures et les informations de test pour obtenir ce que l'on appelle des probabilités postérieures. Cela concerne les probabilités avant et après la collecte de données. Vous commencez avec la probabilité des données étant donné l'hypothèse. Cela s'appelle la probabilité des données, ou la sensibilité. Et c'est ce que vous obtenez normalement d'un test d'hypothèse. Vous ajoutez à cela la probabilité de l'hypothèse ou de la cause. C'est ce qu'on appelle la probabilité antérieure, et c'est comme le taux de base, quelle est la fréquence de cette situation particulière. À cela, vous ajoutez la probabilité des données.

Quelle est la probabilité d'obtenir ce genre de résultat? Cela s'appelle le marginal. Et lorsque vous les combinez, cela vous donne la probabilité de l'hypothèse ou de la cause en fonction des données observées, et cela s'appelle une probabilité postérieure ou postérieure.

Conclusion :

- On a besoin d’informations sur les probabilités antérieures pour pouvoir utiliser ce système.
- Si vous ne disposez pas de ces informations, vous pouvez utiliser une courbe de probabilité pour obtenir toute une plage de valeurs probables.
- Le théorème de Bayes et ses calculs sont plus susceptibles de vous donner la bonne réponse à la question que vous ou votre client vouliez examiner en premier lieu.



