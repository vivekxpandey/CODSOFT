# CODSOFT TASK 5 — Credit Card Fraud Detection

## 📌 Project Overview
This project is part of the **CodSoft Internship Program** and involves building a machine learning model to detect fraudulent credit card transactions. The dataset contains anonymized features derived from PCA, including transaction amount and time.

The goal is to accurately classify transactions as fraudulent or genuine, helping financial institutions prevent fraud using data-driven methods.

## 🎯 Objective
To develop a supervised classification model that identifies fraudulent transactions in imbalanced datasets using robust machine learning techniques.

## 📊 Dataset
**Source:** Credit Card Fraud Detection - [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

**Features Used:**
- V1 to V28 (anonymized numerical features)
- NormalizedAmount (scaled transaction amount)

**Target:**
- `Class` → 0 = Genuine, 1 = Fraudulent

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost, LightGBM
- SMOTE (for class balancing)
- Google Colab

## 🚀 Methodology
- Load and preprocess the dataset
- Normalize transaction amounts
- Handle severe class imbalance using SMOTE
- Train multiple classification models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - LightGBM
- Evaluate models using metrics like:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Visualize:
  - ROC Curve
  - Precision-Recall Curve
  - Confusion Matrix
  - Feature Importances
  - Distribution analysis and pairplots for top features

## 📈 Results
All four models performed well after balancing the dataset. XGBoost and LightGBM showed strong F1-scores and precision, especially effective at identifying fraud cases with minimal false positives. Visualizations provided deep insight into feature behaviors and class separations.

## ▶️ How to Use
- Clone this repository
- Open the notebook in Google Colab
- Upload the `creditcard.csv` dataset to your environment
- Run all cells for preprocessing, training, and evaluation

## 🔗 Google Colab Link - https://colab.research.google.com/drive/180viZX2fq5Co4yq7iTtwPBOUnIbeef-T?usp=sharing
