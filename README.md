# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting credit risk based on lending data. The dataset contains information about loans, with a label indicating whether each loan is healthy (0) or has a high risk of default (1). The logistic regression model is trained on a portion of the data and then tested to assess its ability to predict loan outcomes accurately.

## Results

- **Accuracy Score**: The accuracy score of the logistic regression model is 0.99, indicating that it correctly predicts loan outcomes for 99% of the cases.
- **Precision Score**:
  - Class 0 (healthy loan): Precision is 1.00, meaning that among the loans predicted as healthy, all are truly healthy.
  - Class 1 (high-risk loan): Precision is 0.87, indicating that among the loans predicted as high-risk, 87% are truly high-risk.
- **Recall Score**:
  - Class 0 (healthy loan): Recall is 1.00, suggesting that the model correctly identifies all truly healthy loans.
  - Class 1 (high-risk loan): Recall is 0.95, meaning that the model correctly identifies 95% of high-risk loans among all actual high-risk loans.

## Summary

The logistic regression model demonstrates exceptional performance in predicting loan outcomes, with high accuracy, precision, and recall scores. It effectively distinguishes between healthy loans and high-risk loans, making it a valuable tool for assessing credit risk. Therefore, I recommend deploying this model for use by the company in making lending decisions. Its high accuracy and balanced performance across both classes make it a reliable choice for identifying potential credit risks.
