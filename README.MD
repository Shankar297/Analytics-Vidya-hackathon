
Problem statement : 
Predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not.

Approach – 
The problem statement  is to  find the employee will leave the company or not. Here given data having two file training and testing data. Training data given employee id with all information. And testing data having only employee id. That means we have to extract the test data from train data with only employee id which is present in the test data.
	
	
Data Preprocessing – 
		Checking null value present in data or not.
		Describe data using describe method.


Feature Engineering -
    - In training data target column  is not available. Then we have do feature engineering for making target feature.
    - Here I have use the “LastWorkingDate” for checking the employee leave the  company or not.


Splitting data – 
	Use train_test_split for spliiting data


Model building-
	Apply all classification models.


Evaluation – 
   Select high accuracy and f1 score model.
  
  
  
HyperParameter tunning-
		Use GridSearchCV for hyperparameter tunning.


