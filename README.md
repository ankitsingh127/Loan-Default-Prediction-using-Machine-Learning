# Loan-Default-Prediction-using-Machine-Learning

📘 Project Overview

This project aims to predict the likelihood of loan default based on applicant financial and demographic data.
Using machine learning algorithms, the project helps financial institutions identify high-risk applicants and make data-driven lending decisions.

🎯 Objectives

Analyze and preprocess loan application data

Build and compare machine learning models for loan default classification

Evaluate models using key performance metrics

Visualize model insights and performance metrics interactively

🧩 Key Components
1. Data Preparation

Imported and explored dataset (loan_data.csv or synthetic data if missing)

Handled missing values, outliers, and categorical encoding

Applied feature scaling using StandardScaler

Split data into training and testing sets (80–20 split)

2. Feature Engineering

Encoded categorical features using OneHotEncoder

Created pipelines for reproducible transformations

Selected key predictors such as:

Loan Amount

Applicant Income

Credit Score

Employment Type

Education Level

Property Area

3. Model Development

Implemented and compared multiple models:

Logistic Regression

Random Forest Classifier

Each model was evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC-AUC

4. Model Evaluation

Used metrics and visualizations to assess performance:

Confusion Matrix

ROC Curve

Feature Importance plots

Classification Report

📈 Model Performance
Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	0.86	0.82	0.78	0.80	0.88
Random Forest Classifier	0.91	0.89	0.85	0.87	0.93

✅ Best Model: Random Forest Classifier
💡 Final Accuracy: ~91%

🛠️ Tools & Libraries

Python: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

ML Models: Logistic Regression, Random Forest

Model Persistence: joblib

IDE: Jupyter Notebook / Google Colab

📊 Results & Insights

Credit score, income, and loan amount were the strongest predictors of default.

Random Forest outperformed Logistic Regression with higher recall (better at catching defaulters).

Interactive visualizations helped interpret feature importance and model behavior.


🧠 Future Improvements

Include XGBoost and CatBoost for better performance

Perform hyperparameter tuning using GridSearchCV

Build a Flask web app for real-time prediction deployment
