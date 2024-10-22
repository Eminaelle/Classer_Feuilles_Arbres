# Classification des Feuilles d'Arbre

**Lien du projet GitHub :** [Classer_Feuilles_Arbres](https://github.com/Eminaelle/Classer_Feuilles_Arbres.git)

## Description

Ce projet vise à développer un modèle de machine learning pour classifier les feuilles d'arbres en fonction de leurs caractéristiques de marges et de textures. L’objectif principal est de trouver les meilleurs hyperparamètres pour améliorer la précision du modèle.

Nous avons utilisé **K-Nearest Neighbors (KNN)** comme modèle de référence (*baseline*), et un **Support Vector Machine (SVM)** pour améliorer les résultats après réglage des hyperparamètres.

## Objectifs

- **Exploration des performances** du modèle de base (KNN) sans réglage d’hyperparamètres.
- **Optimisation des hyperparamètres** pour le modèle SVM afin d'obtenir de meilleures performances.

## Résultats

- **KNN (modèle baseline)** :
  - **Précision (accuracy)** : ~0
  - **Log Loss** : 34.54
  
- **SVM avant réglage des hyperparamètres** :
  - **Précision (accuracy)** : 0.83 
  
- **SVM après réglage des hyperparamètres** :
  - **Précision (accuracy)** : 0.93 

## Structure du Projet

- **00-eda.ipynb** : Contient l'exploration des données et l'analyse descriptive.
- **01-modelisation.ipynb** : Contient la modélisation avec KNN (baseline) et SVM, ainsi que les ajustements des hyperparamètres.

## Dépendances

Le projet utilise les bibliothèques suivantes :

pandas==1.5.3
numpy==1.23.5
matplotlib==3.6.2
seaborn==0.12.1
scikit-learn==1.2.0


Pour installer les dépendances, exécutez la commande suivante :

```bash
pip install -r requirements.txt
```

## Données

Les données se trouvent dans le répertoire `data/.` Ce projet utilise des caractéristiques texturales et de marges de feuilles pour entraîner et tester les modèles.

## Utilisation

1. Cloner le projet :

```bash
git clone https://github.com/Eminaelle/Classer_Feuilles_Arbres.git
```

2. Naviguer dans le dossier :

```bash
    cd Classer_Feuilles_Arbres
```
3. Exécuter les notebooks pour reproduire les résultats.

## Licence

Ce projet est sous licence MIT.