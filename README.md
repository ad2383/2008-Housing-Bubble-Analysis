# 2008 Housing Bubble Analysis

## Overview
A quantitative study of the 2008 housing bubble analyzing macroeconomic and financial drivers of systemic risk, with predictive modeling using machine learning and neural networks.

## Objectives
- Identify key economic indicators contributing to the housing bubble
- Analyze relationships between housing prices, credit expansion, and leverage
- Gradient-based sensitivity analysis on neural network model (LSTM) to quantify feature influence on model outputs

## Data Sources
- Case-Shiller Home Price Index 
- Federal Reserve Economic Data (FRED)
- Mortgage and credit market datasets (CAR)

## Methods
- Exploratory data analysis (EDA)
- Feature engineering on macroeconomic indicators
- Machine learning models (e.g., regression, tree-based models)
- Neural networks for time-series forecasting

## Results

- The LSTM model demonstrated strong predictive performance on housing price dynamics (R² ≈ 0.98 on the holdout set).
- Gradient-based sensitivity analysis identified housing supply, unemployment, and inventory measures as the most influential drivers of model predictions.

## Future Work
- Expand to LSTM-based models
- Stress-test predictions under specific macroeconomic shocks
