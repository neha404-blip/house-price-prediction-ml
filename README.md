# House Price Prediction using Machine Learning

## Project Overview

This project predicts house prices using machine learning regression models. The goal was to build a predictive model, evaluate different algorithms, and improve performance through feature engineering and target transformation.

## Dataset

The dataset contains information about residential properties, including:

- Bedrooms
- Bathrooms
- Living area size
- Lot size
- Floors
- Waterfront
- View
- Condition
- Year built
- Renovation year
- Location-related features

Target Variable:
- Price

## Data Preprocessing

The following preprocessing steps were performed:

- Converted date column into year and month features
- Removed unnecessary columns
- Applied One-Hot Encoding to categorical features
- Removed invalid records with zero house price
- Applied log transformation to the target variable to reduce skewness

## Models Used

1. Linear Regression
2. Ridge Regression
3. Random Forest Regressor

## Results

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.7446 |
| Ridge Regression | 0.7457 |
| Random Forest | 0.7227 |

### Best Model
**Ridge Regression**

R² Score: **0.7457**

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Key Learnings

- Importance of data preprocessing
- Handling categorical variables with One-Hot Encoding
- Impact of skewed target distributions
- Using log transformation to improve model performance
- Comparing multiple regression models

## Author

Statistics Student at Jahangirnagar University
