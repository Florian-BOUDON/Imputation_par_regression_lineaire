# Imputation par régression linéaire

Ce projet de Machine Learning vise à créer un modèle d'imputation des données manquantes pour une seule variable en utilisant la méthode de régression linéaire.    
Nous remplacerons les données manquantes par les prédictions d'un modèle de régression linéaire entraîné sur les autres variables du jeu de données.     
La faisabilité de la régression linéaire sera validée en utilisant plusieurs mesures de performance telles que R2, la normalité des résidus, l'homoscédasticité, l'étude des points levier et la distance de Cook.       
Enfin, nous réaliserons une régression backward pour sélectionner les variables les plus pertinentes pour notre modèle d'imputation.

### Description du Projet
Les données fournies pour ce projet contiennent une variable avec des valeurs manquantes. Notre objectif est de créer un modèle d'imputation pour cette variable en utilisant les autres variables disponibles dans le jeu de données. Nous allons procéder en plusieurs étapes pour valider la faisabilité de la régression linéaire et sélectionner les variables pertinentes.

### Contenu du Projet
Le projet est structuré comme suit :

**Chargement et Exploration des Données :** Dans cette première étape, nous chargerons le jeu de données et effectuerons une analyse exploratoire pour identifier les variables avec des données manquantes et comprendre la distribution des variables.

**Prétraitement des Données :** Nous effectuerons des opérations de nettoyage et de prétraitement sur les données. Cela peut inclure la gestion des valeurs manquantes dans les autres variables et la préparation des données pour la régression linéaire.

**Modèle de Régression Linéaire multiple :** Nous entraînerons un modèle de régression linéaire en utilisant les autres variables pour prédire les valeurs manquantes de la variable cible.

**Validation du Modèle :** Nous évaluerons la faisabilité de la régression linéaire en utilisant plusieurs mesures de performance.       
- Le R2
- La normalité des résidus
- L'homoscédasticité de la variance
- Les points levier (identifier les observations influentes)
- La distance de Cook (identifier les observations influentes)

**Régression Backward :** Enfin, nous réaliserons une régression backward pour sélectionner les variables les plus pertinentes pour notre modèle d'imputation.

### Prérequis
Nous travaillons dans un environnement composé de:      
Python 3.x    
pandas      
numpy    
scikit-learn
matplotlib     
seaborn     
statsmodels      

### Structure des Fichiers

├── Regression_multiple.ipynb     
├── Billets_banque.csv     
└── README.md      

Le dossier "data" contient le fichier CSV du jeu de données avec la variable cible manquante.     
Le fichier Regression_multiple.ipynb est un cahier Jupyter contenant tout le code et les analyses du projet.       
Le fichier README.md est le présent document, fournissant une description détaillée du projet.      

### Conclusion
Ce projet de Machine Learning nous permettra de créer un modèle d'imputation des données manquantes pour une variable en utilisant la régression linéaire.     
En validant la faisabilité de la régression linéaire et en sélectionnant les variables pertinentes à l'aide de la régression backward, nous pourrons obtenir un modèle précis et fiable pour l'imputation des données manquantes dans le jeu de données.       

Ce projet fait partie de la formation data-analyst de Openclassrooms & ENSAE (certificat bac+4)
