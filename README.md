# Credit Risk Analysis - Module 17 Challenge
## Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

### 1.) Create the training variables by converting the string values into numerical ones using the get_dummies() method.

![image](https://user-images.githubusercontent.com/87340105/155902745-07f7adde-6b99-4d1d-b91c-bbcf0ca3f9f2.png)

### 2.) Create the target variables.

![image](https://user-images.githubusercontent.com/87340105/155902757-e2961755-af46-4913-82a1-a9d282af45f1.png)

### 3.) Check the balance of the target variables.

![image](https://user-images.githubusercontent.com/87340105/155902770-3e137f3c-3906-4a0f-aec3-343a5ab8a7a0.png)

### 4.) Use the LogisticRegression classifier to make predictions and evaluate the model’s performance.

![image](https://user-images.githubusercontent.com/87340105/155902833-06cad1fb-7baa-419c-a7b8-4514fe60a3d5.png)

### 5.) Calculate the accuracy score of the model.

![image](https://user-images.githubusercontent.com/87340105/155902853-acf3609e-cb32-437b-a06c-52c0b25243c4.png)

### 6.) Generate a confusion matrix.

![image](https://user-images.githubusercontent.com/87340105/155902870-8e318e3f-d637-4d74-8e45-c777153784da.png)

### 7.) Print out the imbalanced classification report

![image](https://user-images.githubusercontent.com/87340105/155902887-32d58891-dd8e-4c13-8c4f-850508fd0f25.png)

## Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
#### Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll use a combinatorial approach of over- and undersampling with the SMOTEENN algorithm to determine if the results from the combinatorial approach are better at predicting credit risk than the resampling algorithms from Deliverable 1. Using the SMOTEENN algorithm, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

### 1.) Continue using your credit_risk_resampling.ipynb file. Resample the training data using the SMOTEENN algorithm.

![image](https://user-images.githubusercontent.com/87340105/155903184-5275210a-81d2-400f-b340-42148a23e3e4.png)

### 2.) After the data is resampled, use the LogisticRegression classifier to make predictions and evaluate the model’s performance.

![image](https://user-images.githubusercontent.com/87340105/155903191-a2e7f918-951c-4656-bf7c-21ed104ab9ff.png)

### 3.) Calculate the accuracy score of the model, generate a confusion matrix, and then print out the imbalanced classification report.

![image](https://user-images.githubusercontent.com/87340105/155903167-6d779b76-a7a2-41da-8243-1da417fb5138.png)

## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
#### Using your knowledge of the imblearn.ensemble library, you’ll train and compare two different ensemble classifiers, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and evaluate each model. Using both algorithms, you’ll resample the dataset, view the count of the target classes, train the ensemble classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

### 1.) Create your training and target variables by completing the following:
### 2.) Create the training variables by converting the string values into numerical ones using the get_dummies() method.
### 3.) Create the target variables.
### 4.) Check the balance of the target variables.
### 5.) Resample the training data using the BalancedRandomForestClassifier algorithm with 100 estimators.
### 6.) Consult the following Random Forest documentation (Links to an external site.) for an example.
### 7.) After the data is resampled, calculate the accuracy score of the model, generate a confusion matrix, and then print out the imbalanced classification report.
### 8.) Print the feature importance sorted in descending order (from most to least important feature), along with the feature score.
### 9.) Resample the training data using the EasyEnsembleClassifier algorithm with 100 estimators.
### 10.) Consult the following Easy Ensemble documentation (Links to an external site.) for an example.
### 11.) After the data is resampled, calculate the accuracy score of the model, generate a confusion matrix, and then print out the imbalanced classification report.
