# Natural-Language-Processing-Project
Using Yelp review data set from kaggle.com
Used CountVectorizer from Scikit Learn to convert review text to a sparse matrix of individual word counts for each review.
The data was then split into test and train sets and the following models were applied using Scikit Learn:
* Naive Bayes Classifier
* Random Forest Classifier
* Logistic Regression
* K Nearest Neighbours with 3 neighbours

The logistic regression model gave the most accurate predictions, with an average F1 score of 93% 
