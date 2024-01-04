# Linear-Regression-Model-on-Head-Size-vs-Brain-Weight
# Headbrain Linear Regression Analysis

This repository contains Python code for performing linear regression analysis on a dataset related to head size and brain weight. The dataset is loaded from a CSV file, and a linear regression model is trained to predict brain weight based on head size.

## Files

- `headbrain.csv`: CSV file containing the dataset with columns - 'Gender', 'Age Range', 'Head Size(cm^3)', and 'Brain Weight(grams)'.

- `headbrain_analysis.py`: Python script for data analysis, linear regression modeling, and visualization using the scikit-learn library.

## Description
The dataset is loaded using pandas, and the 'Head Size(cm^3)' and 'Brain Weight(grams)' columns are extracted as features (X) and target variable (Y).

The data is split into training and testing sets using scikit-learn's train_test_split function.

A linear regression model is created and fitted using the training data.

Predictions are made on the entire dataset and the training set.

R-squared is calculated to evaluate the model's performance on the entire dataset.

Predictions are made on the test set, and a scatter plot is generated for visualization.

The scatter plot for the training set includes both actual and predicted values.

## Notes
Ensure that you have the necessary permissions to read the CSV file.

Adjust the file path in the pd.read_csv line if your dataset is located in a different directory.

The code assumes that the 'Head Size(cm^3)' column is the independent variable (X), and 'Brain Weight(grams)' is the dependent variable (Y).

The script uses scikit-learn for linear regression modeling and matplotlib for data visualization.

Feel free to modify the code for further analysis or use it as a starting point for your own projects.

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install numpy pandas scikit-learn matplotlib 
