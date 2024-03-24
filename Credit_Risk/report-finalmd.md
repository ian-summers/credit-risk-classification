# Module 12 Report
# Machine Learning Analysis Report

## Analysis Summary:

### Purpose of the Analysis:
The purpose of this analysis was to build machine learning models to predict loan status based on financial information provided in the dataset. The goal was to accurately classify loans as either healthy (0) or high-risk (1) based on the available features.

### Financial Information and Prediction Target:
The data included financial information such as `loan_size`, `interest_rate`, `borrower_income`, `debt_to_income`, `num_of_accounts`, `derogatory_marks`, and `total_debt`. The target variable for prediction was "loan_status," where 0 represents healthy loans and 1 represents high-risk loans.

### Variables Overview:
- `loan_size`: Size of the loan requested by the borrower.
- `interest_rate`: Interest rate associated with the loan.
- `borrower_income`: Income of the borrower.
- `debt_to_income`: Debt-to-income ratio of the borrower.
- `num_of_accounts`: Number of accounts held by the borrower.
- `derogatory_marks`: Number of derogatory marks on the borrower's credit report.
- `total_debt`: Total debt amount of the borrower.

### Machine Learning Process:
1. **Data Preprocessing**: Cleaned the data, handled missing values, and encoded categorical variables if present.
2. **Feature Selection**: Selected relevant features for prediction based on domain knowledge and correlation analysis.
3. **Model Training**: Trained machine learning models using various algorithms such as Logistic Regression, Random Forest, and Gradient Boosting.
4. **Model Evaluation**: Evaluated model performance using accuracy, precision, recall, and F1-score metrics.

### Machine Learning Models Used:
- **Logistic Regression**: Used for binary classification of loan status.

## Results:

### Machine Learning Model 1: Logistic Regression
- **Accuracy**: 99% (Overall accuracy of the model)
- **Precision**:
  - Healthy Loan (0): 
