# credit-risk-classification

This is a project using several techniques to train and evaluate a model based on loan risk, with a dataset of historical lending activity from a peer-to-peer lending services company, that can identify the creditworthiness of borrowers.  The repository contains a README file and a folder named Credit_Risk, which contains a Jupyter Notebook file named credit_risk_classification which all of the code for the training, testing, and evaluation of the model; and a Resources folder which holds the CSV file containing the historical lending data.

After reading in the CSV file, the data was split into training and testing data sets using the train_test_split module from sklearn.  A Logistic Regression model was then created using the training data.  The predictions were saved and the model's performance was evaluated using balanced_accuracy_score, then generating a confusion matrix, and then the classification report was printed.

The RandomOverSampler module from imblearn.over_sampling was then used to resample the data.  A Logistic Regression model was created using the resampled data and the new predictions were saved.  The new model was evaluated the same way as the original, using balanced_accurarcy score, then generating a confusion matrix, and then printing the classification report.

