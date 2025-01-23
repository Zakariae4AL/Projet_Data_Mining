# Projet Data Mining - Prédiction des Maladies Cardiaques

Bienvenue dans le projet de prédiction des maladies cardiaques. Ce projet utilise des techniques avancées de data mining et d'apprentissage automatique pour analyser des données cliniques et prédire la présence de maladies cardiaques.

## Contenu du dépôt

Ce dépôt contient les fichiers suivants :

### Rapport :
- **`Rapport_Analyse_Maladies_Cardiaques.pdf`** : Rapport détaillé expliquant les méthodes, les résultats, et les conclusions du projet.

### Données :
- **`heart_statlog_cleveland_hungary_final.csv`** : Jeu de données utilisé pour le projet. Il comprend des caractéristiques cliniques telles que l'âge, le sexe, le taux de cholestérol, etc.

### Documentation des données :
- **`documentation.pdf`** : Documentation décrivant chaque colonne du jeu de données, ses unités et sa signification.

### Scripts :
- **`datamining_heartdesease(1).py`** : Code Python contenant toutes les implémentations des méthodes utilisées (Recursive Feature Elimination, Firefly Algorithm, etc.).

### Notebook :
- **`DataMining_HeartDesease.ipynb`** : Notebook Jupyter interactif pour l'exploration des données, la visualisation, et l'exécution des méthodes de data mining.

## Méthodes utilisées

Le projet explore différentes approches pour la sélection des caractéristiques et l'entraînement des modèles :

- **Recursive Feature Elimination (RFE)** avec SVM, Firefly Algorithm et Naive Bayes.
- **Exhaustive Feature Selection** avec SVM, Firefly Algorithm et Naive Bayes.
- **Backward Selection** avec SVM, Firefly Algorithm et Naive Bayes.
- **Forward Selection** avec SVM, Firefly Algorithm et Naive Bayes.

## Meilleure méthode identifiée

La meilleure performance a été obtenue avec la méthode **Recursive Feature Elimination (RFE)** combinée avec l'algorithme **Firefly**, atteignant une précision de **92.16%**.

## Installation

1. Clone le dépôt sur ta machine locale :

```bash
git clone https://github.com/Zakariae4AL/Projet_Data_Mining.git
cd Projet_Data_Mining
```

2. Installe les dépendances nécessaires :

```bash
pip install -r requirements.txt
```

## Utilisation

1. **Exploration des données** : Consulte le fichier `data_description.txt` pour comprendre le jeu de données.
2. **Exécution des scripts** : Lance le script `datamining_heartdesease.py` pour exécuter les différentes méthodes et reproduire les résultats.
3. **Rapports** : Lis les fichiers Word pour des explications détaillées sur les méthodes et les résultats.

## Jeu de données

Le jeu de données utilisé est une combinaison des ensembles **Statlog**, **Cleveland**, et **Hungary**, largement utilisés pour des recherches dans le domaine de la santé.

### Colonnes principales

- **age** : Âge du patient.
- **sex** : Sexe du patient (1 = Homme, 0 = Femme).
- **chest pain type** : Type de douleur thoracique (valeurs catégoriques).
- **cholesterol** : Taux de cholestérol (mg/dL).
- **max heart rate** : Fréquence cardiaque maximale atteinte.
- **target** : Présence d'une maladie cardiaque (1 = Oui, 0 = Non).

Pour plus de détails, consulte le fichier `documentation.pdf`.

## Contributions

Les contributions sont les bienvenues ! Si tu souhaites contribuer à ce projet :

1. Fork ce dépôt.
2. Crée une branche pour ta fonctionnalité :

```bash
git checkout -b feature/nouvelle-fonctionnalite
```

3. Fais un commit de tes modifications :

```bash
git commit -m "Ajout d'une nouvelle fonctionnalité"
```

4. Pousse la branche sur ton fork :

```bash
git push origin feature/nouvelle-fonctionnalite
```

5. Ouvre une Pull Request.

## Licence

Ce projet est sous licence **MIT**. Consulte le fichier `LICENSE` pour plus d'informations.
