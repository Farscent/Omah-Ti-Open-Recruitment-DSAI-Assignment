# Salary Prediction

The open recruitment process was divided into two parts; Theory test, and practical test.

In the practical test, participants were given salaries of different job titles (mainly in the technology sector). 
The task was to develop a model to predict the total gross annual salary of employees across different job roles, experience levels, employment types, and geographic locations. 
Using historical salary data and relevant job attributes, the model should provide accurate salary predictions, accounting for different work arrangements, company sizes, and levels of experience.

## Project Overview

This notebook demonstrates the process of analyzing and predicting data as part of the Oprec DSAI 2024 challenge. It covers the following:
- **Exploratory Data Analysis (EDA)**: Understanding the dataset's structure, identifying missing values, and deriving insights.
- **Data Cleaning**: Handling missing and duplicate data.
- **Modeling**: Building and evaluating machine learning models for predictions.

---

## Key Features

1. **Dataset Handling**:
   - Loads training and testing datasets.
   - Performs initial data inspections (e.g., `.head()`, `.info()`).
2. **Exploratory Data Analysis**:
   - Visualizes distributions and relationships among variables.
   - Analyzes missing values and outliers.
3. **Data Cleaning and Preprocessing**:
   - Fills or removes missing values.
   - Encodes categorical features for model compatibility.
4. **Machine Learning**:
   - Trains and evaluates predictive models.
   - Compares model performance and selects the best one.

---

My submission notebook is contained in the .zip file. 
I obtained pretty decent results of RMSE scores;
- 60121.02226 RMSE (30% of the test data)
- 62334.06200 (70% of the test data)
showing good consistency, but slight overfitting and future improvements are there.



