# Heart Attack Prediction Using CRISP-DM Methodology

## Overview

This project focuses on predicting the risk of heart attacks using the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology. The dataset used contains various medical attributes that are indicative of cardiovascular health. The goal is to develop a predictive model that can accurately identify individuals at risk of having a heart attack.

## CRISP-DM Methodology

The CRISP-DM methodology is a robust and reliable data mining process that involves six key phases:

1. **Business Understanding:** 
   - Define the project objectives and requirements from a business perspective. 
   - For this project, the goal is to predict the likelihood of a heart attack based on medical data to enable early intervention and reduce mortality rates.

2. **Data Understanding:**
   - Gather initial data and familiarize yourself with it.
   - This includes understanding the structure, exploring the data's properties, and identifying any data quality issues.
   - For this project, the dataset includes features such as age, sex, cholesterol levels, blood pressure, and other health indicators.

3. **Data Preparation:**
   - Process and clean the data to make it suitable for modeling.
   - This includes handling missing values, normalizing data, feature selection, and creating training and test datasets.

4. **Modeling:**
   - Select and apply various modeling techniques.
   - This project explores different machine learning models such as Logistic Regression, Random Forest, and Support Vector Machines to predict heart attack risk.
   - Use hyperparameter tuning to optimize model performance.

5. **Evaluation:**
   - Evaluate the models to ensure they meet the business objectives.
   - Use performance metrics like accuracy, precision, recall, F1-score, and AUC-ROC curve to assess model effectiveness.
   - Select the best model based on evaluation results.

6. **Deployment:**
   - Deploy the model into a production environment where it can be used to make predictions on new data.
   - For this project, deployment might involve creating a web service or application where healthcare professionals can input patient data and receive risk assessments.

### Prerequisites

- Python 3.x
- Pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
