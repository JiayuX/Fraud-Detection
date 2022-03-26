# Fraud-Detection
In this project, we try to use different supervised or unsupervised machine learning models to detect fraudulent credit card transactions.

The supervised models we used are neural multipayer perceptron classifier (MLP) and gradient boosting classifier (GB). The unsupervised models used are isolation forest (IF) and antoencoder (AE).

The recall of all models on their own test set are:

MLP: 93%

GB: 93%

IF: 92%

AE: 93%

Note that MLP and GB are evaluated on the same test data so their results are directly comparable. However, the results of IF and AE are not directly comparable to other models because their training and test data are splitted in different ways.

