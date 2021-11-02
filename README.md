# Titanic-Machine-Learning-from-Disaster-Kaggle
Played around with the Titanic Dataset to predict whether a person survives or not. (https://www.kaggle.com/c/titanic)

## Preprocessing and Feature Engineering
* Dropped 'Ticket' and 'Cabin' features
* Used an unknown token "U" for null points in 'Embarked' variable
* Used median to fill the null points in 'SibSp', 'Parch', 'Fare' and 'Age'

## Model and Accuracy
* LogisticRegression
* Accuracy : 76.31 (Public Leaderboard)

