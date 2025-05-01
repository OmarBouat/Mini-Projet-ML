# Heart Disease Risk Classification - Mini ML Project

This mini-project focuses on building and evaluating machine learning models to classify the risk of heart disease using a medical dataset (`heart.csv`). The project demonstrates preprocessing techniques, model training, hyperparameter tuning, and performance evaluation.

## 📁 Dataset
The dataset contains various health metrics and the target variable indicating heart disease risk.

## 🔧 Preprocessing Steps
- **Loading & Exploration**: Inspection of dataset structure and null values.
- **Categorical Encoding**: Label encoding for categorical features.
- **Normalization**: Standard scaling of numerical features.
- **Train-Test Split**: 75% training, 25% testing.

## 🤖 Models Implemented
- **K-Nearest Neighbors (KNN)**: F1 score evaluated across k = 1 to 20.
- **Multilayer Perceptron (MLP)**: Single hidden layer (100 neurons), max iterations = 1000.
- **Support Vector Machine (SVM)**: Tested with kernels `rbf`, `poly`, `sigmoid` and hyperparameter tuning using `GridSearchCV`.

## 📊 Evaluation
- Confusion matrix visualization
- F1 Score as the main evaluation metric
- SVM with RBF kernel achieved the best results.

## 📌 Conclusion
This project deepened understanding of classification techniques and highlighted the importance of preprocessing and model selection. The SVM model proved particularly effective for this medical classification task.

---

**Author**: Omar Bouattour  
**Academic Year**: 2024–2025
