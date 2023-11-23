# Renewable_energy_project


## Overview
This repository contains Python code for analyzing and modeling sustainable energy data. The code utilizes the pandas library for data manipulation, scikit-learn for machine learning tasks, and matplotlib for data visualization. The primary goal is to predict the renewable energy share in the total final energy consumption based on various features. Dataset is attach to this repo

## Getting Started
To run the code, make sure you have Python installed on your machine. Additionally, install the required libraries by running the following command:

```
pip install pandas scikit-learn matplotlib pandas-profiling
```
## Data
The dataset used for this project is sourced from 'global-data-on-sustainable-energy.csv'. Upon loading the data, the script provides basic information about the DataFrame, including data types and missing values.

## Data Preprocessing
Several preprocessing steps are performed to ensure data quality and compatibility with machine learning models. These include:

Converting the 'Year' column to datetime type.
Converting 'Access to clean fuels for cooking' column to boolean type.
Selecting relevant numeric columns and converting them to numeric types.
Handling missing values.

# Model Training - Regression
The regression model aims to predict the 'Renewable energy share in the total final energy consumption (%)' using selected features. The script splits the data into training and testing sets, creates a linear regression model, fits the model to the training data, makes predictions on the testing data, and evaluates the model using mean squared error (MSE) and R-squared.

# Model Training - Classification
The classification model predicts whether a country has a high or low renewable energy share based on the same features. The script utilizes logistic regression for classification, splitting the data, fitting the model, making predictions, and evaluating the model using accuracy, confusion matrix, and a classification report.

# Data Profiling
The script includes an optional step to generate a pandas profiling report using the pandas-profiling library. The report provides comprehensive insights into the dataset, including statistical summaries, visualizations, and correlation matrices. To generate the report, install the library and run the provided code.

```
pip install pandas-profiling
```
# Visualization
The script visualizes the predicted versus actual values for the regression model using a scatter plot.

# Conclusion
This project provides a comprehensive analysis of sustainable energy data, including regression and classification models for predicting renewable energy shares. Feel free to explore the code and adapt it to your specific use case.
