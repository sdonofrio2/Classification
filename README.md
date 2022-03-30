#Classification

In this repository, I used the imbalanced learn library to resample lending data to predict credit risk.

In the "credit_risk_resampling" ipynb file, I oversampled the data using the Native Random Oversamler and SMOTE algorithms, undersampled the data using the Cluster Centroid algorithm, and did a combination using the SMOTEEN algorithm. For each of these algorithms, I trained a logistic regression classifier from the sklearn.linear_model using the resampled data, calculated the balanced accuracy score, displayed the confusion matrix, and printed the imbalanced classification report. 
Based on this data, the SMOTE algorthm was performing the best.

In the "credit_risk_ensemble" ipynb file, I used the Balanced Random Forest Classifier and Easy Ensemble Classifier models to predict loan risk. I trained a logistic regression classifier from the sklearn.linear_model using the resampled data, calculated the balanced accuracy score, displayed the confusion matrix, and printed the imbalanced classification report. Based on this data, the Easy Ensemble Classifier algorthm was performing the best.
