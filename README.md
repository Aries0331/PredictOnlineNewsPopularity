# Predicting News Popularity in Social Networks

## Background
The project aims to extract value and opportunity from the publication of online news
articles by maximizing the popularity of articles, measured by the number of shares on
social media, to optimize the content creation process for delivering the most benefit at
the least cost.

## Mythology
* Data: The dataset contains features describing the sentiment of the text and title after Natural
Language Processing (NLP), the characteristics of the word features and the article, the
dependent feature of number of article shares and other ancillary information variables
for the articles on Mashable.com during 2013-2015.
* Explore Dataset
  * Draw correlation matrix and hypothesis graphs on the relationships between certain features
  * Principal Component Analysis: the PCA plot shows that in order to achieve a 95% explained variance in the independent set, we need around 35 variables, which is a significant reduction from 58 initial ones
* Feature Importance: By implementing classification tree and classification random forest, we can find top features that affect the popularity of news
* Comparing of different Machine Learning models  
  
Regression | RMSE (With 10-fold CV)
------------ | -------------
Linear Regression | 11760.99
Laso | 11656.98
Ridge | 11024.96 

  
Classification | Accuracy
------------ | -------------
Logistic Regression | 0.599
Decision Tree | 0.637
Random Forest | 0.661 
KNN(K=30) | 0.584
