# Waze User Churn Project

## Overview

This project investigates user churn for the Waze navigation app. The goal is to analyze user data, identify factors influencing churn, and develop models to predict and ultimately reduce user churn. The project follows a structured approach, encompassing data exploration, analysis, visualization, and statistical modeling.

## Project Stages

The project is divided into several stages, each with specific objectives and tasks:

**1. Data Inspection and Preparation**

- **Objective:** To understand and prepare the user data for analysis.
- **Tasks:**
  - Data loading and exploration using Python (pandas, numpy).
  - Data cleaning, including handling missing values and identifying/addressing outliers.
  - Summarizing data characteristics (e.g., data types, descriptive statistics).

**2. Exploratory Data Analysis (EDA) and Visualization**

- **Objective:** To explore the data visually and identify patterns or trends related to user churn.
- **Tasks:**
  - Creating visualizations (e.g., histograms, box plots) to understand data distributions and relationships.
  - Analyzing correlations between variables and user churn.

**3. Statistical Analysis**

- **Objective:** To use statistical methods to analyze the relationship between user behavior and churn.
- **Tasks:**
  - Conducting hypothesis tests (specifically, a t-test) to compare the mean number of rides between different user groups.
  - Interpreting statistical results to draw conclusions about factors influencing churn.

**4. Regression Modeling**

- **Objective:** To build a model that predicts user churn based on various factors.
- **Tasks:**
  - Building a binomial logistic regression model.
  - Evaluating model performance (e.g., accuracy, precision, recall).
  - Identifying key predictors of user churn.

**5. Machine Learning Modeling**

- **Objective:** To develop machine learning models for improved churn prediction.
- **Tasks:**
  - Building and comparing tree-based models: Random Forest and XGBoost.
  - Feature engineering, selection, and transformation.
  - Evaluating model performance and identifying optimal models.

## Key Findings

- The project identified factors influencing user churn, such as user activity patterns and driving behavior.
- Statistical analysis provided insights into user behavior differences (e.g., device type).
- Machine learning models were developed to predict user churn, with varying degrees of accuracy and predictive power.

## Recommendations

- Further investigation into factors influencing user churn is recommended.
- Additional data collection and feature engineering may improve the accuracy of churn prediction models.
- The models can be used to inform strategies for user retention and engagement.

## Files

The project includes the following files:

- waze_dataset.csv: The dataset used for analysis.
- 2. Waze project lab.pdf: Notebook for data inspection and preparation.
- 3. Waze project lab.pdf: Notebook for exploratory data analysis and visualization.
- 4. Waze project lab.pdf: Notebook for statistical analysis.
- 4.1 -executive-summary.pdf: Executive summary for the statistical analysis stage.
- 5. Waze project lab.pdf: Notebook for regression modeling.
- 5.1 -executive-summary.pdf: Executive summary for the regression modeling stage.
- 6. Waze project lab.pdf: Notebook for machine learning modeling.
- 6.1 -executive-summary.pdf: Executive summary for the machine learning modeling stage.

## Dependencies

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Author

\[Vinod Anbalagan]
