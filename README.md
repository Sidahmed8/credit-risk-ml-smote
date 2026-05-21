# Credit Risk Classification with SMOTE and Model Optimization

## Project Overview

This project focuses on predicting credit risk using supervised machine learning models.

The main goal is to classify clients as good or bad credit risks based on socio-demographic, financial and behavioral characteristics. The project also addresses the class imbalance problem using SMOTE and compares several supervised learning models.

---

## Business Problem

In the banking sector, credit risk assessment is essential to reduce payment defaults while keeping the credit approval process reliable and fair.

The main question is:

> How can we build a predictive model that classifies clients into good or bad credit risk while handling class imbalance and optimizing model performance?

---

## Objective

The objective of this project is to:

- Perform exploratory data analysis
- Prepare and clean the dataset
- Handle class imbalance using SMOTE
- Train and compare supervised machine learning models
- Evaluate models using Precision, Recall and F1-score
- Identify the best compromise between performance, interpretability and robustness

---

## Machine Learning Models

The project compares three supervised learning models:

- Logistic Regression
- Decision Tree
- Random Forest

---

## Methodology

The project follows this pipeline:

```text
Raw Data
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train/Test Split
   ↓
SMOTE Balancing
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Model Comparison

## Technologies Used
Python
Pandas
NumPy
Scikit-learn
Imbalanced-learn / SMOTE
Matplotlib
Seaborn
Google Colab
Evaluation Metrics

##The models are evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion Matrix
Notebook

The full notebook is available here:

credit_risk_classification_smote.ipynb
