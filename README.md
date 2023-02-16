# credit_analysis
# Overview of the loan prediction risk analysis: 
### Explain the purpose of this analysis.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we’ll oversample the data using the **RandomOverSampler and SMOTE algorithms**, and **undersample the data using the ClusterCentroids algorithm**. Then, we’ll use a combinatorial approach of over and undersampling using the **SMOTEENN algorithm**. Next, we’ll compare two new machine learning models that reduce bias, **BalancedRandomForestClassifier and EasyEnsembleClassifier**, to predict credit risk. Once we done, we’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results: 
### Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

**Deliverable 1: Use Resampling Models to Predict Credit Risk**
Using your knowledge of the **imbalanced-learn and scikit-learn libraries**, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the **oversampling RandomOverSampler and SMOTE algorithms**, and then you’ll use the **undersampling ClusterCentroids algorithm**. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.


in credit_risk_resampling.ipynb, and save it to your Credit_Risk_Analysis folder.

Using the information we’ve provided in the starter code, create your training and target variables by completing the following steps:

Create the training variables by converting the string values into numerical ones using the get_dummies() method.
Create the target variables.
Check the balance of the target variables.
Next, begin resampling the training data. First, use the oversampling RandomOverSampler and SMOTE algorithms to resample the data, then use the undersampling ClusterCentroids algorithm to resample the data. For each resampling algorithm, do the following:

Use the LogisticRegression classifier to make predictions and evaluate the model’s performance.
Calculate the accuracy score of the model.
Generate a confusion matrix.
Print out the imbalanced classification report.
![image](link)
![image](link)
![image](link)
![image](link)
![image](link)





# Summary: 
### Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.There is a summary of the results.There is a recommendation on which model to use, or there is no recommendation with a justification


