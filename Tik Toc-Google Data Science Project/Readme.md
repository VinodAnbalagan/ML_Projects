# TikTok Video Classification Project

## Project Overview

This project aims to develop a machine learning model to classify TikTok videos as either "claims" or "opinions" to help prioritize content moderation efforts. The project was completed as part of a data science course and follows a comprehensive data science workflow from proposal to final model deployment.

## Project Structure

The project is organized into six main phases, each documented in separate PDF files:

1. **Project Proposal** (`1. TikTok-project-proposal.pdf`)

   - Outlines the project objectives, milestones, and timeline
   - Defines the goal of classifying videos as claims or opinions

2. **Initial Data Exploration** (`2. TikTok project lab.pdf`)

   - Python notebook with initial data loading and exploration
   - Basic statistical analysis and variable relationships

3. **Exploratory Data Analysis (EDA)** (`3.1 TikTok project lab.pdf`)

   - Data visualization and deeper analysis
   - Identification of key patterns and relationships in the data

4. **Statistical Analysis** (`4. TikTok project lab.pdf`)

   - Hypothesis testing to validate observations
   - Statistical comparisons between video categories

5. **Regression Modeling** (`5. TikTok project lab.pdf`)

   - Logistic regression to predict verified status
   - Model evaluation and interpretation

6. **Machine Learning Classification** (`6. TikTok project lab.pdf`)
   - Final classification models (Random Forest and XGBoost)
   - Model evaluation and selection

## Key Findings

### Data Insights

- Videos labeled as claims receive significantly more views (average 501,029) than opinion videos (average 4,956)
- Authors posting claim videos are more likely to be banned or under review
- Verified accounts are much more likely to post opinions than claims

### Model Performance

- **Random Forest Model** achieved:

  - Recall: 0.995
  - Precision: 1.00
  - F1-score: 1.00
  - Accuracy: 1.00

- **XGBoost Model** achieved:
  - Recall: 0.99
  - Precision: 1.00
  - F1-score: 0.99
  - Accuracy: 0.99

The Random Forest model was selected as the champion model due to its slightly better recall score.

## Technical Implementation

### Data Processing

- Handled missing values by dropping null entries
- Created new features like text length from video transcriptions
- Addressed class imbalance through resampling techniques
- Encoded categorical variables for model compatibility

### Model Features

The most predictive features were all related to user engagement:

- Video view count
- Video like count
- Video share count
- Video download count
- Video comment count

## How to Use This Repository

1. Clone the repository:

```bash
git clone [repository-url]
```

2. Review the PDF files in numerical order to follow the project progression
3. Key files to examine:
   - `2. TikTok project lab.pdf` for initial data exploration
   - `3.1 TikTok project lab.pdf` for comprehensive EDA
   - `6. TikTok project lab.pdf` for final model implementation

## Dependencies

The project was implemented using Python with the following key libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- XGBoost

## Conclusion

This project successfully developed a highly accurate machine learning model to classify TikTok videos as claims or opinions. The model can help prioritize content moderation efforts by identifying videos more likely to violate platform terms of service. The Random Forest model demonstrated exceptional performance with near-perfect classification metrics.
