# 🥗 Open Food Facts – Data Cleaning & Feasibility Study  
Data Scientist Training – OpenClassrooms  

## 🎯 Contexte du projet

L’agence **Santé Publique France** souhaite améliorer la qualité de la base de données Open Food Facts afin de faciliter la saisie des produits par les utilisateurs.

La base Open Food Facts contient :
- Informations générales sur les produits
- Tags (catégories, origine, localisation…)
- Ingrédients et additifs
- Informations nutritionnelles (valeurs pour 100g)

Cependant, de nombreuses erreurs de saisie et valeurs manquantes compliquent son exploitation.

L’objectif de cette mission était d’évaluer la **faisabilité d’un système de suggestion / auto-complétion** pour compléter certaines variables fortement incomplètes (> 50% de valeurs manquantes).

---

## 📊 Objectifs

- Nettoyer et explorer le jeu de données Open Food Facts
- Identifier les variables pertinentes
- Traiter les valeurs manquantes (au moins 3 méthodes adaptées)
- Détecter et corriger les valeurs aberrantes
- Automatiser les traitements pour garantir la robustesse du pipeline
- Réaliser des analyses univariées et multivariées
- Tester la significativité statistique des relations observées
- Conclure sur la faisabilité d’un système de suggestion
- Expliquer la conformité du projet aux principes du RGPD

---

## 🛠 Méthodologie

### 1️⃣ Nettoyage des données
- Sélection des variables pertinentes
- Analyse des taux de valeurs manquantes
- Traitement des données manquantes :
  - Suppression conditionnelle
  - Imputation statistique (moyenne / médiane)
  - Imputation basée sur corrélations
- Détection et traitement des valeurs aberrantes
- Automatisation des étapes de nettoyage

### 2️⃣ Analyse exploratoire
- Analyse univariée :
  - Histogrammes
  - Boxplots
  - Diagrammes circulaires
- Analyse multivariée :
  - Matrices de corrélation
  - Tests statistiques de significativité
  - Création / sélection de variables pertinentes

### 3️⃣ Étude de faisabilité
Analyse des relations entre variables nutritionnelles afin d’évaluer la possibilité de prédire ou suggérer certaines valeurs manquantes.

### 4️⃣ RGPD
Bien que les données ne contiennent pas d’informations personnelles :
- Minimisation des données
- Transparence
- Finalité explicite
- Sécurité des traitements
- Responsabilité

---

## 📈 Résultats

L’analyse met en évidence :
- Un taux élevé de valeurs manquantes sur certaines variables
- Des corrélations exploitables entre variables nutritionnelles
- La possibilité de construire un système de suggestion basé sur des relations statistiques

La faisabilité technique d’un système d’auto-complétion apparaît plausible sous certaines conditions de qualité des données.

---

## 📁 Contenu du repository

- 📓 Notebook final (.ipynb)
- 📊 Présentation du projet (.pptx)

---

## 🧰 Technologies utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## 👩‍💻 Auteur

Adriana TINT  
Data Scientist – OpenClassrooms  