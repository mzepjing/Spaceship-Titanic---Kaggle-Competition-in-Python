# Spaceship-Titanic---Kaggle-Competition-in-Python


# Project Summary

## Business Challenge II - Spaceship Titanic

### Introduction
The Spaceship Titanic dataset analysis aims to predict which passengers were transported to an alternate dimension during the spaceship's collision. The dataset required cleaning and transformation to handle missing values and categorical variables. Feature engineering was performed to create new variables and analyze trends between independent variables and the dependent variable (Transported). Various machine learning models were developed and evaluated to identify the best performing model for prediction.

### Dataset Exploration
- The dataset was cleaned and transformed to handle missing values and categorical variables.
- Feature engineering was performed to create new variables.
- Initial insights were gained regarding passenger behavior, popular destinations, and correlations between variables.

### Feature Engineering
- New variables were developed to capture relevant information and improve prediction accuracy.
- Trend-based features were analyzed to understand the relationship between independent variables and the dependent variable (Transported).

### Model Development
- Multiple machine learning models were developed and evaluated to predict passenger transportation.
- Models such as DecisionTreeClassifier, RandomForestClassifier, HistGradientBoostingClassifier, and StackingClassifier were employed.
- Evaluation metrics, including accuracy scores and confusion matrices, were used to assess model performance.

### Conclusion
- The analysis provided insights into passenger behavior and trends related to transportation.
- The best performing model was the StackingClassifier with a testing accuracy of 0.8068.
- False negatives (missed predictions of transported passengers) were identified as a more critical concern than false positives.
- The analysis can assist in improving safety measures and emergency response protocols in similar disaster scenarios.
