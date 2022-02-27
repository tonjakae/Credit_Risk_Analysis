# Credit_Risk_Analysis
## Module 17 Challenge
### Deliverable 1: Use Resampling Models to Predict Credit Risk
#### Using your knowledge of the imbalanced-learn and scikit-learn libraries, you’ll evaluate three machine learning models by using resampling to determine which is better at predicting credit risk. First, you’ll use the oversampling RandomOverSampler and SMOTE algorithms, and then you’ll use the undersampling ClusterCentroids algorithm. Using these algorithms, you’ll resample the dataset, view the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

Create training and target variables by completing the following steps:

* Create the training variables by converting the string values into numerical ones using the get_dummies() method.

![image](https://user-images.githubusercontent.com/87340105/155902745-07f7adde-6b99-4d1d-b91c-bbcf0ca3f9f2.png)

* Create the target variables.

![image](https://user-images.githubusercontent.com/87340105/155902757-e2961755-af46-4913-82a1-a9d282af45f1.png)

* Check the balance of the target variables.

![image](https://user-images.githubusercontent.com/87340105/155902770-3e137f3c-3906-4a0f-aec3-343a5ab8a7a0.png)

* Use the LogisticRegression classifier to make predictions and evaluate the model’s performance.

![image](https://user-images.githubusercontent.com/87340105/155902833-06cad1fb-7baa-419c-a7b8-4514fe60a3d5.png)

* Calculate the accuracy score of the model.

![image](https://user-images.githubusercontent.com/87340105/155902853-acf3609e-cb32-437b-a06c-52c0b25243c4.png)

* Generate a confusion matrix.

![image](https://user-images.githubusercontent.com/87340105/155902870-8e318e3f-d637-4d74-8e45-c777153784da.png)

* Print out the imbalanced classification report

![image](https://user-images.githubusercontent.com/87340105/155902887-32d58891-dd8e-4c13-8c4f-850508fd0f25.png)
