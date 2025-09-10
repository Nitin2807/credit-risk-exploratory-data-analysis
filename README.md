# Credit Risk Exploratory Data Analysis (EDA)

This project performs an in-depth exploratory data analysis on a financial dataset to identify patterns and factors that indicate whether a loan applicant is likely to default.

## Project Overview

The notebook takes a large dataset of credit application data and performs several key EDA steps:
- **Data Loading:** Imports the `application_data.csv` dataset.
- **Data Cleaning & Missing Value Treatment:**
    - Columns with more than 47% missing values are dropped.
    - Categorical features with missing values (like `OCCUPATION_TYPE`) are imputed.
    - Numerical features are handled by filling missing values with the median.
- **Feature Engineering:**
    - Time-based columns like `DAYS_BIRTH` and `DAYS_EMPLOYED` are converted into more interpretable 'Years' units.
    - Continuous numerical features like `AMT_CREDIT` are binned into categorical groups (e.g., 'Very Low Credit', 'Low Credit').
- **Data Visualization:** The notebook likely contains visualizations (the code for plotting is present) to better understand the distribution and relationships within the data.

## Goal
The primary goal is to understand the driving factors behind loan defaults, which can help in building more accurate credit risk models.
