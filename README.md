# Credit-Risk-prediction
A machine learning-based solution to predict loan repayment likelihood by analyzing applicant data. This project focuses on addressing class imbalance, optimizing model performance, and ensuring accurate and fair predictions for credit risk evaluation.

Key Features
1. Data Preprocessing
Mean Imputation: Handles missing values effectively.
Data Cleaning: Ensures consistency across datasets.
SMOTE (Synthetic Minority Over-sampling Technique): Addresses class imbalance, crucial for handling the disparity between likely defaulters and non-defaulters.
Easy Ensemble Method: Trains the model on multiple balanced subsets of data to improve robustness by combining weaker classifiers for better predictions.
2. Machine Learning Models
Evaluated Algorithms:
Logistic Regression
Decision Tree
Random Forest
XGBoost
Performance Metrics: Precision, recall, and overall accuracy are used to evaluate each model.
3. Best Performing Model
Random Forest was identified as the most effective model due to:
Exceptional accuracy on imbalanced data.
Ability to capture complex relationships in the dataset.
Balanced prediction metrics, making it ideal for deployment.
