# Online Retail Business Customers

ML-Classification, Python-JupyterNB

The purpose of this analysis is to create a model that is capable (with a certain degree of accuracy) of predicting whether or not a customer will contribute to the sales revenue of an online retailer. To be able to do so, we shall train and test Classifiers on an existing customer dataset that has been sourced from the UCI Machine Learning Repository (Web Link: https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

The dataset consists of 12,330 online customers of an undisclosed online retailer and, comprises of 10 numerical features and 8 categorical features. 

The feature termed 'Revenue' takes up the value, 'TRUE' for those customers that had made purchases online and 'FALSE' for those customers that had not. The dataset consists of 10,422 customers where 'Revenue' = 'FALSE' and 1908 customers where 'Revenue' = 'TRUE'. On being able to predict the 'Revenue' identification of new customers, we may be able to gain an insight into the effectiveness of targetted- marketing strategies while also gaining an insight into how the strategies can be optimised. For instance, a greater portion of marketing efforts can be focused on new customers who are predicted to make purchases online.

The two classification techniques we will be utilising, is the K-Nearest Neighbour[s] classifier and the Gaussian-Naive Bayes Classifer. For both classifiers, we shall train and test the model on the same dataset using the K-Fold Cross Validation method. We will then utilise Pipelines to construct several models at once (based on several hyperparameter values and feature selection methods). From all the models that are created, we shall pick the one with the highest performance metric.

