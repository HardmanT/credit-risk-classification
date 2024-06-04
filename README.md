# credit-risk-classification

## Overview of the Analysis

* In this analysis, I aimed to develop machine learning models to predict credit risk, which is crucial for financial institutions in making informed lending decisions. The purpose of this analysis was to evaluate the performance of various machine learning models in predicting whether a loan is healthy (0) or high-risk (1) based on financial data.

* The dataset contained information on various financial attributes of loans, and the target variable was the loan status, categorized into healthy (0) and high-risk (1) loans. I performed exploratory data analysis to understand the distribution of the target variable and the characteristics of the features.

* The stages of the machine learning process included data preprocessing, feature engineering, model selection, training, and evaluation. I employed algorithms such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting to build and evaluate the models.

## Results

* Logistic Regression:
    * Accuracy: 0.99
    * Precision:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.86
    * Recall:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.91

* Decision Trees:
    * Accuracy: 0.98
    * Precision:
        * Label 0 (Healthy loan): 0.99
        * Label 1 (High-risk loan): 0.76
    * Recall:
        * Label 0 (Healthy loan): 0.99
        * Label 1 (High-risk loan): 0.84

* Random Forest:
    * Accuracy: 0.99
    * Precision:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.90
    * Recall:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.86

* Gradient Boosting:
    * Accuracy: 0.99
    * Precision:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.88
    * Recall:
        * Label 0 (Healthy loan): 1.00
        * Label 1 (High-risk loan): 0.87
## Summary

* Based on the evaluation results, the Logistic Regression model outperformed other models in terms of accuracy, precision, and recall for both healthy and high-risk loans. It achieved high scores across all metrics, indicating robust performance in predicting credit risk.

* The performance of the models depends on the problem we are trying to solve. In the context of credit risk analysis, it is essential to correctly identify high-risk loans (label 1) to minimize potential losses for the company. Therefore, models with higher precision and recall for label 1 are preferred.

* Considering the high precision and recall scores for both label 0 and label 1, the Logistic Regression model is recommended for use by the company in credit risk assessment tasks. Its ability to accurately classify both healthy and high-risk loans makes it a suitable choice for mitigating financial risks associated with lending.
