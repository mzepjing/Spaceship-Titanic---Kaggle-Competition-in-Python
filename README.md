# Spaceship-Titanic---Kaggle-Competition-in-Python


# Introduction

The Spaceship Titanic dataset was not easy to work with at the beginning, this is because the test and train sets didn’t have the same columns, in fact, the test was missing the independent variable, “Transported”. That said, we first had to clean the train set by dealing with missing values as well as transforming categorical variables into 1 and 0. And did the same for the test set.

In addition, to adjust the scale of variables as well as to deal with skewness we executed logarithmic transformation and standardization for some of the variables.

This allowed us to have the database ready, and from that point on, 9 models were applied in order to find the one that predicted “Transported” the best, which ended up being the StackingClassifier model.



# Index

Dataset Exploration

* Importing libraries
* Setting Pandas print options
* Loading dataset
* Exploring dataset


Feature Engineering

* Developing new variables
* Trend-Based Features between the dependent variable (Transported) and independent variables 



Model Development

* Plotting predictions
* Developing candidate statmodels (chechking R-squared, p-values and correlations)
* Final Models 
    * KNeighborsClassifier
    * RandomForestClassifier
    * AGradientBoostingClassifier
    * Tunned KNeighborsClassifier
    * HistGradientBoostingClassifier
