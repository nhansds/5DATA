## Choosing Metrics

> Bien choisir ses indicateurs et ses mesures de succès

Les data sciences sont goal-directed

Data sciences sont action-oriented

- Le but est de faire quelque chose

Les data sciences doivent être explicite (can guide effort)

Cela peut être bénéfique pour les clients, cela prévient la frustration de la part du client. Cela améliore l'utilisation de son temps.

Businness metrics :

- Key Performances Indicators KPI

  - Non financier
  - Régulier dans le temps
  - CEO Focus
  - Simple
  - Team based
  - Significant impact

- SMART Goals

  - Specific
  - Mesurable
  - Assignable
  - Realistic
  - Time-bound

- Classification accuracy

- ![](D:\Msc2\5DATA - Data Engineer\Data Science Foundations - Fundamentals\screens\metrics.png)

  - Sensivity
  - Specificity
  - Positive predictive value PPV
  - Negative predictive value NPV

  Conclusion

  - Measurement boosts awareness
  - Awareness contributes to quality
  - You should measure thoughtfully and sensitively


## Existing Data Sets

3 Types :

- In-house data
- Open data
- Third-party data

In-house data (dans l'organisation)

- +
  - Rapide et simple
  - Format standardisé
  - Bien documenté
  - Original team identifiers
- -
  - Données inexistantes
  - La documentation peut être inadéquate
  - Quality reliability

Open data (disponible librement)

- Gouvernement
- Organisation
- Certaines entreprises
- Données scientifiques



- +
  - Data sets très gros (plusieurs TB)
  - Portée (historique, géographique...)
  - Bien formatté
  - Bien documenté
- -
  - Echantillons biaisés
  - Signification pas claire
  - Obligation de partager
  - Pas de privacy ni de confidentialité

Third-party data ou data as a service (DaaS)

- Data brokers
- Process data

+ ++
  + Save time and effort
  + Individual-level data
  + Summaries and inferences
+ --
  + Expensive
  + Requires
  + Distasteful

## APIs

Application Programming Interfarce

Permet aux programmes de discuter

Permet aux programmes d'accèder à des données en ligne

REST API Reprensentational State Transfer --> JSON

Language agnostic

Social APIs (FB, Twitter, Soundcloud)

Visual API (Maps, YouTube, Flickr)

API

- Données Web Structurés
- Données directement dans un programme
- Un des meilleurs outils pour les data sciences

## Scraping Data

Toutes les données n'arrivent pas en JSON, ne sont pas formattés pour les manipuler.

HTML Text ou Tables ; PDFs : Media ; Word ; PPT...

Attention aux problèmes de copyright et de confidentialité

Outils prêt à l'utilisation :

- import.io
- ScraperWiki
- Tabula
- GoogleSheets (=IMPORTHTML_)
- Excel

Outils personnalisés :

- R
- Python
- Bash
- Java
- PHP

## Creating data

Questions à se poser quand on doit créer soi même ses données : 

- The level of intervention
  - Is it observational ?
  - Is it experimental ?
- Quel type de données ?
  - Données quantitatives
  - Données numériques
  - Données qualitatives (textes nécessitant une analyse par ex)
- Localisation
  - En ligne ?

Toutes ces questions doivent être posées avant de commencer la récolte de données.

Plusieurs méthodes pour récolter des données :

- Entretiens
  - Nouveaux sujets et nouvelles audiences
  - Structuré ou non
  - Consomme du temps
  - Cela peut demander un certain entrainement / des connaissances sur le sujet
- Sondages
  - Questions ouvertes ou fermées
  - Facilité pour administrer en ligne
  - Attentions aux biais (échantillon faible par exemple)
- Cart sorting
  - Classement de sujets
  - Détermine des catégories et des hiérarchies
  - Vérifier la facilité d'utilisation d'un site internet
- Expérimentations
  - Mettre des personnes dans des situations différentes
  - Meilleure méthode pour des données "de cause à effet"
  - Demande beaucoup de travail et de connaissances/méthodes

Conclusion

- Il faut obtenir exactement les données que l'on veut
- Peut demander beaucoup de connaissances / d'entrainement
- Attention aux problèmes éthiques

