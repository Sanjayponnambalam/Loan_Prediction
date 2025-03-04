# Loan Amount Prediction

## Overview
The Loan Amount Prediction project aims to develop a predictive model to assess loan eligibility based on various applicant details. Using machine learning techniques, this model helps financial institutions make data-driven decisions on loan approvals.

## Key Features
- Predicts loan approval status based on applicant attributes.
- Utilizes data preprocessing and feature engineering for better model accuracy.
- Implements machine learning algorithms for loan status classification.
- Handles missing data and extreme values effectively using transformations.
- Provides insights into factors that influence loan approval decisions.

## Dataset
The dataset consists of multiple applicant-related variables:

| Variable            | Description                                      |
|-------------------- |------------------------------------------------ |
| Loan_ID            | Unique Loan ID                                  |
| Gender             | Male/ Female                                    |
| Married            | Applicant married (Y/N)                         |
| Dependents         | Number of dependents                            |
| Education          | Applicant Education (Graduate/ Under Graduate)  |
| Self_Employed      | Self employed (Y/N)                             |
| ApplicantIncome    | Applicant income                                |
| CoapplicantIncome  | Coapplicant income                              |
| LoanAmount         | Loan amount in thousands                        |
| Loan_Amount_Term   | Term of loan in months                          |
| Credit_History     | Credit history meets guidelines                 |
| Property_Area      | Urban/ Semi Urban/ Rural                        |
| Loan_Status        | Loan approved (Y/N)                             |

### Observations:
- Applicants with a credit history have a higher chance of loan approval.
- Higher applicant and co-applicant incomes increase approval likelihood.
- Higher education levels positively impact loan approval.
- Properties in urban areas with high growth potential are favored.

## Workflow Overview
1. **Understanding the Dataset**
   - Understanding various features (columns) of the dataset.
   - Understanding the distribution of categorical variables.
   - Identifying outliers in LoanAmount and ApplicantIncome.
   
2. **Data Preprocessing**
   - Handling missing values.
   - Encoding categorical variables.
   - Transforming skewed data (log transformation on extreme values).
   
3. **Exploratory Data Analysis (EDA)**
   - Understanding data distribution.
   - Identifying key factors influencing loan approval.
   
4. **Feature Engineering**
   - Creating new meaningful features.
   - Normalizing numerical values.
   
5. **Model Building**
   - Training machine learning model: Logistic Regression.
   - Using key features: 'Credit_History', 'Education', and 'Gender'.
   - Hyperparameter tuning for optimization.
   
6. **Model Evaluation**
   - Assessing performance using metrics such as accuracy, precision, recall, and F1-score.
   
7. **Prediction & Deployment**
   - Using the trained model to predict loan approvals.
   - Deploying the model for real-time loan eligibility assessments.

## Model Performance
- The best-performing model achieved an accuracy of **80.45%**.
- **Credit history** was found to be a significant predictor, with 79.58% of approved applicants having a credit history.
- Log transformations improved model stability by reducing the impact of extreme values.

This project provides a data-driven approach to loan amount prediction, helping financial institutions make informed lending decisions.

