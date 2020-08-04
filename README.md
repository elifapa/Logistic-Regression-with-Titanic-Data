# Logistic Regression with Titanic Data  
## Project Goal:  
Goal is to build a ML algorithm and train our data to predict whether a passenger will die or not in Titanic.
## Data Source:
Data is taken from [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) which is a kaggle competition. Dataset consists of train and test files.
Metadata can also be found on kaggle website.
## Data Description:  
This dataset consists of information of the passengers who were in the Titatic ship. Data is split into two groups, train.csv and test.csv. Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and has 12 columns, containing target variable. The `test.csv` dataset contains 418 datapoints and 11 columns.
## Conclusion:
After data is cleaned and preprocessed, it is fed into Logictic Regression ML Algorithm and it enable us to predict the target variable for test data. 
With StratifiedKFold cross validation, mean accuracy score turned out to be **0.844**
You can find the confusion matrix below.
