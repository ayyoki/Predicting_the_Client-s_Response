# Predicting the Client's Response + EDA

## Overview
This project involves building a Supervised Machine Learning classification model to predict a customer's purchase decision based on various factors. It also includes an Exploratory Data Analysis (EDA) to understand the data better before applying the machine learning model.

### Development Environment
- **Platform**: Google Collaboratory

## Libraries Used
### Data Pre-Processing and Analysis
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- missingno
- imblearn (ADASYN)

### Model Training
- xgboost (XGBClassifier)

### Hyperparameter Tuning
- GridSearchCV

### Evaluation Metrics
- sklearn.metrics

## Introduction to the Dataset
- **Source**: Bank marketing Dataset available in the git folder as `bank-marketing.csv`.
- **Description**: The dataset includes banking data to facilitate a marketing campaign, focusing on how banks can target customers to maximize the product selling potential.
- **Size**: 45211 rows and 23 columns.

### Attribute Information
- **Age**: Customer's age.
- **Age Group**: Age group of the customer.
- **Eligibility**: Eligibility for the campaign.
- **Job**: Customer's occupation.
- **Salary**: Customer's salary.
- **Marital Status**: Marital status.
- **Education Level**: Highest level of education attained.
- **Marital-Education Status**: Combined marital status and education level.
- **Targeted**: If the customer is targeted by the campaign.
- **Default Status**: Default status of the customer.
- **Account Balance**: Account balance.
- **Housing Status**: Housing information.
- **Loan Status**: Loan information.
- **Contact Source**: Source of contact information.
- **Day & Month**: Date of contact.
- **Duration**: Duration of contact in days.
- **Campaign**: Campaign details.
- **Pdays**: Days since last contact.
- **Previous Response & POutcome**: Outcome of previous campaigns.
- **Y (Decision)**: Customer's decision (Yes/No).
- **Response**: Customer's response.

## Project Steps
1. Data Collection
2. Handling missing values (Remove, fill, NaN values)
3. Exploratory Data Analysis (EDA)
4. Feature Encoding
5. Feature Selection
6. Handling Imbalanced Classes
7. Model Building
8. Hyperparameter Tuning
9. Model Evaluation

## Results and Metrics
The model performance is summarized by the following metrics:
- **ROC-AUC**: 0.992
- **Accuracy**: 0.951
- **Class 0 Precision & Recall**: 0.95
- **Class 1 Precision & Recall**: 0.95
- **F1-Score**: 0.95
