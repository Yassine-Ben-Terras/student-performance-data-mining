#  Student Performance Data Mining & Prediction

##  Description du Projet
Ce projet de Data Mining a pour objectif d'analyser et de prédire les performances académiques des étudiants à partir d'un jeu de données comprenant 25 000 observations et 16 variables. L'étude couvre l'ensemble du cycle de vie de la donnée : de l'analyse exploratoire (EDA) à la modélisation prédictive en passant par l'analyse multivariée.

##  Fonctionnalités et Démarche
- **Analyse Exploratoire des Données (EDA) :** Étude univariée et bivariée pour comprendre la distribution des notes et l'impact des variables catégorielles (méthode d'étude, type d'école, etc.).
- **Analyse Multivariée :** Mise en évidence des corrélations (ex: forte corrélation entre les heures d'étude et le score global) et réduction de dimensionnalité via l'Analyse en Composantes Principales (ACP).
- **Modélisation Prédictive :** Entraînement et comparaison d'algorithmes de Machine Learning pour prédire la réussite des étudiants.
  - *Arbre de Décision (Decision Tree)*
  - *Forêt Aléatoire (Random Forest)* - Modèle retenu avec une précision d'environ 75%.

##  Principaux Résultats
- **Facteurs influents :** Les heures d'étude et les scores par matière (Mathématiques, Sciences, Anglais) sont les indicateurs les plus fiables de la réussite globale.
- **Règle d'association :** Un faible temps d'étude combiné à une assiduité moyenne conduit systématiquement à une performance faible (Lift = 3.14).
- **Fiabilité :** L'Alpha de Cronbach calculé démontre une excellente cohérence interne des données.

##  Technologies et Bibliothèques Utilisées
- **Langage :** Python 3
- **Manipulation de données :** Pandas, NumPy
- **Visualisation :** Matplotlib, Seaborn
- **Machine Learning :** Scikit-Learn

