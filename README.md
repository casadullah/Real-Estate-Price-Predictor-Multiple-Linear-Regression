# Real Estate Price Predictor — Multiple Linear Regression

## What this project does
Predicts real estate prices using Multiple Linear Regression 
with standardized features (size and year) on a real estate 
dataset.

## Concepts demonstrated
- Multiple Linear Regression with Sklearn
- Feature standardization using StandardScaler
- R-squared and Adjusted R-squared comparison
- Manual p-value calculation
- Simple vs Multiple regression comparison
- Real price prediction for a new property

## Key findings
- Size is a highly significant predictor (p ≈ 0.000)
- Year is statistically insignificant (p = 0.357) — 
  once size is known, year adds no reliable information
- Every standardized unit increase in size adds $67,501
- Every standardized unit increase in year adds $13,724
- Predicted price for 750 sq ft (2009): $258,330

## Model performance
| Metric | Value |
|--------|-------|
| R-squared | 0.7764803683276793 |
| Adjusted R-squared | 0.77187171612825 |
| Size p-value | 0.000 |
| Year p-value | 0.357 |

## Tools used
Python · Pandas · NumPy · Sklearn · Scipy · Matplotlib

## How to run
pip install pandas numpy scikit-learn scipy matplotlib
jupyter notebook real_estate_regression.ipynb
