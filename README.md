🏠 House Price Prediction

An end-to-end regression project built as part of a data science internship. The goal is to predict house prices based on property features using machine learning models: Linear Regression and Random Forest, and to identify which features influence price the most.


📌 Problem Statement

Real estate buyers and sellers often rely on guesswork or outdated comparisons to estimate a property's fair value. This project builds a regression model that predicts house prices based on features such as area, number of rooms, facilities and furnishing status.

✅ Tasks Completed

Task 1 — Data Loading & Exploration

Loaded dataset using Pandas
Displayed first 10 rows
Checked shape: 545 rows × 13 columns
Identified target (price) and features
Confirmed zero missing values


Task 2 — Data Cleaning

No missing values or duplicates found
Applied One-Hot Encoding to all categorical and binary columns
All features converted to numeric form for modelling


Task 3 — Model Building

Split data 80/20 into train and test sets
Trained Linear Regression and Random Forest Regressor
Evaluated both models using MAE, RMSE, and R²

Task 4 — Visualizations

Histogram of house price distribution
Correlation heatmap of all features
Actual vs Predicted price scatter plot (both models overlaid)


Task 5 — Insights & Summary

Area (0.54) and bathrooms (0.52) are the strongest predictors of price
Air conditioning (0.45) is the most impactful amenity feature
Unfurnished status negatively impacts price (-0.28)
Linear Regression suited this dataset better due to its small size (545 rows)

