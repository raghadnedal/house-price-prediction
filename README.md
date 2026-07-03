# House Price Prediction - Regression

This project is a Machine Learning regression project that predicts house prices using the House Prices dataset from Kaggle.

## Project Goal

The goal of this project is to build and compare different regression models to predict house sale prices based on house features.

## Dataset

The dataset contains information about houses, such as:

- Overall quality
- Living area
- Garage size
- Basement area
- Neighborhood
- Kitchen quality
- Exterior quality
- Sale price

The target variable is:

`SalePrice`

## Steps

1. Data loading
2. Data understanding
3. Exploratory Data Analysis
4. Missing values handling
5. Feature selection
6. Encoding categorical features
7. Model training
8. Model evaluation
9. Model comparison
10. Model improvement experiments

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Random Forest with more features
- Random Forest without outliers
- Random Forest with log-transformed target
- Tuned Random Forest

## Best Model

The best model so far is:

Random Forest with more features, no extreme outliers, and log-transformed target.

This model achieved the best performance based on MAE and RMSE.

## Evaluation Metrics

The models were evaluated using:

- MAE
- RMSE
- R² Score

## Tools Used

- Python
- pandas
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook
- Git & GitHub
