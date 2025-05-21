# Auto_Loan_Credit_Decisioning_Model
 Development of a credit decisioning model for auto loan applications using historical applicant data

## Objectives

1. Conduct exploratory data analysis (EDA) and preprocessing.
2. Train and evaluate a Logistic Regression (LR) model.
3. Develop and compare Machine Learning models: Decision Trees and Random Forests.
4. Recommend the best model for business use based on performance and interpretability.
5. Evaluate fairness by gender and race and use LIME for explainability.

## Dataset

- `training_data.csv`: Includes historical application outcomes with the target variable `bad_flag`.
- `evaluation_data.csv`: Unlabeled dataset for generating approval predictions.

## Model Highlights

- Logistic Regression with class balancing performed best (AUC = 0.796).
- SMOTE was applied to address class imbalance.
- LIME was used for individual prediction explanations.
- Approval rates by demographic groups were evaluated to assess fairness.

## Report

See the uploaded pdf report for the full technical write-up.


