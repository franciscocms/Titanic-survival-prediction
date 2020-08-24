# Titanic-survival-prediction

Machine Learning project to predict passenger survival in Titanic disaster.

**Dataset Preview**

<img src="https://github.com/franciscocms/Titanic-survival-prediction/blob/master/images/df_head.png" width=800>

Feature Overview:

**PassengerId** - passenger identification number\
**Survived** - target feature (0 or 1):
* 1 = Survived
* 0 = Not Survived

**Pclass** Each passenger class - integer feature with 3 unique values (1, 2 or 3):
* 1 = Upper Class
* 2 = Middle Class
* 3 = Lower Class


Name, Sex and Age are self-explanatory
SibSp is the total number of the passengers' siblings and spouse
Parch is the total number of the passengers' parents and children
Ticket is the ticket number of the passenger
Fare is the passenger fare
Cabin is the cabin number of the passenger
Embarked is port of embarkation and it is a categorical feature which has 3 unique values (C, Q or S):
C = Cherbourg
Q = Queenstown
S = Southampton


**Feature Engineering**


**Model explored:** Multi-Layer Perceptron
