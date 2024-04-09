# Diabetes_Prediction_and_Analysis_Project
# Project Overview

This project aims to predict whether a person will have diabetes or not based on various health indicators. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, model creation using logistic regression, and model evaluation.

## Dataset
The dataset used in this project contains information about several health indicators such as pregnancies, glucose level, blood pressure, skin thickness, insulin level, BMI, diabetes pedigree function, and age. The target variable is the outcome, indicating whether the person has diabetes or not.

## Project Structure
- `diabetes_prediction.ipynb`: Jupyter Notebook containing the Python code for the project.
- `Dataset.csv`: Dataset used for analysis.
- `README.md`: This file providing an overview of the project.

## Libraries Used
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Steps Involved
1. **Data Loading**: Loading the dataset using pandas.
2. **Basic Checks**: Performing basic checks such as checking for missing values and data corruption.
3. **Domain Analysis**: Analyzing the domain knowledge related to diabetes and its risk factors.
4. **Exploratory Data Analysis (EDA)**:
   - Univariate analysis to understand the distribution of variables.
   - Bivariate analysis to explore relationships between variables and the target variable.
5. **Data Preprocessing and Feature Engineering**:
   - Handling missing values.
   - Handling corrupted data.
   - Checking for outliers.
6. **Feature Selection**: Checking for redundant features and correlations between variables.
7. **Model Creation**:
   - Splitting the data into training and testing sets.
   - Creating a logistic regression model.
   - Training the model.
8. **Model Evaluation**: Evaluating the performance of the model using metrics such as confusion matrix, accuracy, recall, precision, F1-score, and classification report.

## Results
The logistic regression model achieved satisfactory performance in predicting diabetes based on the given health indicators.
