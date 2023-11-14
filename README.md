# AI_model_for_diabetes_2023
 Python code predicting diabetes with logistic regression. Features chi-squared feature selection, scaling method exploration, and visualizations for model evaluation. Ideal for understanding predictive modelling in healthcare analytics.

This Python script predicts diabetes using Logistic Regression, leveraging scikit-learn, pandas, and matplotlib.

Code Explanation

Data Loading and Preprocessing:
Reads diabetes data from an Excel file.
Balances the dataset by selecting an equal number of samples for each class.
Converts the "gender" column to numeric values.

Feature Selection:
Uses the chi-squared test to select the best features.
Plots a bar chart to visualize feature importance.

Model Training:
Splits the dataset into training and testing sets.
Applies Min-Max Scaling and Normalization to features.
Trains a Logistic Regression model for each scaling method.

Model Evaluation:
Computes and prints accuracy, recall, precision, and AUC scores for each model.
Plots the ROC curve for each model.
Side-by-Side Metric Comparison:

Creates a side-by-side bar chart comparing accuracy, recall, precision, and AUC for both scaling methods.
