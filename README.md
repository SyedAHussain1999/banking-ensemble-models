# Bank Term Deposit Prediction Using Ensemble Learning

## Project Overview
This project focuses on predicting whether a customer will subscribe to a term deposit product using a real-world Portuguese banking dataset. The objective is to compare standard machine learning classifiers with ensemble methods to determine the most accurate and business-relevant predictive approach.

## Process Summary

### 1. Data Preprocessing
- Cleaned and transformed the dataset.
- Applied one-hot encoding and standard scaling for model compatibility.
- Ensured robust feature engineering for accurate model input.

### 2. Baseline Modeling
- Built and tuned Logistic Regression and K-Nearest Neighbors classifiers.
- Used GridSearchCV for hyperparameter tuning.
- Evaluated performance using accuracy and classification reports.

### 3. Ensemble Learning Models
- Implemented and compared four ensemble classifiers:
  - Random Forest
  - AdaBoost
  - Bagging Classifier
  - Voting Classifier (hard and soft voting)
- Tuned each model with GridSearchCV and evaluated using standard metrics.

### 4. Evaluation and Comparison
- Compared baseline and ensemble models using consistent evaluation metrics.
- Generated classification reports and confusion matrices for interpretability.

## Key Findings
- Ensemble models outperformed individual baseline classifiers.
- The Voting Classifier with soft voting delivered the best overall results.
- Ensemble learning proved effective for improving predictive accuracy in customer marketing tasks.

## Tools and Techniques Used
- Language: Python
- Libraries: scikit-learn, pandas, NumPy
- Techniques: One-Hot Encoding, Standard Scaling, GridSearchCV, Model Evaluation
- Models: Logistic Regression, K-Nearest Neighbors, Random Forest, AdaBoost, Bagging, Voting Classifier

## Business Relevance
This project reflects a practical banking use case where marketing strategies are enhanced through predictive analytics. The resulting model supports more efficient targeting, increased conversion rates, and improved campaign ROI.
