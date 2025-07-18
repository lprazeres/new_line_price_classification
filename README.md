🛒 Predicting Competitive Prices Using Business Analytics
This project applies Business Analytics and Machine Learning techniques to support strategic pricing decisions for a new line of products in a retail business.

A local store is launching a new product category but lacks market experience to define competitive price points. My goal was to help the client identify optimal price ranges based on product characteristics and market data.

🔍 Project Workflow
Market Benchmarking:
I collected price data of similar products from competitors to establish a market baseline.

Hypothesis Testing:
Statistical tests were applied to understand which features significantly influence the price:

ANOVA for numeric variables

Kruskal-Wallis for non-parametric data

Chi-square for categorical variables

Machine Learning Classification:
I trained multiple classification models to predict price ranges.
The best-performing model was XGBoost, which provided high accuracy and handled complex feature interactions effectively.

Feature Importance & SHAP Analysis:

Used Feature Importance to identify the top variables contributing to price prediction.

Applied SHAP values to interpret the influence and magnitude of each variable on model predictions.

Business Impact:
Based on the trained model, I predicted the price range for the client’s new products. Now, the business can:

Set competitive prices

Create targeted promotions

Understand key product drivers impacting profitability
