# Diabetes-Diagnosis-Project

### Problem Definition
1. What is Diabetes?

Diabetes is a chronic health condition that impacts the body's ability to convert food into energy. It involves difficulties in processing food into sugar and regulating its release into the bloodstream, predominantly managed by insulin. Diabetes manifests in three primary types: type 1, type 2, and gestational diabetes, each with distinct characteristics.

Type 1 Diabetes: Arises from an autoimmune reaction hindering insulin production, typically diagnosed in children and young adults.

Type 2 Diabetes: Involves insulin resistance, often diagnosed in adults, but increasingly seen in younger age groups.
Gestational Diabetes: Occurs during pregnancy and may pose health risks for both mother and baby. While diabetes has no cure, lifestyle adjustments like weight management, healthy eating, and physical activity significantly aid in its management and prevention.

### 1.2 What is Pima Indian Diabetes?

Pima Indian diabetes is prevalent among the Pima Native American population in Arizona and exhibits a significantly high incidence of type 2 diabetes. Understanding this condition offers unique insights into genetic and environmental factors contributing to the disease. Exploring this area aids in developing effective healthcare practices and prevention strategies, making it a crucial focus of medical investigation.
Dataset Details

The Pima Indians Diabetes Dataset aims to predict diabetes onset using diagnostic measures. This dataset, obtained from the National Institute of Diabetes and Digestive and Kidney Diseases, concentrates on female patients aged 21 or older with Pima Indian heritage. Its objective is to predict diabetes presence diagnostically based on specific diagnostic measurements selected from a larger database.
Attribute Information:

    Number of times pregnant
    Plasma glucose concentration 2 hours in an oral glucose tolerance test
    Diastolic blood pressure (mm Hg)
    Triceps skin fold thickness (mm)
    2-Hour serum insulin (mu U/ml)
    BMI (weight in kg/(height in m)^2)
    Diabetes pedigree function
    Age (years)
    Class variable (0 means non-diabetic, 1 means diabetic)

### Project Overview

This project focuses on diagnosing diabetes using eight features provided in the PIMA dataset. The project involves several stages:

    Data Analysis and Review: Comprehensively review statistical and descriptive information of the dataset.
    Data Management: Address missing values, duplicates, and outliers.
    Model Training: Employ machine learning classification models (Logistic Regression, Decision Trees, Neural Networks, XGBoost, KNN, Lightgbm) using techniques like GridSearchCV, RandomizedSearchCV, and Optuna.
    Model Selection and Evaluation: Choose the best model and thoroughly analyze and evaluate the final results.

This repository includes a Jupyter notebook containing detailed information on data preprocessing (handling missing values and outliers) and building machine learning models including hyperparameter tuning for machine learning classification models.
