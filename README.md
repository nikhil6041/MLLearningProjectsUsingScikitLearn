# MLLearningProjectsUsingScikitLearn
This repository contains some basic ml projects created using the scikit learn package 


# 1. Housing Price Prediction
I have created a Housing Price Prediction Model using the California Housing Dataset and after doing some preprocessing trained it on different regression
algorithms .Here , before doing any kind of training I found from the dataset that it was biased for several income ranges . So , in order to have an 
unbiased dataset I used Stratified Sampling instead of Simple Sampling. After doing all this I went on to train it on several different regression 
algorithms namely LinearRegression , DecisionTreeRegression , SupportVectorRegression , RandomForestRegression.
The best performance was given by the random forest regressor althought SVR also gave a similar performance but after finding the 
best paramters for both the models using GridSearchCV initially and RandomizedSearchCV later and performing the analysis across several cross validation sets .
I went with RandomForestRegressor to have a much better performance over test sets which may be from varied distributions . 
