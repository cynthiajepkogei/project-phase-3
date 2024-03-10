# project-phase-3

# Logistic Regression Model Performance

The Logistic Regression model has the following performance metrics in relation to customer churn:

- **Accuracy**: 0.788606, which means the model correctly predicted the customer churn about 78.86% of the time.
- **Precision**: 0.393617, indicating that when the model predicts a customer will churn, it is correct about 39.36% of the time.
- **Recall**: 0.732673, meaning the model correctly identifies 73.27% of the actual churn cases.
- **F1 Score**: 0.512111, which is the harmonic mean of precision and recall, providing a balance between the two metrics.
- **ROC-AUC**: 0.76563, this is the area under the receiver operating characteristic curve, and a value closer to 1 indicates a better model. This score suggests the model’s ability to distinguish between customers who will churn and those who won’t is fairly good.

## Confusion Matrix

|                | Predicted: No Churn | Predicted: Churn |
|----------------|---------------------|------------------|
| Actual: No Churn | 452 (True Negatives)  | 114 (False Positives) |
| Actual: Churn    | 27 (False Negatives)  | 74 (True Positives)  |

## Model Evaluation

In terms of overall performance, the model seems to be better at predicting customers who will not churn (True Negatives) than those who will (True Positives). However, the number of False Positives is relatively high, which could lead to unnecessary costs for the company. The low number of False Negatives is a positive aspect, as it means the model is less likely to miss opportunities to retain customers. 

However, there is room for improvement, particularly in increasing the number of True Positives and reducing the number of False Positives. This could potentially be achieved by further tuning the model or using a different modeling approach.
