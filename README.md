# FinSight — Financial Risk Intelligence System

## Overview

FinSight is a machine learning project that analyzes loan application data and predicts loan approval outcomes using Logistic Regression. It focuses on data preprocessing, feature engineering, and classification model evaluation.

## Dataset

- **Records:** 614 loan applications
- **Original Features:** 13 columns
- **Target Variable:** `Loan_Status`
- **Domain:** Financial Analytics

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Logistic Regression

## Project Workflow

1. Loaded and explored the loan application dataset.
2. Handled missing values using mode and median imputation.
3. Created a `TotalIncome` feature by combining applicant and co-applicant income.
4. Applied one-hot encoding to categorical variables.
5. Used `StandardScaler` for feature scaling.
6. Trained a Logistic Regression model with `max_iter=1000`.
7. Evaluated the model using test accuracy and a confusion matrix.

## Results

- **Test Accuracy:** 85.37%

The accuracy represents the result obtained on the project's test dataset.

## Key Learnings

- Data cleaning and preprocessing
- Handling missing values
- Feature engineering
- Categorical encoding and feature scaling
- Logistic Regression and model evaluation

## Future Improvements

- Evaluate precision, recall, and F1-score.
- Compare additional classification algorithms.
- Explore feature selection and model tuning.

## Author

**Kumkum Rathor**  
M.Sc. Applied Mathematics  
National Institute of Technology, Warangal
