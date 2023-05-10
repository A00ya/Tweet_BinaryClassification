# Tweet_BinaryClassification

This project aims to classify tweets into two categories: positive and negative sentiment. 
The machine learning approach involves feature extraction using the scikit-learn library's bag-of-words, 
model training using logistic regression, and hyper-parameter tuning using GridSearchCV.

# Dataset

The dataset used for this project consists of labeled tweets, where each tweet is assigned a sentiment label of either positive or negative. 
The dataset should be preprocessed and formatted in a way that is suitable for feature extraction and model training.

# Feature Extraction

To represent tweets as numerical features, we will utilize the scikit-learn library's Bag-of-words which onverts each tweet into a vector of word frequencies.

# Model training 

For this project, logistic regression will be used as the classification model. Logistic regression is a popular choice for binary classification tasks. 
The scikit-learn library provides an efficient implementation of logistic regression suitable for this project.

# Hyper-parameter Tuning

To optimize the performance of the logistic regression model, hyper-parameter tuning will be performed using GridSearchCV. 
GridSearchCV exhaustively searches through a specified set of hyper-parameters and evaluates the model's performance using cross-validation.

# Conclusion

By reading this READ.Me file, you will have an idea on how to classify tweets, firstly preprocess the dataset, extract features using scikit-learn, train the logistic regression model, evaluate its performance using the accuracy score, 
and optimize the model using GridSearchCV.

Good luck!
