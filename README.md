# A study on SMS Spam Classification using Naive Bayes.
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
Credit card companies need to have the ability to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
Datasets contains transactions made by credit cards in September 2013 by european cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.


The data contains only numerical input variables which are the result of a PCA transformation. 
Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data.

The objective is to build a model to classify and predict if a transaction is fraudulent.

`Predictors:`
```
V1, V2, ... V28 are the principal components obtained with PCA.
The only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
```

`Target:`
```
Output (0: Not Fraud, 1: Fraud)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud/home).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_Naive_Bayes_Spam_Classification/blob/master/Naive%20Bayes%20-%20Spam%20Classifier.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
      3.1 Visualizing the Variables
      3.2 Data Cleaning
    4 Train Test Split
    5 Select and Train a Model
      5.1 Naive Bayes Model
    6 Apply Model on Test Set
    ```   

### Model Performance
The model has an average `Precision` and `Recall` of 99%.
![alt text](https://github.com/zhenyu92/ML_Naive_Bayes_Spam_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
