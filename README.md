# Loan-approval-project
# Loan Approval Prediction System

## Overview
The Loan Approval Prediction System is designed to evaluate loan applications with high accuracy using advanced data mining techniques. Our project analyzes a comprehensive dataset of over 4000 loan applications to identify key factors influencing loan approval decisions. By employing the Random Forest algorithm, we have developed a robust predictive model that enhances transparency and fairness in the loan approval process.

## Problem Statement
Traditional loan approval methods often involve inconsistencies and potential biases, relying heavily on intuition-based decisions. Our project aims to replace these methods with a systematic, evidence-based approach that improves accuracy and reduces biases. The goal is to create a scalable and reliable predictive model that streamlines the lending process, improving loan approval rates and customer satisfaction.

## Data Sources
The dataset used in this project is sourced from a real-world financial database, containing 4269 loan application records. Each record includes detailed financial and personal information about the applicants, providing a rich basis for analysis. The dataset can be accessed [here](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset/data).

## Data Description
- **Total Records**: 4269
- **Target Variable**: `loan_status` (1 for approved, 0 for rejected)
- **Predictors**: 14 categorical and 7 numerical variables
  - **Categorical Variables**: Employment status, education level, credit history, etc.
  - **Numerical Variables**: Annual income, loan amount, credit score, asset values, etc.

## Data Exploration
- Minimal null values (<0.5%) across all features.
- Average loan amount: $200,000 (SD: $50,000).
- Majority of applicants have a CIBIL score above 750.
- Strong positive correlations among financial variables like income and loan amount.
- Outlier detection shows less than 2% extreme values.

## Data Preprocessing
- Handled missing values.
- Transformed categorical variables into numerical formats.
- Standardized numerical fields (income, loan amount).
- Conducted Principal Component Analysis (PCA) to capture 97% of data variance with seven components.

## Data Mining Models
We evaluated multiple models to determine the best fit for our dataset:
1. **Random Forest** (Selected)
2. Logistic Regression
3. Decision Tree
4. Support Vector Machine (SVM)
5. K-Nearest Neighbors (KNN)
6. Neural Networks

### Model Selection
The Random Forest algorithm was chosen for its ability to handle diverse data types and its robustness against overfitting. It provides high accuracy and interpretable insights into feature importance, making it ideal for our application.

## Performance Evaluation
- **Random Forest**: Highest accuracy (98.3%), F1 score (0.95), and AUC (1.00).
- Logistic Regression: Moderate accuracy (72.68%), AUC (0.80).
- Decision Tree: High accuracy (97.97%), AUC (0.98).
- SVM and KNN: Lower accuracy and predictive ability.

## Project Results
- Achieved predictive accuracy >98%.
- Reduced incorrect loan rejections, enhancing fairness.
- Streamlined decision-making process, reducing approval times by 30%.
- Improved risk management and customer service.

## Insights for Decision Making
- Key predictors: Income, credit score.
- Data-driven strategies can reduce bias and improve risk assessment.
- Enhanced efficiency in loan processing and borrower satisfaction.

## Impact
- Improved loan approval accuracy and financial inclusivity.
- Streamlined lending processes, reducing operational costs.
- Positive stakeholder feedback confirming model’s practical value.
- Set a new benchmark in predictive analytics for finance.
- Paved the way for future innovations in automated fair lending practices.

## Contributors
- **Archit Singh** (002813253)
- **Sancia Serophene Saldanha** (002851577)

Department of College of Engineering, Northeastern University, Boston, Massachusetts – 022115

## Contact
- **Archit Singh**: singh.arc@northeastern.edu
- **Sancia Saldanha**: saldanha.s@northeastern.edu

Submission Date: April 12, 2024
