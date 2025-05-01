# Classification du Risque de Crise Cardiaque – Mini-Projet Machine Learning

Ce mini-projet a pour objectif de développer et d’évaluer des modèles d’apprentissage automatique afin de prédire le risque de crise cardiaque à partir d’un jeu de données médicales (`heart.csv`). Il met en œuvre différentes étapes de prétraitement, d'entraînement de modèles, d’optimisation d’hyperparamètres et d’évaluation des performances.

## 📁 Jeu de données
Le jeu de données contient plusieurs indicateurs médicaux ainsi qu’une variable cible indiquant la présence ou non d’une maladie cardiaque.

## 🔧 Prétraitement
- **Chargement et exploration** : Analyse des premières lignes et détection des valeurs manquantes.
- **Encodage des variables catégorielles** : Encodage via `LabelEncoder`.
- **Normalisation** : Mise à l’échelle des variables numériques avec `StandardScaler`.
- **Division des données** : Séparation en ensemble d’entraînement (75 %) et de test (25 %).

## 🤖 Modèles utilisés
- **K-Plus Proches Voisins (KNN)** : Évaluation du F1-score pour k allant de 1 à 20.
- **Perceptron Multicouche (MLP)** : Une couche cachée de 100 neurones, 1000 itérations max.
- **Support Vector Machine (SVM)** : Test avec les noyaux `rbf`, `poly`, `sigmoid` et recherche des meilleurs hyperparamètres via `GridSearchCV`.

## 📊 Évaluation
- Affichage de la matrice de confusion
- Utilisation du F1-score comme métrique principale
- Le modèle SVM avec noyau RBF a donné les meilleurs résultats.

## 📌 Conclusion
Ce projet m’a permis d’approfondir ma compréhension des techniques de classification en machine learning, en soulignant l’importance du prétraitement, du choix des modèles et de la sélection des hyperparamètres. Le SVM s’est révélé particulièrement performant dans ce contexte médical.

---

**Auteur** : Omar Bouattour  
**Année universitaire** : 2024–2025
