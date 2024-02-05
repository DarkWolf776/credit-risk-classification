# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

In this homework assignment, we explored the task of predicting loan statuses using machine learning models.
We started by preprocessing the data, including handling missing values, encoding categorical variables, and splitting the data into training and testing sets. 
We then experimented with two machine learning models: logistic regression and logistic regression with resampled data using Random Over Sampling.

## Results

* Logistic Regression Model:
Accuracy Score: The logistic regression model achieved an accuracy score of 1.0. 
This score indicates the proportion of correctly classified instances out of all instances in the testing set.
Confusion Matrix: The confusion matrix reveals the model's performance across different classes. 
It shows the number of true positives, true negatives, false positives, and false negatives.
Classification Report: The classification report provides additional insights into the model's performance by reporting precision, recall, F1-score, and support
for each class. These metrics help evaluate the model's ability to correctly classify instances for both healthy and high-risk loans.

* Logistic Regression Model with Resampled Data:
Accuracy Score: After resampling the data to address class imbalance, the logistic regression model achieved an accuracy score of 1.0.
 This score reflects the model's ability to accurately predict loan statuses after accounting for class imbalance.
Confusion Matrix: The confusion matrix for the model with resampled data provides insights into how well the model 
predicts both healthy and high-risk loans, considering the balanced distribution of classes.
Classification Report: The classification report for the model with resampled data offers detailed metrics for each class, 
including precision, recall, F1-score, and support. These metrics highlight the model's performance in identifying both healthy and high-risk loans,
 taking into account the resampling technique used to address class imbalance.

## Summary

Overall, both machine learning models showed promising performance in predicting loan statuses. 
However, the logistic regression model with resampled data demonstrated improved accuracy and robustness by addressing class imbalance. 
By leveraging techniques like Random Over Sampling, we were able to enhance the model's ability to generalize across different classes,
 resulting in more reliable predictions for both healthy and high-risk loans.
