**Chapitre 8 Applied Statistics** 

**Hypothesis Testing** : Tester sa théorie

1 ère étape et 2 ème étape : 

![](D:\Msc2\5DATA\1.1 - Blended Learning  Understanding Data Science ( ~3h)\screens\a.png)

L’utilisation des tests d’hypothèses : 

\-    Recherches scientifiques

\-    Diagnostiques 

\-    Le pour et le contre (Go/no go decisions) 

Deux couples d’hypothèses, **Null Hypothesis** et **Alternative Hypothesis** 

  ![](D:\Msc2\5DATA\1.1 - Blended Learning  Understanding Data Science ( ~3h)\screens\b.png)

Prendre une décision :

\-    Méthode du faux positif : Echantillon qui montre les effets de façon aléatoire 

\-    Méthode du faux négatif : Les données semblent aléatoires (A revoir)

Ces deux méthodes sont dangereuses : 

\-    Peuvent facilement être mal interprété

\-    Les questions peuvent être mal posées 

 

Conclusion : 

\-    Commun pour la plupart des oui/non questions 

\-    Utiles malgré les critiques 

\-    Les estimations sont très utiles 

**Confidence Intervals** 

 Niveaux de confidences :

\-    Choisir un niveau 

\-    95 % de niveaux communs

\-    Plus de confidence = des intervalles plus libres

Efficacité et précision (Accuracy and precision) 

![](D:\Msc2\5DATA\1.1 - Blended Learning  Understanding Data Science ( ~3h)\screens\c.png)

Interprétation :

  ![](D:\Msc2\5DATA\1.1 - Blended Learning  Understanding Data Science ( ~3h)\screens\d.png)

Facteurs qui affectent les intervalles libres : 

\-    Niveau de confidence 

\-    Déviation standard

\-    Sample size (plus important) 

Conclusion : 

\-    Les intervalles de confidences sont focus sur les paramètres 

\-    Les variations sont explicitement incluses 

\-    Plus informatifs que les tests d’hypothèses 

**Les problèmes communs dans la modélisation** 

\-    La non-normalité des données 

o  *Outliers*

o  Modèles et mesures distordues 

o  Tentative de transformations

o  Plusieurs distributions ? 

\-    La non-linéarité des données 

o  Supposition commune

o  Tentative de transformation de variables 

o  Les polynômes peuvent aidées

\-    Mutlicolinéarité (Bon courage 😊 ) 

o  Les prédictions peuvent corrélées 

o  Les coefficients peuvent être affectés 

o  Utilisation de trop de variable 

 

*The combinatorial Explosion and the Curse of dimensionality* 

![](D:\Msc2\5DATA\1.1 - Blended Learning  Understanding Data Science ( ~3h)\screens\e.png)

Les données manquantes : 

\-    Peuvent créer des distorsions et créer des impartialités 

\-    Chercher les patterns qui manquent 

\-    Ne peut pas remplacer les données manquantes 

Conclusions :

\-    Les données apportent des complications 

\-    Les erreurs mènent aux ambiguïtés, l’impartialités, les hypothèses

\-    L’utilisation des analyses et théories peuvent résoudre celles-ci 


 

 

**Validating Models** 

Est-ce qu’on est dans la cible ? 

Les probabilités postérieures : 

\-    La plupart des analyses sont de p(DIH)

**-**    Les p(HID) sont plus intéressantes [Qim Heart Issues Detector (Qim HID)](https://www.qiminfo.ch/les-projets-data-science-de-qim-info/)

**-**    **Utilisation du théorème de Bayes** 

Réplication des études :

\-    Exact vs conceptual replications 

\-    Combinaisons des résultats d’autres études 

\-    Meta-analyse d’après la méthode Bayesian

Cross validation : 

Les mêmes données pour entrainer et tester 

\- Leave-one-out (LOO)

\- Leave-p-out (LPO)

\- k-fold 

Conclusions: 

\-    Permet de faire une *Analysis count* 

\-    Checker la validité et la généralisation 

\-    Construire la confidence dans l’analyse et le modèle 


 

 