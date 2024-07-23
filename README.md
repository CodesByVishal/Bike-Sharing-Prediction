# Bike Sharing Prediction : ML MODEL

----

## Abstract

Rental bikes have become integral to urban mobility, with cities like Seoul, South Korea, implementing bike share programs. Accurately predicting bike demand is crucial for the success of such programs, ensuring availability and accessibility for users. This project aims to forecast the number of bikes required per hour, utilizing weather data and other factors to ensure a stable supply of rental bikes.

----

## Problem Statement

Given a dataset containing weather information and bike rental counts per hour, the objective is to predict the number of rental bikes needed for stable supply. Independent variables include temperature, humidity, wind speed, visibility, dew point, solar radiation, snowfall, rainfall, and date information.

---

## Introduction

The dataset comprises 8760 rows and 14 columns, with weather variables as independent features and bike rental count as the dependent variable. The goal is to understand the dataset, identify outliers, explore correlations, perform data visualization, implement models, and draw conclusions to predict bike demand accurately.

---

## Steps Involved

### Data Summary
- Analysis of the dataset to gain insights and create graphical representations for better understanding.

### Data Preprocessing
- Handling missing values, renaming columns, and splitting the date column into year, month, and day.

### Identify Relationships in Dataset
- Utilizing correlation matrix to assess statistical relationships between variables.

### Encoding of Categorical Columns
- Employing One Hot Encoding to convert categorical features into numerical format.

### Exploratory Data Analysis (EDA)
- Analyzing relationships between the target variable (Rented Bike Count) and independent variables.

### Models Implemented
- **Linear Regression**: Forecasting target variable based on independent variables.
- **Lasso Regression**: Extending linear regression with regularization penalty for better accuracy.

---

## Conclusion

From data loading to model building, the project covered exploratory data analysis, handling null values, encoding categorical columns, outlier detection, and model implementation. With a R2 score of 0.77 in Linear Regression, the model effectively captures most of the data variance.
