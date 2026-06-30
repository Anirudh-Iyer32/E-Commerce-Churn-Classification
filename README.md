# E-Commerce Customer Churn Prediction

## Overview

This project builds and evaluates machine learning models to predict customer churn in an e-commerce environment. The objective is to identify customers who are likely to stop engaging with the platform, enabling businesses to take proactive retention strategies.

The project covers the complete machine learning lifecycle—from data preprocessing and exploratory data analysis (EDA) to feature engineering, model training, optimization, evaluation, and feature selection. Deployment and automated model retraining are outside the scope of this project.

---

## Project Objectives

* Analyze customer demographics and purchasing behavior.
* Predict customer churn using ensemble machine learning models.
* Compare the performance of multiple algorithms.
* Address class imbalance while preventing data leakage.
* Optimize model performance through Bayesian hyperparameter tuning.
* Select the most informative features using Recursive Feature Elimination (RFE).

---

## Machine Learning Pipeline

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering and encoding
* Train-test split
* **Class imbalance handling using SMOTE-Tomek (applied only to the training dataset to prevent data leakage)**
* Model training
* Hyperparameter optimization using Bayesian Optimization
* Feature selection using Recursive Feature Elimination (RFE)
* Model evaluation and comparison

---

## Models Implemented

* Random Forest
* XGBoost
* LightGBM

---

## Model Evaluation

Each model was evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score

Performance was further analyzed using:

* Confusion Matrix
* ROC Curve
* Precision-Recall Curve

---

## Feature Selection

Recursive Feature Elimination (RFE) was used to identify the most relevant features, improving model interpretability while reducing unnecessary complexity.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE-Tomek)
* XGBoost
* LightGBM
* Matplotlib
* Seaborn
* Bayesian Optimization

---

## Future Improvements

* Deploy the best-performing model as a REST API.
* Develop an interactive web application.
* Implement automated retraining pipelines.
* Add model monitoring and data drift detection.
* Containerize the application using Docker.
* Deploy using cloud platforms such as AWS SageMaker.
