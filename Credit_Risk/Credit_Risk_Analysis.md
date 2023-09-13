# Credit Risk Classification Report


## Overview of the Analysis


### 1.Purpose of analysis 
This analysis aims to evaluate the reliability of two supervised machine learning models in classifying whether prospective loan applications are 'healthy' or 'high-risk.


### 2. Data 
The machine learning models were created using a dataset of historical lending activity from a peer-to-peer lending services company, in order to identify the creditworthiness of borrowers. The data set included the following details:
* Loan Size
* Interest Rate
* Borrower Income
* Debt To Income
* Number of Accounts
* Derogatory Marks
* Total Debt of Borrower


### 3. Predictions
The variables we were trying to predict:
labels(y) - Series
features (X) - Dataframe
value_counts -checks the balance of the traget values.


### 3. Methodology
The analysis was performed in the following four stages:
1. PreProcessing: Use the test-train-split method to split the Data into Training and Testing Sets
2. Training: Create a Logistic Regression Model and train it using the Original Data
3. Validating:  Test the Logistic Regression Model in order to validate the reliability of the training.
4. Predicting: Predict a Logistic Regression Model with Resampled Training Data, using the RandomOverSampler module from the imbalanced-learn library to resample the data in order to further test the accuracy.


## Results
Balanced Accuracy:
Precision:
Recall:
F1-Score: 

### Machine Learning Model 1 Description:
Machine Learning Model 1 - created using the original lending data. 
  * Balanced Accuracy: 95% (0.9520479254722232)
  * Precision:
  * Recall: 
  * F1-Score:



### Machine Learning Model 2 Description:      
Machine Learning Model 1 - created using resampled data. 
  * Balanced Accuracy: 99% (0.9945026387334079)
  * Precision:
  * Recall: 
  * F1-Score:


## Summary
Machine Learning Model 2 uses the RandomOverSampler module to resample the orginal training data and address the imbalanced ratio of Heathy Loans to High-Risk Loans present in Machine Learning Model 1. Model 2 results indicate that addressing the imbalance of loan types within the data set helped to mitigate the level of bias present in Machine Learning Model 1 and ultimately led to a higher accuracy level.

## Recommendations:
Based on the results, Machine Learning Model returned the most accurate predictions and would therefore be the  Machine Learning Model of choice. 

