# AIML-Task5-Decision-Trees-and-Random-Forests
# Decision Trees & Random Forests – Heart Disease Prediction

This project applies **Decision Tree** and **Random Forest** algorithms to predict the presence of heart disease using a classification dataset.

## 🎯 Objective

- Train and visualize decision tree models.
- Understand and control overfitting using tree depth.
- Compare performance between single trees and random forests.
- Evaluate models using accuracy and cross-validation.
- Interpret feature importance.

---

## 🧠 Dataset

- **Dataset:** Heart Disease UCI Dataset
- **Target variable:** `target` (0 = No heart disease, 1 = Heart disease)
- **Features:** age, sex, cp (chest pain), trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, etc.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Graphviz (optional, for tree visualization)

---

## ✅ Tasks Performed

### 1️⃣ Train a Decision Tree Classifier
- Used `DecisionTreeClassifier` from `sklearn.tree`
- Visualized the decision tree using `plot_tree`
- Explored decision paths and splits

### 2️⃣ Analyze Overfitting & Control Tree Depth
- Trained trees with/without `max_depth`
- Observed that deeper trees overfit training data

### 3️⃣ Train a Random Forest
- Used `RandomForestClassifier` from `sklearn.ensemble`
- Compared accuracy with the single decision tree
- Random forest gave **better generalization** and higher test accuracy

### 4️⃣ Interpret Feature Importances
- Extracted `.feature_importances_` from the random forest
- Visualized key features contributing to predictions

### 5️⃣ Evaluate Using Cross-Validation
- Applied `cross_val_score` for k-fold validation
- Computed mean accuracy and verified model stability

---
