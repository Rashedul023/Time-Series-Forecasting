# Time Series Forecasting of Carbon Monoxide and Nitrogen Oxides

## Overview
This project performs time series forecasting on air quality data to predict future levels of Carbon Monoxide (CO) and Nitrogen Oxides (NOx). The goal is to analyze historical pollutant trends and build predictive models for environmental monitoring.

## Dataset
- Source: Air quality dataset  
- Target Variables: CO and NOx concentration levels  
- Type: Time series data  
- No major missing values after preprocessing  

## Models Used
- ARIMA  
- Random Forest Regressor  
- Support Vector Regression (SVR)  
- LSTM (Deep Learning)  

## Data Preprocessing
- Handling missing values  
- Date-time parsing and indexing  
- Normalization / Scaling  
- Train-test split (time-based)  
- Feature engineering for lag values  

## Results
- Compared model performance using MAE, MSE, and RMSE  
- LSTM showed strong performance in capturing temporal dependencies  
- Traditional models performed well for short-term forecasting  

## Key Findings
- Deep learning models captured seasonality and trends effectively  
- Classical time series models provided stable baseline performance  
- Proper preprocessing significantly improved forecasting accuracy  
 Conclusion  
