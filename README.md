# Optimizing_Profitability
Optimizing Profitability: A Data-Driven Approach using Multiple Linear Regression

## Overview
This project focuses on predicting the profitability of an organization based on various factors such as R&D Spend, Administration, Marketing Spend, and the geographical location (State). Leveraging data analysis and multiple linear regression, we aim to provide insights into the key drivers of profit and optimize decision-making processes.

## Multiple Linear Regression
Multiple Linear Regression is a statistical method used to model the relationship between a dependent variable and multiple independent variables. In this project, we employed Multiple Linear Regression to understand how R&D Spend, Administration, Marketing Spend, and State collectively impact the profitability of an organization.

## Methodology

### Data Preparation
- Imported necessary packages in Jupyter Notebook.
- Extracted, loaded and copied the dataset.

### Data Preprocessing
- Handled incorrect 0 values in the dataset.
- Imputed incorrect data using the median of the respective columns.

### Exploratory Data Analysis (EDA)
- Analyzed the data to gain insights.
- Used box plots to identify outliers in the "State" variable.
- Imputed outliers for New York City.

### Outlier Imputation
- Filtered the data for New York City and imputed outliers using upper and lower threshold values.
- Merged the cleaned data with the copy of the original dataset.

### Data Visualization
- Created scatter plots for Administration vs. Profit, Marketing Spend vs. Profit, and R&D Spend vs. Profit.
- Analyzed correlations to understand relationships.

### Categorical Variable Analysis
- Analyzed the impact of the "State" variable on profit using one-way ANOVA.
- Concluded that "State" is not a significant factor in profit variation.

### Feature Selection
- Chose R&D Spend and Marketing Spend as independent variables for predicting profit.

### Model Building
- Built a multiple linear regression model using Scikit-Learn.
- Split the data into training and testing sets.
- Trained the model on the training data and tested it on the testing data.

### Model Evaluation
- Assessed the model's performance using the R-squared (r2_score).
- Achieved an r2_score of approximately 90.35%, indicating a strong model fit.

## Conclusion
This project provides valuable insights for businesses aiming to optimize profitability. By leveraging data analysis and multiple linear regression, we identified key factors influencing profit and built a robust predictive model. The findings empower organizations to make informed decisions and allocate resources strategically.
