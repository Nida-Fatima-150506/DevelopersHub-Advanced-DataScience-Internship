# Task 4: Loan Default Risk with Business Cost Optimization

## Objective

The objective of this project is to predict loan default risk using machine learning models and optimize business decisions by adjusting the prediction threshold based on business costs.

## Dataset

- **Dataset:** Home Credit Default Risk (application_train.csv)
- **Source:** Kaggle

## Approach

- Loaded and explored the dataset
- Performed data cleaning and handled missing values
- Encoded categorical variables using Label Encoding
- Split the dataset into training and testing sets
- Trained Logistic Regression and CatBoost classification models
- Evaluated model performance using accuracy
- Analyzed feature importance using CatBoost
- Performed business cost optimization
- Optimized the prediction threshold to reduce financial risk

## Results

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **93.40%** |
| CatBoost | **93.27%** |
| Optimized Threshold Accuracy | **92.37%** |

**Total Business Cost:** **$256,000**

## Conclusion

This project demonstrated a complete loan default prediction pipeline using Logistic Regression and CatBoost. Business cost optimization was applied to improve decision-making by considering the financial impact of false positives and false negatives. This approach provides a more practical solution for real-world credit risk assessment.
