# supervised-machine-learning-challenge
Module 19 Challenge

# Description
Learning is the foundation of humanity. The ability to problem solve and learn from past mistakes has allowed humans to survive for this long. But what if computers could learn and problem solve as well. While society is not quite at the apocalyse at the hands of Skynet nor is Arnold Schwarzenegger telling us come with him if we want to live, there are many examples of machines learning. Through the use of algorithms to build a model or method based on sample data, machine learning is broadly defined as a machine's capability to imitate intelligent human behavior.

While there are many approaches to machine learning, this challenge focuses on supervised learning. Supervised learning uses labeled datasets to train algoirthms to classify data or predict outcomes accurately, such as whether a loan will or will not be approved. Using the scikit-learn library and lending data, this challenge builds two models: logisitc regression and random forest classifier to predict loan approvals.

In this repository, there is a Resources folder containg the lending data in CSV format and a Jupyter notebook entitled Credit Risk Evauluator that contains script of data prepocessing and model building and scoring. There is also Supervised Machine Learning Challenge folder containing two child folders with Jupyter notebooks that correspond to the two model used: LogisticRegression and RandomForestClassifier

Below is a summary of the steps to achieve the final models:

1. Assign the data the either X or y.
2. Split the data training and testing datasets
3. Initialize scaler model by fitting on the training data and transform the data.
4. Initialize logistic regression or random forest classifier by fitting on the scaled training data.
5. Score each model.

# Predictions
Logistic regression performs better when the noise variables are less than or equal to the explanatory variables. Considering the number of dimensions or columns of data and their particular relevance to credit score, I predict the logistic regression to perform better than random forest classifier. In addition, there are not any categorical dimensions in the data indicating logistic regression would perform better.

# Conclusions
The logistic regression model scored 99.4% and the random forest classifier model scored 99.2%. By an thin, almost negligible margin, logistic regression performed better. It is best to say both models perform well. 
