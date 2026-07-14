# Task 3: Energy Consumption Time Series Forecasting

## Objective

The objective of this project is to forecast household energy consumption using historical time series data and compare the performance of ARIMA, Prophet, and XGBoost models.

## Dataset

- **Dataset:** Household Power Consumption Dataset
- **Source:** UCI Machine Learning Repository (Downloaded from Kaggle)

## Approach

- Loaded and explored the dataset
- Performed data preprocessing and handled missing values
- Combined Date and Time into a Datetime column
- Resampled the data to daily observations
- Engineered time-based features (Day of Week, Month, Year)
- Conducted Exploratory Data Analysis (EDA)
- Built ARIMA, Prophet, and XGBoost forecasting models
- Evaluated the models using MAE and RMSE
- Compared the forecasting performance of all models
- Visualized actual vs predicted energy consumption

## Results

| Model | MAE | RMSE |
|-------|------:|------:|
| ARIMA | **0.3013** | **0.3931** |
| Prophet | **0.4053** | **0.5218** |
| XGBoost | **0.3690** | **0.4617** |

## Conclusion

Among the three forecasting models, **ARIMA** achieved the best performance with the lowest MAE and RMSE values. The project demonstrated the complete workflow of time series forecasting, including preprocessing, feature engineering, model development, evaluation, and visualization.
