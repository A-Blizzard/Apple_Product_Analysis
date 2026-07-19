# Apple_Product_Analysis
Predicting Apple sale prices using Random Forest and an adapted RFM framework for products.


This project develops a Random Forest regression model to predict the sale prices of Apple devices by adapting the traditional RFM (Recency, Frequency, Monetary) framework from customer analytics to product analytics.

The adapted RFM features are defined as:

Recency: Days Since Launch
Frequency: Listing Frequency
Monetary: Launch Price

The project compares two feature engineering approaches:

Continuous RFM variables (Days Since Launch, Listing Frequency, Launch Price)
Quartile-based RFM scores (R, F, and M scores)

The objective is to evaluate whether continuous feature representations or discretized RFM scores provide better predictive performance for sale price estimation.

The notebook includes:

Data cleaning and preprocessing
Product-specific feature engineering
Adapted RFM framework
Random Forest model development
Model evaluation using R², MAE, and RMSE
Feature importance analysis
