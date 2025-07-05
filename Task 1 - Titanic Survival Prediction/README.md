# CODSOFT TASK 1 — Titanic Survival Prediction

## Project Overview

This project is a part of the CodSoft internship program. It involves building a machine learning model that predicts whether a passenger survived the Titanic disaster. The dataset is sourced from Kaggle and includes various passenger details such as age, gender, ticket class, fare, and embarkation port. The goal is to perform data preprocessing and apply a classification algorithm to make accurate survival predictions.

## Objective

To create a supervised machine learning model using logistic regression that can predict survival outcomes based on historical passenger data from the Titanic.

## Dataset

- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Features Used**:
  - `Pclass`: Ticket class
  - `Sex`: Gender
  - `Age`
  - `SibSp`: Number of siblings/spouses aboard
  - `Parch`: Number of parents/children aboard
  - `Fare`: Ticket fare
  - `Embarked`: Port of embarkation
- **Target Variable**:
  - `Survived`: 0 = Did not survive, 1 = Survived

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## Methodology

1. Load and explore the dataset
2. Handle missing values in `Age` and `Embarked`
3. Drop irrelevant columns (`Name`, `Ticket`, `Cabin`, `PassengerId`)
4. Encode categorical features (`Sex`, `Embarked`)
5. Feature scaling using `StandardScaler`
6. Train a Logistic Regression model with increased iterations (`max_iter`)
7. Evaluate the model using accuracy and classification metrics

## Results

The logistic regression model achieved a good level of accuracy after proper preprocessing and scaling. Feature scaling and increasing the number of iterations helped resolve convergence warnings and improved model performance.

## How to Use

1. Clone this repository  
2. Open the project in Jupyter Notebook or Google Colab  
3. Run the cells step by step to see preprocessing, training, and evaluation

## Google Colab Link

[Open in Google Colab] - https://colab.research.google.com/drive/1GZs2ZHIDkZomxgmkiiKRpuwdhiB55xGU?usp=sharing
