# 🧠 Projet de Prédiction du Taux d'Attrition des Employés

![Python](https://img.shields.io/badge/python-3.8%2B-blue) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange) ![Licence: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Issues GitHub](https://img.shields.io/github/issues/Schadrac237/Projet-ML-pr-diction) ![Étoiles GitHub](https://img.shields.io/github/stars/Schadrac237/Projet-ML-pr-diction)

## 📌 Présentation du Projet

Ce projet a été réalisé dans le cadre d’un travail de groupe académique portant sur l’application des techniques de machine learning pour prédire le taux d’attrition des employés au sein d’une entreprise. La prédiction de l’attrition est une problématique clé en gestion des ressources humaines, car elle permet aux entreprises d’anticiper les départs potentiels, d’améliorer les stratégies de rétention et d’optimiser la planification des effectifs.

Le jeu de données fourni comprend diverses caractéristiques relatives aux employés, qui ont été utilisées pour entraîner des modèles prédictifs capables d’identifier les collaborateurs susceptibles de quitter l’entreprise. L’objectif principal était de construire, d’évaluer et de comparer plusieurs modèles de classification afin de sélectionner celui offrant la meilleure performance pour la prédiction.

## 🎯 Objectifs

Les objectifs principaux du projet étaient les suivants :

- Réaliser un prétraitement complet des données incluant le nettoyage, la gestion des valeurs manquantes et l’encodage des variables pour préparer le jeu de données à l’apprentissage automatique.
- Entraîner plusieurs modèles de machine learning, notamment Random Forest, Decision Tree, SVM, Régression Logistique, KNN et Perceptron.
- Évaluer la performance de chaque modèle en utilisant des métriques clés telles que la précision, le rappel, le score F1 et l’aire sous la courbe (AUC).
- Analyser les résultats afin d’identifier le modèle le plus performant.
- Explorer des pistes d’amélioration pour les modèles moins performants via l’ingénierie des caractéristiques ou l’optimisation des hyperparamètres.
- Fournir des recommandations exploitables pour faciliter la prise de décision RH à partir des prédictions générées.

## 🧭 Méthodologie et Approche

Le déroulement du projet s’est articulé autour des étapes suivantes :

1. **Nettoyage et Prétraitement des Données :**  
   Le jeu de données initial a été nettoyé afin de traiter les valeurs manquantes et d’éliminer les variables non pertinentes ou redondantes. Les variables catégorielles ont été encodées par des méthodes adaptées telles que l’encodage one-hot pour assurer la compatibilité avec les algorithmes de machine learning.

2. **Séparation du Jeu de Données :**  
   Les données préparées ont été divisées en ensembles d’entraînement et de test pour garantir une évaluation impartiale des performances des modèles.

3. **Développement des Modèles :**  
   Plusieurs algorithmes de classification ont été implémentés en Python dans un environnement Jupyter Notebook, en utilisant des bibliothèques reconnues comme pandas pour la manipulation des données, numpy pour les opérations numériques, matplotlib pour la visualisation et scikit-learn pour la construction et l’évaluation des modèles.

4. **Évaluation des Modèles :**  
   Chaque modèle a été évalué à l’aide de métriques essentielles telles que la précision, le rappel, le score F1 et l’AUC, afin de mesurer leur capacité à classer correctement les cas d’attrition.

5. **Analyse des Performances :**  
   Les méthodes d’ensemble telles que Random Forest et Decision Tree ont montré une performance exceptionnelle avec des scores très élevés, tandis que des modèles plus simples comme le Perceptron ont affiché des résultats plus modestes.

6. **Contribution et Collaboration :**  
   Ce projet a été réalisé en équipe. Mes contributions ont inclus l’entraînement et l’évaluation d’un modèle de machine learning, le nettoyage des données, ainsi que la gestion de la séparation des données en ensembles d’entraînement et de test. Une collaboration régulière a permis d’assurer la cohérence et d’optimiser les résultats.

## 🛠️ Technologies Utilisées

Le projet a utilisé les outils et bibliothèques suivants :

- Python version 3.8 ou supérieure pour le développement et l’analyse.
- Jupyter Notebook comme environnement interactif pour le développement et la documentation.
- pandas pour la manipulation efficace des données.
- numpy pour les calculs numériques et la gestion des tableaux.
- matplotlib pour la visualisation des données et des résultats.
- scikit-learn pour la construction, l’entraînement et l’évaluation des modèles de machine learning.

## 📊 Résultats

| Modèle             | Précision | Rappel | Score F1 | AUC    |
|--------------------|-----------|--------|----------|--------|
| Perceptron         | 0.35      | 0.14   | 0.20     | N/A    |
| Régression Logistique | 0.67    | 0.26   | 0.38     | 0.77   |
| SVM                | 0.88      | 0.43   | 0.57     | 0.89   |
| KNN                | 0.51      | 0.42   | 0.46     | 0.92   |
| Decision Tree      | 0.93      | 0.94   | 0.94     | 0.96   |
| Random Forest      | 0.98      | 0.96   | 0.97     | 1.00   |

Les modèles Random Forest et Decision Tree ont démontré une excellente précision prédictive, avec des scores AUC et F1 proches de la perfection, confirmant leur pertinence pour la tâche de prédiction d’attrition. Les modèles plus simples tels que le Perceptron ont des performances limitées, suggérant la nécessité d’optimisations supplémentaires.

## ⚙️ Utilisation du Dépôt

Ce dépôt contient l’ensemble du code source, incluant les étapes de prétraitement, les scripts d’entraînement et d’évaluation des modèles. Le jeu de données original est privé et n’est pas inclus pour des raisons de confidentialité.

