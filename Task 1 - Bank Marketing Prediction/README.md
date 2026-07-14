# Task 1: Term Deposit Subscription Prediction

## Objective

The objective of this project is to predict whether a bank customer will subscribe to a term deposit using the Bank Marketing dataset.

## Dataset

- Dataset: Bank Marketing Dataset
- Source: UCI Machine Learning Repository (Downloaded from Kaggle)

## Approach

- Loaded and explored the dataset
- Performed data cleaning
- Conducted Exploratory Data Analysis (EDA)
- Encoded categorical features
- Split the dataset into training and testing sets
- Built Logistic Regression and Random Forest models
- Evaluated models using Accuracy, Confusion Matrix, F1-Score, Classification Report, and ROC Curve
- Applied SHAP (Explainable AI) to interpret model predictions

## Results

### Logistic Regression

- Accuracy: **78.77%**
- F1 Score: **0.7756**

### Random Forest

- Accuracy: **83.34%**
- F1 Score: **0.8301**

## Conclusion

Random Forest outperformed Logistic Regression and achieved the highest accuracy. SHAP was used to explain feature importance and individual predictions, making the model more interpretable.
