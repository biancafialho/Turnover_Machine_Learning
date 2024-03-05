# Employee Turnover Analysis

## Overview

This project aims to analyze an employee database of a multinational corporation to identify factors influencing turnover. The dataset comprises 30 variables and includes information on 1470 employees. The company's turnover rate is approximately 16%, indicating an unbalanced dataset.

## Key Findings

- Employees at Job Level 1 are more likely to resign.
- Distance from home to work impacts turnover; longer commutes correlate with higher turnover rates.
- Marital status is a significant factor, with single employees showing a higher likelihood of turnover, possibly indicating a greater openness to career changes.
- Younger employees are more prone to turnover.

## Data Preprocessing

To enhance variable analysis, certain transformations were applied. Text-to-number conversions were performed, and categorical variables were converted into dummy variables. The Random Forest Classifier and Shap Values were utilized to assess variable importance.

## Model Results

The analysis revealed the following influential variables:

1. Job Level
2. Distance from Home
3. Marital Status
4. Age

These findings align with both exploratory analysis and predictive modeling, reinforcing their significance.

## Conclusion

While the identified factors provide valuable insights, the extent to which the company can intervene and control these variables for improvement remains uncertain. It is crucial for the company to explore strategies to address turnover based on these findings.

