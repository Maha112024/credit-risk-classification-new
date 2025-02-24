# credit-risk-classification-new


The logistic regression model is highly effective in predicting both labels, but with some differences in performance between the two classes:

Class 0 (healthy loans): The model performs excellently with perfect precision (1.00) and perfect recall (1.00), indicating it correctly identifies all healthy loans with no false positives or false negatives.

Class 1 (high-risk loans): The model is still strong but not flawless. It has a precision of 0.87 and a recall of 0.95, meaning it misses some high-risk loans (false negatives), but when it predicts high-risk loans, it is quite accurate. The recall is higher than precision, indicating it catches most of the high-risk loans, but with a few false positives.

Despite the slight dip in performance for class 1, the overall accuracy of 99% and strong macro and weighted averages of 0.95 and 0.99 respectively show that the model is still very effective at predicting both labels, with a minor trade-off for class 1.
