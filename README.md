# 🌳 Decision Trees & Random Forests – Heart Disease Dataset

## 🎯 Objective

This project focuses on building and evaluating tree-based models — **Decision Trees** and **Random Forests** — to classify the presence of heart disease using a medical dataset. The workflow demonstrates model training, tuning, visualization, and performance evaluation.

---

## 🔄 Workflow Steps

### 1. 📥 Load and Explore the Dataset
The heart disease dataset was loaded using pandas. Basic EDA was performed to understand the structure and distribution of features.

### 2. 🌲 Train a Decision Tree Classifier
A Decision Tree was trained using `DecisionTreeClassifier` from Scikit-learn. The tree structure was visualized using `plot_tree`.

### 3. 📉 Analyze Overfitting & Control Tree Depth
To address overfitting, a pruned version of the tree with `max_depth` was tested and compared against the full-depth tree based on test accuracy.

### 4. 🌲🌲 Train a Random Forest Classifier
A `RandomForestClassifier` was used to improve accuracy through ensemble learning. Performance was compared to the decision tree model.

### 5. 📊 Interpret Feature Importances
Feature importances from the Random Forest were extracted and visualized to understand which factors most influenced predictions.

### 6. 📈 Evaluate Using Cross-Validation
Both models were evaluated using 5-fold cross-validation to assess their generalization ability.

---

## ✅ Output

- Decision tree visualization
- Accuracy scores (full tree, pruned tree, random forest)
- Feature importance chart
- Cross-validation results

---

## 📚 Requirements

- Python  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  

---

## 📁 Dataset

The **Heart Disease dataset** includes features such as age, sex, cholesterol level, blood pressure, and chest pain type, with a binary target indicating the presence or absence of heart disease.

---
