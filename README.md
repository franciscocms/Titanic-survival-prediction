# Titanic-survival-prediction

Machine Learning project to predict passenger survival in Titanic disaster.\
https://www.kaggle.com/c/titanic/overview

**Dataset Preview**

<img src="https://github.com/franciscocms/Titanic-survival-prediction/blob/master/images/df_head.png" width=800>

**Feature Overview:**

*PassengerId* - passenger identification number\
*Survived* - target feature (0 or 1):
* 1 = Survived
* 0 = Not Survived

*Pclass* Each passenger class - integer feature with 3 unique values (1, 2 or 3):
* 1 = Upper Class
* 2 = Middle Class
* 3 = Lower Class


*Name*, *Sex*, *Age*

*SibSp* - total number of the passengers' siblings and spouse\
*Parch* - total number of the passengers' parents and children\
*Ticket* - ticket number of the passenger\
*Fare* - passenger fare\
*Cabin* - cabin number of the passenger\
*Embarked* - port of embarkation -> categorical feature of 3 unique values (C, Q or S):
* C = Cherbourg
* Q = Queenstown
* S = Southampton


**Classifiers explored:** 
* Random Forest: accuracy achieved (~0.75) with simple parameters tuning;
* Multi-layer perceptron (pytorch implementation): accuracy achieved (~0.78 -> personal highscore) with heavy parameters tuning + decision threshold f-score maximization on validation data;

**Higher Test Accuracy:** 0.78229 (top 23% - **ongoing**)


Link to [Kaggle Notebook!](https://www.kaggle.com/franciscosilva10/titanic-notebook)

