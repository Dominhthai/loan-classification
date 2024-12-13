# loan-classification
A Final Machine Learning Project that predicts whether a person should get a Loan from banks or not, the label feature is named Loan_status.
* This model trains and evaluates in 2 different ways: Use Classifiers from Scikit-Learn and use a Simply Built Neural Network.
* Our Neural Network is trained on GPU, with 100 epochs.At each epoch, we save the best model based on highest acc(Accuracy) so far. Our optimization method is use L1 Regularization.
* The evaluation metrics are: Accuracy, Precision, Recall, F1-Score.
* The best result is 94% for Classifier XGBoost.
