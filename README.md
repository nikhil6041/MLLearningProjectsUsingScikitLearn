# MachineLearningPracticeProjects
This repository contains all the ml projects which I have worked on for learning purposes.


# 1. Housing Price Prediction
I have created a Housing Price Prediction Model using the California Housing Dataset and after doing some preprocessing trained it on different regression
algorithms .Here , before doing any kind of training I found from the dataset that it was biased for several income ranges . So , in order to have an 
unbiased dataset I used Stratified Sampling instead of Simple Sampling. After doing all this I went on to train it on several different regression 
algorithms namely LinearRegression , DecisionTreeRegression , SupportVectorRegression , RandomForestRegression.
The best performance was given by the random forest regressor althought SVR also gave a similar performance but after finding the 
best paramters for both the models using GridSearchCV initially and RandomizedSearchCV later and performing the analysis across several cross validation sets .
I went with RandomForestRegressor to have a much better performance over test sets which may be from varied distributions . 
# 2. Avocado Price Prediction
In this project , it was the first time I dealt with time series data . I came to know about the fb-prophet package and do recommend everyone to have a look upon it . It's usage is pretty much similar to scikit-learn.I built a ml model which was able to predict future prices of the avocado .The dataset I used can be found in the datasets section of this repository.
# 3. Car Price Prediction
Instead of the scikit-learn I have used keras with tensorflow as a backend to build a model able to predict the future prices of the cars.
# 4. Cats Vs Dogs
Well , hopefully I guess this is the first model almost every novice ml practitioner who is getting started with cnns atleast encounter once . This is a large dataset which can be found from kaggle although I didn't use the entire dataset , I developed four different ml models each giving a better performance as compared to the previous one . First I used a small neural network to train my model but it was overfitting so I moved to create synthetic data using data augmentation but that also was overfitting not as bad as the previous model . So , I went to use a pretrained model the VGG16 with pretrained weights it gave me a decent performance although in my final model I unfreezed some of its layers and retrained the whole model which gave me a better performance than all the previous models.
# 5. ChicagoCrimeRatePrediction
This task also has a time-series based data which is available on kaggle . I have used the fb-prophet model for this particular task although I might try soon with deep learning based and update this notebook.
# 6. CIFAR10
In this project I have built a cnn model for predicting classes of different images . The dataset being used here is CIFAR10 which is also available on various online platforms. I have used the built in dataset from the keras datasets for this particular task.
# 7. EmailForecasting
A basic machine learning based approach to classify the mails as spam or ham . I will be updating this project with a new notebook which will be based on deep learning methods.
# 8. ImplementingDeepDream
An attempt to implement the deepdream model created by google . I have built it taking help from several text materials and online blogs .
# 9. Traffic sign classification
Built a cnn model to classify from different traffic signs . 
# 10. Yelp Reviews 
Did a sentiment analysis from the reviews present in the dataset.
