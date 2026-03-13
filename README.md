# Machine-Learning-Data-Analysis-Project
Machine learning data analysis project implementing preprocessing, feature engineering, regression modeling, and clustering using Python with automated result reporting in Excel.
This project performs a complete data analysis and machine learning workflow including:

- Data exploration
- Data cleaning
- Feature engineering
- Regression modeling
- Clustering analysis
- Model evaluation
- Business interpretation of results

The project was implemented in Python using Jupyter Notebook.


---

# Workflow Overview

The notebook performs the following steps:

## 1. Data Exploration
- Check column data types
- Identify numerical and categorical features
- Compute frequencies for categorical variables
- Detect missing values

## 2. Data Cleaning
- Missing value imputation
- Outlier detection and logging
- Data preprocessing

## 3. Feature Engineering
- Encoding categorical variables
- Feature selection using importance scores

## 4. Train/Test Split
The dataset is split into:

- **80% training**
- **20% testing**

Features are standardized using `StandardScaler`.

## 5. Regression Model
A **Random Forest Regressor** is trained using **GridSearchCV** to optimize hyperparameters.


Evaluation metric:
- R² Score

## 6. Clustering
K-Means clustering is used to identify patterns in the dataset.

Cluster evaluation includes:
- Cluster distribution
- Cluster quality metrics

## 7. Results Logging

All results are exported to an Excel file.




