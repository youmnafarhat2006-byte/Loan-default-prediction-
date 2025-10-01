# Loan-default-prediction-
Project Overview

This project aims to predict which customers might default on their loans using machine learning. The goal is to help financial institutions identify high-risk borrowers and make informed lending decisions.

Key Features & Data

Data preprocessing: handled missing values, encoded categorical variables, and scaled numeric features.

Feature selection: used SelectKBest to identify top 20 features such as interest rate, debt-to-income ratio, credit scores, account activity, home ownership, and verification status.

Models Used

Gradient Boosting (best performer)

Random Forest

Logistic Regression

Evaluation Metrics

Accuracy

Precision

Recall

F1-score

ROC-AUC

Cross-validation: Stratified K-Fold

Results

Gradient Boosting achieved 91% accuracy and 78% recall, effectively identifying high-risk borrowers.

Tech Stack

Python

Pandas, NumPy, SciPy

Scikit-learn (pipelines, ensemble models, feature selection)

Conclusion

This project provided hands-on experience in data preprocessing, feature engineering, model building, and evaluating machine learning models on real-world financial datasets.
