## Loan Approval Prediction

## Overview
This project showcases a machine learning pipeline to predict loan approval decisions based on applicant and loan details. The goal is to assist financial institutions in streamlining the loan application process and enhancing decision-making efficiency.

The dataset used for this project can be accessed directly from the following link:

https://raw.githubusercontent.com/no37no37/Loan_Approval_Prediction_ML_Model/refs/heads/main/loan_approval_dataset.csv


## Dataset
The dataset contains 4,269 entries and 13 features, including applicant demographics, financial information, and loan attributes. The target variable is loan_status, indicating whether a loan was "Approved" or "Rejected."

Key Features:

-**Applicant Details**: Number of dependents, education level, employment status.

-**Financial Information**: Income, loan amount, CIBIL score, and various asset values.

-**Loan Details**: Loan term and associated bank assets.

## Data Cleaning and Preprocessing

The following preprocessing steps were applied:

Removed leading/trailing spaces in column names.

Encoded categorical features (education, self_employed, and loan_status).

Verified and handled missing values (none found).

Scaled and split the data into training (75%) and testing (25%) sets.

## Exploratory Data Analysis (EDA)
EDA included visualizations to explore feature distributions and relationships with loan_status. Key insights:


Higher CIBIL scores are associated with higher approval rates.

Graduates tend to have higher approval rates compared to non-graduates.

The loan amount and income show variations based on loan status.


## Model Development
The project implemented the following models for classification:

-**K-Nearest Neighbors (KNN)**

-**Random Forest Classifier**


## Model Evaluation

Models were evaluated using accuracy, precision, recall, and F1-score. Key results include:

KNN: Achieved an accuracy of 55%.

Random Forest: Achieved the best performance with an accuracy of 98%.

## Results

The final model provides insights into the factors influencing loan approval decisions and can be used to automate the initial screening process for loan applications.

## Summary 

This project focuses on predicting loan approval by analyzing various factors such as an applicant’s financial history, income, credit score, employment status, and other relevant attributes. Using historical loan data and machine learning algorithms, a predictive model has been developed to assess the likelihood of loan approval for new applicants.

## Future Work

Implement advanced models like XGBoost or Neural Networks for enhanced accuracy.

Explore feature engineering to incorporate additional insights.

Deploy the model as a web service for real-time predictions.
