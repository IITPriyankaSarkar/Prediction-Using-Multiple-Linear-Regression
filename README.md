# Project Name : Prediction Using Multiple Linear Regression

# Project Overview
This project demonstrates the application of Multiple Linear Regression for predicting a quantitative response variable. Multiple Linear Regression is an extension of Simple Linear Regression that uses multiple features to predict a real-valued output. The model assumes a linear relationship between the features and the target variable.

# Objective
The main objective is to build and evaluate multiple linear regression models to predict sales revenue based on advertising spending across different channels—TV, Radio, and Newspaper. The project involves:

Loading and exploring the dataset

Analyzing feature relationships with the response variable

Building multiple linear regression models

Evaluating models with appropriate metrics

Understanding the effect of including/excluding features

Exploring interaction effects between features

# Dataset
The dataset used in this project captures sales revenue and advertisement spends on various media channels:

TV: Advertising budget spent on TV

Radio: Advertising budget spent on Radio

Newspaper: Advertising budget spent on Newspaper

Sales: Sales revenue generated

The dataset contains 200 entries for advertising spends and sales.

# Libraries Used
The project uses the following Python libraries:

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

SciPy (for skewness)

Yellowbrick (for regression diagnostic plots)

# Project Steps
1. Importing Libraries
All necessary libraries for data manipulation, visualization, and modeling are imported.

2. Loading Data
Advertising dataset is loaded and basic structure and summary statistics are displayed.

3. Exploratory Data Analysis
Visualize relationships between features (TV, Radio, Newspaper) and sales.

Correlation heatmap to understand feature interrelations.

4. Building Multiple Linear Regression Model
Fit a linear regression model using TV, Radio, and Newspaper as predictors.

Coefficients and intercept are estimated.


 
5. Feature Selection
Evaluate which combination of features best predicts sales by comparing metrics like R-squared and RMSE.

6. Model Evaluation
Use train-test split to evaluate model performance on unseen data.

Metrics used:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R-squared (R2)

Diagnostic plots from Yellowbrick for residuals and prediction errors.

7. Interaction Effects
Explore synergy between features by creating interaction terms (e.g., TV * Radio) and fit a regression model including them for potentially improved performance.

# Results
The regression model indicates that TV and Radio advertisement budgets positively affect sales while Newspaper has minimal or no effect.

Interaction effects between TV and Radio enhance model performance.

The model evaluation metrics demonstrate a good fit with a high R2 score (~0.98) and low RMSE (~0.7) on the test dataset.

# Conclusion
Multiple Linear Regression is effective in modeling sales based on advertisement spends, particularly considering interaction effects. The project highlights key steps in building, evaluating, and interpreting regression models with multiple predictors.
