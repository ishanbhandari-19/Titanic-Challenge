# Titanic-Challenge
My take on the challenge [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## Preprocessing and Feature Engineering
* Dropped 'Ticket' and 'Cabin' features
* Made a new feature 'Title' by using the 'Name' feature.
* Made a new ordinal feature 'Family_size' using 'Parch' and 'SibSp'.

## Model and Accuracy
* Endemble of 11 Random Forest Classifier models for final submission.
* Accuracy : 80.861 (Public Leaderboard)

