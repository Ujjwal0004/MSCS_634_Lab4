# MSCS_634_Lab4
# Lab 4: Regression Analysis with Regularization Techniques

## Purpose
This lab explores different regression techniques using the Diabetes dataset. The goal is to implement Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, Ridge Regression, and Lasso Regression. The models were evaluated using MAE, MSE, RMSE, and R² to understand performance and overfitting behavior.

## Dataset
The Diabetes dataset from sklearn.datasets contains multiple health-related features used to predict disease progression. The dataset includes 10 standardized features such as BMI, age, blood pressure, and other medical measurements. No missing values were found, so no major data cleaning was required.

# Key Insights
- Simple Linear Regression performed reasonably but was limited because it used only one feature.
- Multiple Linear Regression performed better because it used all available features.
- Polynomial Regression improved performance at moderate degrees but showed overfitting at higher degrees.
- Ridge and Lasso Regression helped reduce overfitting by shrinking coefficients.
- Lasso set some coefficients to zero, which means it performed feature selection.

# Challenges faced
- Choosing the correct polynomial degree required testing multiple values.
- Higher degree polynomial models increased training accuracy but reduced test performance due to overfitting.
- Selecting appropriate alpha values for Ridge and Lasso required comparison.
- Understanding the difference between relationship visualization and model evaluation graphs required careful interpretation.
