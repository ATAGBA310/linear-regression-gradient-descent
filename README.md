# linear-regression-gradient-descent

Ce projet implémente un modèle de régression linéaire à partir de zéro, en utilisant la méthode de descente de gradient pour ajuster les paramètres. L'objectif est de prédire une variable en fonction d'une caractéristique, tout en optimisant l'erreur de prédiction. Le code est écrit en Python avec l'utilisation des bibliothèques **Numpy** et **Matplotlib**.

## Description du Projet

La régression linéaire est un algorithme de machine learning qui modélise la relation entre une variable cible et une ou plusieurs variables d'entrée. Ce projet implémente une régression linéaire simple (une seule variable d'entrée) en utilisant la **descente de gradient** pour optimiser le modèle.

- **Entrée** : Un jeu de données généré avec `sklearn.datasets.make_regression` (100 échantillons et 1 caractéristique).
- **Sortie** : Un modèle de régression linéaire ajusté avec les paramètres optimaux.
- **Algorithme utilisé** : Descente de gradient pour minimiser la fonction coût (erreur quadratique moyenne).
- **Outils utilisés** : 
  - Python
  - Numpy
  - Matplotlib

## Fonctionnalités

- Génération automatique de données pour la régression.
- Implémentation manuelle de la régression linéaire.
- Affichage de la courbe de régression et de la fonction coût au fil des itérations.
- Calcul du **coefficient de détermination (R²)** pour évaluer la performance du modèle.

## Comment exécuter le projet

1. **Clonez le dépôt** :
   ```bash
   git clone https://github.com/ATAGBA310/linear-regression-gradient-descent.git
