# Projet de Scoring en Machine Learning

## Description

Ce projet vise à développer un modèle de scoring pour évaluer la probabilité de défaut de paiement des clients d'une institution financière. Le modèle est entraîné sur un jeu de données de clients, contenant diverses informations sociodémographiques et financières. Le but est de prédire la probabilité de défaut de paiement (variable cible `TARGET`) à partir des caractéristiques fournies.

## Contenu du Projet

- **Exploration des Données** : Analyse des caractéristiques des données, traitement des valeurs manquantes, et visualisation de la distribution des variables.
- **Préparation des Données** : Nettoyage des données, encodage des variables catégorielles, et application de techniques de rééchantillonnage pour gérer le déséquilibre des classes.
- **Modélisation** : Entraînement de différents modèles de machine learning, évaluation de leurs performances, et sélection du modèle final.
- **Évaluation** : Analyse des performances du modèle à l'aide de métriques telles que l'AUC, la courbe ROC, et la matrice de confusion.
- **Interprétation** : Visualisation des features importances et des impacts des différentes variables sur la prédiction.

## Structure du Repository

- `TP_ML1.ipynb` : Le notebook Jupyter contenant tout le code pour l'exploration des données, la préparation, la modélisation, et l'évaluation.
- `data/` : Dossier contenant les fichiers de données utilisés dans ce projet (non inclus dans le repository).
- `README.md` : Ce fichier, fournissant un aperçu du projet et des instructions pour le reproduire.

## Prérequis

Assurez-vous que les packages suivants sont installés dans votre environnement Python :
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `imblearn`

Vous pouvez installer ces packages en utilisant pip :
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imblearn

Les données peuvent être téléchargées depuis Kaggle en suivant ce lien : [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk). Placez les fichiers application_train.csv et application_test.csv dans le dossier data/.
