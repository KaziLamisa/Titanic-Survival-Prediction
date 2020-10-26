# Titanic Survival Prediction Competition
Data Set: https://www.kaggle.com/c/titanic

### Setup:
- Python version 3.8.3
- Pyspark version 3.0.1

### Description:
#### Task
Predict Survival of passengers based on given information.
#### Task Completion Approach: 
Used pyspark for loading, cleaning and running machine learning algorithm.
1. Load data into spark RDD.
2. Covert the RDD into a Dataframe.
3. Explore dataset
4. Analysis the features with visualisation.
5. Drop less important features.
6. Identify missing values and fillup after analysis.
7. Convert categorial features to feed the machine learning model.
8. Used Logistic Regression Model for prediction.
9. Tune Hyper Parameters using cross validation.
      
_Current Score on Kaggle: .7751_

### To-Do:
- Search for more appropriate values to fillup the missing cells.
- Find out correlations between features.
- Try different classification algorithms to upgrade score.
