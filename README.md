# Air Quality Forecasting Project

## Description

This project aims to forecast the concentrations of CO (Carbon Monoxide) and NO₂ (Nitrogen Dioxide) using time-series data.

## Steps

1. **Data Preprocessing**: Combined the Date and Time columns, handled missing values, and detected outliers.
2. **Exploratory Data Analysis (EDA)**: Analyzed trends, seasonality, and correlations in the data.
3. **Feature Engineering**: Created lag features, time-based features, and included environmental factors.
4. **Model Training**: Trained ARIMA, Random Forest, and LSTM models for forecasting.
5. **Model Evaluation**: Evaluated models using MAE and RMSE.
6. **Visualization and Insights**: Generated forecasts and provided actionable recommendations.

## Evaluation

The best model was the Random Forest Regressor for both CO(GT) and NO₂(GT), achieving a MAE of X and RMSE of Y.

## Recommendations

- Implement monitoring systems during high CO and NO₂ levels.
- Introduce policies for better traffic and industrial emissions control.
