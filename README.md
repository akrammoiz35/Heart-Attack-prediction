Heart Disease Prediction Model using Machine Learning
Overview
This project focuses on building a Heart Disease Prediction Model using the widely recognized UCI Machine Learning Repository Heart Disease dataset. The dataset contains medical information collected from patients during heart disease trials at the Cleveland Clinic Foundation. The goal is to develop a machine learning model that predicts whether a patient is at risk of heart disease based on 14 clinical attributes.

By analyzing the dataset through Exploratory Data Analysis (EDA) and experimenting with various machine learning algorithms, we identify key factors contributing to heart disease and compare different models to select the one that provides the most accurate predictions.

Problem Statement
Heart disease is a leading cause of death worldwide, and early detection can significantly improve patient outcomes. The challenge is to create a machine learning model that can accurately predict the presence of heart disease based on medical attributes, allowing healthcare professionals to assess patient risks more effectively.

Dataset
The UCI Heart Disease dataset includes the following attributes:

Age
Sex
Chest pain type (cp)
Resting blood pressure (trestbps)
Serum cholesterol (chol)
Fasting blood sugar (fbs)
Resting electrocardiographic results (restecg)
Maximum heart rate achieved (thalach)
Exercise-induced angina (exang)
ST depression induced by exercise relative to rest (oldpeak)
Slope of the peak exercise ST segment (slope)
Number of major vessels colored by fluoroscopy (ca)
Thalassemia (thal)
Target (presence of heart disease: 1 for presence, 0 for absence)
Project Pipeline
The project is divided into several stages:

Exploratory Data Analysis (EDA):

Cleaning the dataset: Handling missing values and duplicates.
Visualizing the data: Analyzing distributions and relationships between variables.
Feature engineering: Creating new features and encoding categorical variables.
Data Preprocessing:

Normalization and scaling of numerical attributes.
Encoding categorical features such as chest pain type and thalassemia classification.
Splitting the dataset into training and test sets.
Model Building:

Logistic Regression
Decision Trees
Random Forest
Support Vector Machines (SVM)
Neural Networks
Model Evaluation:

Comparing models using metrics such as:
Accuracy
Precision
Recall
F1 Score
ROC-AUC Score
Selecting the Random Forest model based on superior performance across metrics.
Random Forest as the Best Performing Model
After evaluating the performance of various models, the Random Forest algorithm emerged as the most effective for predicting heart disease. Its ability to handle large feature spaces, manage both numerical and categorical data, and provide high accuracy made it the optimal choice.
