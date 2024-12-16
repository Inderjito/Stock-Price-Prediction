# Stock-Price-Prediction

- The goal of this project is to build machine learning model using different classifer to determine whether to buy or sell Citigroup stock

- In this project live data was downloaded from yahoo finance from  January 2015 to August 2023

- strategy1 If the next trading day's close price is greater than today's close price then the signal is ‘buy’, otherwise ‘sell’




- strategy_2: Utilize the 50-day moving average vs the 200-day moving average. 
- A golden cross(or golden crossover) is a chart pattern that involves a short-term moving average crossing above a long-term moving average. Typically, the 50-day MA is used as the short-term average, and the 200-day MA is used as the long-term average. This is an indicator of bullish (buying) signal.

- ## The follwing step was taken to complete this project

#### Pre-process and clean the data
- Define the Feature Variable ‘X’, and the Label/Target variable ‘y’
- Spilt the data into training and test datasets (use the 80/20 percent ratio)
- Choose a Classifier and fit it on the training dataset (take its default parameters)
-  Evaluate the Classifier on the test dataset

#### The following Machine Learning Classifier was used to build model 

- K-Nearest Neighbors (KNN) 
- Random Forest Classifier (RF)
-  Gradient Boosting Classifier (GB)
- Support Vector Machines (SVMs)
-  XGBoost Classifier
