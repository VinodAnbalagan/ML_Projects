# Waze User Churn Project

## Overview

This project investigates user churn for the Waze navigation app. The goal is to analyze user data, identify factors influencing churn, and develop models to predict and ultimately reduce user churn. The project follows a structured approach, encompassing data exploration, analysis, visualization, and statistical modeling.

## Project Stages

The project is divided into several stages, each with specific objectives and tasks:

**1. Data Inspection and Preparation**

- **Objective:** To understand and prepare the user data for analysis.
- **Tasks:**
  - Data loading and exploration using Python (pandas, numpy)[cite: 96, 97, 98, 99, 100, 18, 19, 20, 21, 22, 23].
  - Data cleaning, including handling missing values and identifying/addressing outliers[cite: 378, 379, 380, 381, 382, 383, 384, 385, 386, 387, 388, 389, 390, 391, 178, 179, 180, 181, 182, 183, 184, 185, 186, 187, 188, 189, 190].
  - Summarizing data characteristics (e.g., data types, descriptive statistics)[cite: 91, 92, 93, 94, 95, 392, 393, 394, 12, 13, 14, 86, 87, 88, 89, 90, 10, 11, 618, 619, 620, 621, 8, 9].

**2. Exploratory Data Analysis (EDA) and Visualization**

- **Objective:** To explore the data visually and identify patterns or trends related to user churn.
- **Tasks:**
  - Creating visualizations (e.g., histograms, box plots) to understand data distributions and relationships[cite: 363, 364, 365, 366, 367, 368, 369, 370, 371].
  - Analyzing correlations between variables and user churn[cite: 375, 376, 377, 174, 175, 176].

**3. Statistical Analysis**

- **Objective:** To use statistical methods to analyze the relationship between user behavior and churn.
- **Tasks:**
  - Conducting hypothesis tests (specifically, a t-test) to compare the mean number of rides between different user groups (e.g., iPhone vs. Android users)[cite: 616, 617, 618, 619, 620, 621].
  - Interpreting statistical results to draw conclusions about factors influencing churn[cite: 683].

**4. Regression Modeling**

- **Objective:** To build a model that predicts user churn based on various factors.
- **Tasks:**
  - Building a binomial logistic regression model[cite: 854, 855, 856, 857, 858, 859, 860, 861].
  - Evaluating model performance (e.g., accuracy, precision, recall)[cite: 862, 863, 864, 865, 866, 867, 868, 869, 870, 871, 872, 873, 874, 875, 703, 704, 705, 706, 707, 708, 709, 710, 711, 712, 713, 714, 715, 716, 717, 718, 719, 720, 721, 722, 723, 724, 725].
  - Identifying key predictors of user churn[cite: 1015, 1016].

**5. Machine Learning Modeling**

- **Objective:** To develop machine learning models for improved churn prediction.
- **Tasks:**
  - Building and comparing tree-based models: Random Forest and XGBoost[cite: 1277, 1278, 1279, 1280, 1281, 1282].
  - Feature engineering, selection, and transformation[cite: 1283, 1284, 1285, 1286, 1287].
  - Evaluating model performance and identifying optimal models[cite: 1494, 1495, 1050, 1051, 1052, 1053, 1054, 1055, 1056, 1057, 1058, 1059, 1060, 1061, 1062].

## Key Findings

- The project identified factors influencing user churn, such as user activity patterns and driving behavior[cite: 87, 9, 8, 10, 68, 69, 70, 83, 84, 85].
- Statistical analysis provided insights into user behavior differences (e.g., device type)[cite: 168, 169, 170, 171].
- Machine learning models were developed to predict user churn, with varying degrees of accuracy and predictive power[cite: 363, 364, 365, 366, 367, 368, 369, 370, 371].

## Recommendations

- Further investigation into factors influencing user churn is recommended[cite: 1303, 1304, 1305].
- Additional data collection and feature engineering may improve the accuracy of churn prediction models[cite: 1494, 1495].
- The models can be used to inform strategies for user retention and engagement[cite: 1280, 1281, 1282].

## Files

The project includes the following files:

- `waze_dataset.csv`: The dataset used for analysis.
- `2. Waze project lab.pdf`: Notebook for data inspection and preparation.
- `3. Waze project lab.pdf`: Notebook for exploratory data analysis and visualization.
- `4. Waze project lab.pdf`: Notebook for statistical analysis.
- `4.1 -executive-summary.pdf`: Executive summary for the statistical analysis stage.
- `5. Waze project lab.pdf`: Notebook for regression modeling.
- `5.1 -executive-summary.pdf`: Executive summary for the regression modeling stage.
- `6. Waze project lab.pdf`: Notebook for machine learning modeling.
- `6.1 -executive-summary.pdf`: Executive summary for the machine learning modeling stage.

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
