# 2008 Housing Bubble Analysis

A quantitative study of the 2008 housing bubble analyzing macroeconomic and 
financial drivers of systemic risk, with predictive modeling using machine 
learning and neural networks.

📄 [Full Empirical Study (PDF)](2008_HousingBubble_QuantitativeAnalysis.pdf)

## Overview
This project engineers 20+ macro-financial features from 200,000+ records 
spanning 1970–2010 across Case-Shiller, FRED, and HMDA datasets. It applies 
correlation analysis, regression modeling, and an LSTM classifier to forecast 
the Case-Shiller Home Price Index and isolate early-warning signals preceding 
the 2008 collapse.

## Data Sources
- Case-Shiller Home Price Index
- Federal Reserve Economic Data (FRED)
- Home Mortgage Disclosure Act (HMDA)

## Methods
- Feature engineering on 20+ macroeconomic indicators across 200,000+ records
- Exploratory data analysis and correlation analysis to identify early-warning signals
- Regression modeling (OLS, Ridge) for baseline forecasting
- Random Forest for feature importance and nonlinear relationships
- LSTM neural network for time-series forecasting of housing price dynamics
- Gradient-based sensitivity analysis to quantify feature influence on model outputs

## Results
- LSTM achieved R² ≈ 0.98 on the holdout set for Case-Shiller HPI forecasting
- Housing supply authorization, unemployment, and unsold inventory identified 
  as the strongest leading indicators of collapse
- Findings synthesized in a 4,000-word empirical study linking model outputs 
  to macroeconomic theory

## Future Work
- Extend framework to identify early-warning signals in other asset bubbles
- Stress-test predictions under specific macroeconomic shock scenarios
- Incorporate credit spread and shadow banking data for richer systemic risk modeling
