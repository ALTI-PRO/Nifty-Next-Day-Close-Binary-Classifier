# Nifty-Next-Day-Close-Binary-Classifier

This is a binary classifier based on 4 commonly used technical indicators. The data is not being treated as a timeseries. Classification has been done using the following models:

1) XG Boost
2) Random Forest
3) KNN
4) Decision Tree 
5) Naive Baise 

Based on F1 scores, XGBoost performed the best.

Reason for Selecting XB Boost:
Five different models were traine on the same data. The performance was compared based on weighted average f1 score. They have been listed below in descending order of their performance. XG boost outperformed all these models
XG Boost: 52, Random Forest - 0.50, KNN - 0.51, Decision Tree - 0.47, Naive Baise - 0.41

How can we improving the performance?
1) and Feature Engineering To boost the models performance, some proprietory indicators can be created based on research.
2) Feature selection Including more indicators of different classes might help imporove the performance of the model. For eg. including the data from the derivatives market such as OI can help the model with market sentiment. We can also include data from social media, macroeconomic indicators, bond yields etc.
3) Optimizing Indicator Parameters Short term and long term trends can be defined with slower and faster parameters for the indicators.
4) Tuning Hyper Parameters of the Mode
There are many parameters of the model which the models do not learn during training. Thus tuning the hyperparameters might give a performance boost
