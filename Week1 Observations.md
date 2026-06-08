### Overall Conclusion

In this assignment, both Logistic Regression and Linear Regression models were implemented on the German Credit dataset. The dataset was preprocessed using one-hot encoding and split into training and testing sets before model training.

The Logistic Regression model achieved an accuracy of 80% and demonstrated better performance for the classification task. Precision, recall, F1-score, and the confusion matrix were used to evaluate its performance. A convergence warning was observed during training, indicating that the optimizer reached the maximum iteration limit before fully converging. However, the model was successfully trained and produced valid predictions. This warning can be reduced by scaling the numerical features before training.

The Linear Regression model achieved an MSE of 0.1566, RMSE of 0.3958, and an R² score of 0.2469. Since the target variable represents categorical credit classes, Linear Regression is not ideally suited for this problem. Logistic Regression provided more meaningful and interpretable results for the credit classification task.

Based on the evaluation metrics, Logistic Regression is the more appropriate model for predicting credit risk in the German Credit dataset.
