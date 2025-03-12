# Projet de Prédiction Météo Multivariée avec des Réseaux de Neurones Récurrents (RNN)

## Description du Projet

Ce projet vise à prédire les données météorologiques multivariées de Delhi en utilisant des modèles de réseaux de neurones récurrents (RNN), notamment des modèles LSTM, GRU et BiLSTM. Le projet est divisé en plusieurs étapes, allant de l'importation et le nettoyage des données à l'entraînement et l'évaluation des modèles.

### Objectifs
- Prédire les variables météorologiques telles que la température moyenne, l'humidité, la vitesse du vent et la pression moyenne.
- Comparer les performances des modèles LSTM, GRU et BiLSTM.
- Standardiser et prétraiter les données pour améliorer les performances des modèles.

## Structure du Projet

Le projet est structuré en plusieurs parties principales :

1. **Importation des Données** : Les données météorologiques quotidiennes de Delhi sont importées et nettoyées pour éliminer les valeurs aberrantes.
2. **Prétraitement des Données** : Les données sont divisées en ensembles d'entraînement et de test, puis standardisées.
3. **Création des Séquences** : Les données sont transformées en séquences pour être utilisées par les modèles RNN.
4. **Choix du Modèle** : Les modèles LSTM, GRU et BiLSTM sont implémentés et comparés. Mais le GRU a ete priorisé.
5. **Entraînement et Évaluation** : Les modèles sont entraînés sur les données d'entraînement et évalués sur les données de test.

## Technologies Utilisées

- **Python** : Langage de programmation principal.
- **Pandas** : Pour la manipulation des données.
- **NumPy** : Pour les calculs numériques.
- **Scikit-learn** : Pour la division des données et la normalisation.
- **TensorFlow/Keras** : Pour la création, l'entraînement et l'évaluation des modèles de réseaux de neurones.
- **Matplotlib** : Pour la visualisation des résultats.

## Instructions pour Exécuter le Projet

### Prérequis

- Python 3.x
- Les bibliothèques Python suivantes doivent être installées :
  ```bash
  pip install pandas numpy scikit-learn tensorflow matplotlib
bash```