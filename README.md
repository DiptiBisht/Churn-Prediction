# Churn-Prediction
Use Python’s Scikit Learn to solve the churn prediction problem. The datasets for training and testing are below. It has both categorical and numeric variables.

Cell Phone Churn - TRAIN-1.csvDownload Cell Phone Churn - TRAIN-1.csv

Cell Phone Churn - TEST-1.csvDownload Cell Phone Churn - TEST-1.csv

 

Classification methods to try: Use the following methods from Scikit Learn to predict churn:

1. Multi-layer PerceptronLinks to an external site.

2. sklearn.svm.LinearSVC — scikit-learn 1.1.3 documentationLinks to an external site.

3. Decision TreeLinks to an external site.

4. Random ForestLinks to an external site.

 

To Do List:

(1) First, solve the classification problem using the default mode for all classifiers.

(2) Record accuracy, precision, recall, AUC and F1 score on the test set for each classifier in an Excel table.

(3) Now perform hyperparameter tuning on the Random Forest classifier by changing at least three different hyperparameters. Use random search for hyperparameter tuning.

(4) Describe the best parameters found through hyperparameter tuning of the Random Forest classifier. Construct a Random Forest classifier with the best parameters found.

(5) In the same Excel table, record accuracy, precision, recall, AUC and F1 score on the test set from the hyperparameter tuned Random Forest classifier.

(6) Compare the default results with the best hyperparameter tuned results for the Random Forest classifier. Did you get better results with hyperparameter tuning for any of the metrics (accuracy, precision, recall, AUC or F1 score)? If not, why not? Explain.

(7) Use the SelectKBest function (sklearn.feature_selection.SelectKBest — scikit-learn 1.1.3 documentationLinks to an external site.) to find and list the top 5 features.

(8) Perform ensemble predictions (one-layer stacking) by combining predictions from the four classifiers. Use KNN (sklearn.neighbors.KNeighborsClassifier — scikit-learn 1.1.3 documentationLinks to an external site.) as the stacking classifier.

(9) Add the stacking results to your Excel table. Did you get better results (accuracy, precision, recall, AUC or F1 score) with stacking compared to any of the prior individual classifiers, either in default mode or tuned? If not, why not? Explain.
