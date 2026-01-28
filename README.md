# house-price-ml-final

# House Price Prediction Using Machine Learning

## Problem Definition
The goal of this project is to predict house sale prices based on various property features using supervised machine learning.

## Dataset
The dataset comes from Kaggle's "House Prices: Advanced Regression Techniques" competition and contains housing data with numerical and categorical features.

## Exploratory Data Analysis
EDA showed that SalePrice is right-skewed and strongly correlated with features such as Overall Quality and Living Area.

## Preprocessing
- Missing values handled using median (numerical) and mode (categorical)
- Categorical variables encoded using one-hot encoding
- Features scaled using StandardScaler
- Data split into training and testing sets

## Modeling
A Linear Regression model was trained to predict sale prices.

## Evaluation
The model was evaluated using RMSE and R² metrics. Results show reasonable predictive performance for a baseline model.

## Reflection
The main challenge was understanding preprocessing steps and feature preparation. This project helped reinforce the complete machine learning workflow from raw data to evaluation.
