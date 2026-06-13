# Nike sales Revenue Prediction

## One Line Summary
A machine learning project that perdict the revenue using machine learning models.

## Overview
This project analyzes Nike sales data and builds predictive models to estimate revenue based on product, customer, sales channel, region, date, and pricing-related features.

The aim is which model give the best revenue prediction from the dataset.

## Problem Statement
Sales revenue prediction is important for business planning, inventory management, and decision-making.

This project predicts Nike product revenue using historical sales data and compares two machine learning models to identify the better-performing approach.

## Dataset
The dataset used is `nike_test_data.csv`, which contains Nike sales records with columns such as:
- Order ID
- Gender Category
- Product Line
- Product Name
- Units Sold
- MRP
- Discount Applied
- Revenue
- Order Date
- Sales Channel
- Region
- Profit
- Clothing Size
- Shoe Size

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- CSV dataset

## Methods
The project follows these steps:
1. Load the Nike sales dataset.
2. Then clean the dataset by using pandas in jupyter notebook.
3. After that i do EDA
4. Convert order dates into useful features such as year, month, day, and weekday.
5. Preprocess numerical and categorical columns using scaling, imputation, and one-hot encoding.
6. Train two models:
   - Linear Regression
   - Random Forest Regressor
7. Generate prediction comparison CSV and visualization graph.

## Dashboard 
Screenshot <img width="1092" height="637" alt="Dashboard_screenshot" src="https://github.com/user-attachments/assets/7c821f43-336d-4185-baea-290c2f0c17e0" />

## Results and Conclusion
The Random Forest model gave the best performance for revenue prediction.

## Future Work
Add more advanced models such as XGBoost or Gradient Boosting.

Build an interactive dashboard using Power BI, Tableau, Streamlit, or Dash.

Add more sales data for better model training.

Perform feature importance analysis.

Improve data cleaning and handle outliers.

Deploy the model as a simple web application.

## Author and Contact
Author: Pratisha Biswal
Project: Nike Sales Revenue Prediction
Email: pratishabiswal@gmail.com
GitHub: https://github.com/








