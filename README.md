# Predicting-Restaurant-Revenue-A-Machine-Learning-Approach-with-XGBoost-SVM-and-Random-Forest
## Overview

This project aims to predict the monthly revenue of a restaurant based on various factors such as the number of customers, menu price, marketing spend, cuisine type, average customer spending, promotions, and reviews. By utilizing machine learning models, we can provide insights that help restaurant owners optimize their strategies and increase profitability.

## Features

- Predict monthly revenue based on historical data.
- Utilize various machine learning algorithms (XGBoost, Random Forest, Support Vector Machine).
- Evaluate model performance using multiple regression metrics.
- Visualize the results and insights for better understanding.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib/Seaborn (for visualization)

## Data Description

The dataset used for this project contains the following columns:

- `Number_of_Customers`: Number of customers visiting the restaurant.
- `Menu_Price`: Price of the menu items.
- `Marketing_Spend`: Amount spent on marketing.
- `Cuisine_Type`: Type of cuisine offered.
- `Average_Customer_Spending`: Average spending per customer.
- `Promotions`: Indicator of promotional activities (binary).
- `Reviews`: Number of reviews received.
- `Monthly_Revenue`: Target variable representing the monthly revenue.

## Models Used

1. **XGBoost Regressor**: An efficient implementation of gradient boosting for regression tasks.
2. **Random Forest Regressor**: An ensemble method that uses multiple decision trees for better accuracy.
3. **Support Vector Machine (SVM)**: A powerful regression model that works well in high-dimensional spaces.

## Evaluation Metrics

The performance of the models is evaluated using the following metrics:

- **Mean Absolute Error (MAE)**: Average absolute difference between predicted and actual values.
- **Mean Squared Error (MSE)**: Average of the squares of the errors.
- **Root Mean Squared Error (RMSE)**: Square root of MSE, representing error in the original units.
- **R-squared (R²)**: Proportion of variance in the target variable explained by the model.
