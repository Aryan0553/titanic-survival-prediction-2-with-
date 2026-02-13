# Titanic Survival Prediction using Scikit-Learn Pipeline

## 📌 Project Overview
This project implements an end-to-end Machine Learning pipeline to predict passenger survival on the Titanic dataset. 
It demonstrates clean preprocessing, feature engineering, model training, evaluation, and validation using Scikit-learn best practices.

---

## 🧠 Key Concepts Used
- Train-Test Split
- ColumnTransformer
- Missing Value Imputation
- One-Hot Encoding
- Feature Scaling
- Feature Selection (Chi-Square)
- Decision Tree Classification
- Cross Validation
- Pipeline Architecture

---
## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🗂 Dataset
The dataset used is the **Titanic dataset**, containing passenger information such as:
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

Target Variable: **Survived**

---

## 🔄 Machine Learning Pipeline
1. Data Cleaning & Column Dropping  
2. Train-Test Split  
3. Age & Embarked Imputation  
4. One-Hot Encoding for Categorical Features  
5. Min-Max Scaling  
6. Feature Selection using Chi-Square  
7. Decision Tree Classifier  
8. Accuracy Evaluation & Cross Validation  

---

## 📈 Model Performance
- Test Accuracy: ~62.5%
- Cross-Validation Accuracy (5-fold): ~63.9%

---

## 🚀 How to Run
```bash
pip install pandas numpy scikit-learn
