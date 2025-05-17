# 📊 Projet Machine Learning : Prédiction des Résultats de Match de Football


## 🎯 Objectif

Ce projet a pour but de prédire l’issue de matchs de football (victoire à domicile, victoire à l'extérieur ou match nul) à l’aide de techniques de machine learning supervisé.  
Nous avons utilisé les données de la compétition Kaggle ["Football: Who’s Gonna Win?"](https://www.kaggle.com/competitions/football-whos-gonna-win) pour entraîner et évaluer plusieurs modèles de classification.

---

## 📂 Données

Les données utilisées proviennent de statistiques de matchs (équipes, scores, performances passées, etc.). Un travail important de **prétraitement** et d’**exploration des données (EDA)** a été réalisé pour :

- Nettoyer les données manquantes
- Transformer les variables catégorielles
- Créer des features pertinentes pour la prédiction

---

## ⚙️ Méthodologie

Nous avons implémenté et comparé plusieurs modèles de classification pour identifier celui offrant les meilleures performances :

- 🌲 Random Forest  
- 🌳 Decision Tree  
- ⚡ XGBoost  
- 🌟 LightGBM

L’évaluation a été faite à l’aide de **matrices de confusion**, **précision**, **rappel** et **F1-score**.

---

## 🧪 Résultats

Les modèles XGBoost et LightGBM ont donné les meilleurs résultats en termes de **précision globale** et de **capacité de généralisation** sur des données de test.

---

## 📌 À venir / pistes d’amélioration

- Prise en compte des cotes de paris pour enrichir les données
- Utilisation d’ensembles de modèles (stacking, voting)
- Intégration d’un pipeline automatisé de preprocessing + entraînement

---

## 🧠 Outils et technologies

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost, LightGBM
- Jupyter Notebook
- Matplotlib / Seaborn



