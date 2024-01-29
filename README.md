# Titanic-Gender-Classification
Creating a model which classifies gender on the famous Titanic dataset

Titanic is one of the most famous datasets for machine learning.

We are given information about 891 titanic passengers and whether they survived or not.

As opposed to predicting if a passenger survived or not, this project has a task to build a ML model predicting the gender of passengers.

This project also includes EDA and data preprocessing followed by applying multiple different models including Logistic regression, Decision tree, Random forests, and Artificial neural networks.

Dataset source: https://www.kaggle.com/c/titanic/data

Data: The original data has been split into two groups:

1) Training set (train.csv)
2) Test set (test.csv) - This file does not contain the "Survived" column
However, since we want to predict gender as opposed to survival, we will only use the training set as the whole dataframe, and not use the test set at all.

Total nr. of rows: 891

Nr. of explanatory features: 11

Binary target variable: Sex (0 will mean Female, 1 will mean Male)

Features available:

1) PassengerId - Unique ID given to identify a particular passenger (this variable will not be used for classification)

2) Survived - Whether the passenger survived or not (0 = Did not survive, 1 = Survived)

3) Pclass - Ticket class (1 = 1st class = Upper socio-economic status, 2 = 2nd class = Middle socio-economic status, 3 = 3rd class = Lower socio-economic status)

4) Name - Name of the passenger (this variable will not be used for classification)

5) Age - Age in years

6) SibSp - Number of siblings / spouses aboard the Titanic

7) Parch - Number of parents / children aboard the Titanic

8) Ticket - Ticket number

9) Fare - Passenger fare

10) Cabin - Cabin number

11) Embarked - Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
