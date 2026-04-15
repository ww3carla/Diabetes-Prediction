# Diabetes Prediction Project

## Overview

This project focuses on predicting whether a patient has diabetes based on medical data using machine learning techniques.

The dataset used is the Pima Indians Diabetes dataset, which contains several health-related features such as glucose level, BMI, blood pressure, and age.

---

## Objectives

- Perform exploratory data analysis (EDA)
- Clean and preprocess the dataset
- Compare multiple machine learning models
- Select the best-performing model
- Evaluate the final model using appropriate metrics

---

## Dataset

The dataset contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target variable:
- `Outcome` (0 = no diabetes, 1 = diabetes)

---

## Workflow

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Visualization of features
   - Correlation analysis

2. **Data Cleaning**
   - Detection of invalid zero values
   - Replacement with missing values (NaN)
   - Median imputation

3. **Modeling**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)

4. **Model Evaluation**
   - Cross-validation (5-fold)
   - F1-score used as main metric
   - Confusion matrix and classification report

---

## Results

- Logistic Regression achieved the best performance based on the F1-score.
- Simpler models performed comparably or better than more complex ones.
- Glucose was identified as the most important feature for prediction.

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---
