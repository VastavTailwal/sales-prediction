# Big Mart Sales Prediction Project

## Overview

The Big Mart Sales Prediction project is a data science and machine learning project that aims to predict sales for Big Mart outlets based on various features and data analysis. This project includes data cleaning, exploratory data analysis (EDA), data visualization, encoding, scaling, and the application of several regression models.

## Project Highlights

- **Dataset:** The project utilized a dataset containing information about products and outlet sales for Big Mart outlets.

- **Key Steps:**
  - Data Cleaning: The dataset underwent thorough cleaning to handle missing values and outliers.
  - Exploratory Data Analysis (EDA): EDA techniques were employed to gain insights into the dataset's characteristics.
  - Data Visualization: Visualizations were created to better understand the distribution and relationships among variables.
  - Data Encoding: Categorical variables were encoded for compatibility with machine learning models.
  - Data Scaling: Feature scaling was applied to standardize numerical features.

- **Regression Models:**
  - Linear Regression
  - Lasso Regression
  - Ridge Regression
  - Random Forest
  - XGBoost
  - LightGBM
  - Artificial Neural Network (ANN)

## Approach

1. **Data Cleaning:** Missing values and outliers were addressed to ensure data quality.

2. **Exploratory Data Analysis (EDA):** EDA techniques were used to understand data distributions, correlations, and key insights.

3. **Data Visualization:** Visualizations, such as histograms, scatter plots, and heatmaps, were created to represent data patterns effectively.

4. **Data Encoding:** Categorical variables were encoded, such as one-hot encoding or label encoding, to convert them into numerical form.

5. **Data Scaling:** Numerical features were scaled for uniformity and to prevent model bias.

6. **Model Building:** Regression models, including Linear Regression, Lasso, Ridge, ANN, XGBoost, LightGBM, and Random Forest, were implemented and evaluated for sales prediction.

## Results

| Model | R2 score |
| ----- | -------- |
| Linear Regression | 0.63 * |
| Lasso Regression | 0.51 |
| Ridge Regression | 0.51 |
| Random Forest | 0.59 |
| XG Boost | 0.60 |
| Light GBM | 0.61 |
| ANN | 0.60 * |

- Best model is Light GBM with test r<sup>2</sup> score of `0.60`.

\* Overfitted

## Lessons Learned

- Insights gained from EDA informed feature selection and engineering.
- The importance of feature scaling in improving model performance.
- The significance of model selection and hyperparameter tuning in regression tasks.

## Future Steps

- Further hyperparameter tuning for the selected model to enhance predictive accuracy.
- Feature engineering to explore additional potential predictors.
- Exploring ensemble techniques for combining model predictions.

## Conclusion

The Big Mart Sales Prediction project involved extensive data preprocessing, EDA, and the application of various regression models. It serves as a valuable learning experience in data analysis and predictive modeling in the context of retail sales.
