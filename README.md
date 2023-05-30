# High-velocity-tweets-classification
Live tweets streaming sentiment analysis 

## Method:  
Our approach is making twitter sentiment prediction is to first train a Naive Bayes model of twitter sentiment prediction using a given labled dataset at Kaggle.
We then save the trained model and will load and use it subsequently in a streaming application. We use Databricks (PySpark and PySpark SQL) for this task.

## Steps (order of execution):
1. NB model
2. Tweetread
3. Tweet live preds
