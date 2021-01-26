# Predicting Wine Quality

## MLP 1: Project Design and Milestone

#### Design Document
#### Motivation: What problem are you tackling?
Wine is a very popular alcoholic beverage worldwide. There are many wine applications allowing users to get professional and normal consumer ratings for a particular wine. But producers of wine would like to preemptively know the perceived quality of the wine before its distribution. 
Knowing the perceived quality of a wine allows for proper pricing of the wine and to maximize profit by focusing on those types of wine which are cheapest to produce while generating the highest perceived quality. In addition, winemakers use pH to measure ripeness in relation to acidity. Low pH wines taste tart and crisp, while higher pH wines are more susceptible to bacterial growth. Most wine pH’s fall around 3 to 4 with 3.0 to 3.4 being desirable for white wines and 3.3 to 3.6 being desirable for red wine. It would be very useful to predict the wine pH level to ensure the highest quality wine. 
This study aims to research two specific industry problems:

1.	How to predict a wine’s quality base on its physicochemical properties.
2.	How to predict the pH for wine base on other physicochemical properties 
Based on data of red and white wines from Portugal, we will try to predict the outcomes by using a regression, classification and Neural Network algorithms.
#### Method: What machine learning techniques are you planning to apply or improve upon?
•	Regression: Linear Regression with different regularizations

•	Classification: K Nearest Neighbor (KNN), Naïve Bayesian, Decision Tree, Random Forest Classifier
#### Intended experiments: What experiments are you planning to run?
•	Regression: 

  o	Compare Model Experiment:

  -	Algorithm: linear regression with different regularization
  -	Independent Variable: learning algorithms
  -	Dependent Variable: Model performance (metrics)
  
  o	Tuning Best Model Experiment:
  - Generally: Find best testing-training set ratio 
  
•	Classification:

  o	Compare Model Experiment: 

  - Algorithm: K Nearest Neighbor (KNN), Naïve Bayesian, Decision Tree, Random Forest Classifier
  - Independent Variable: learning algorithms
  - Dependent Variable: Model performance (metrics)
  
  o	Tuning Best Model Experiment:

  -	Generally: Find best testing-training set ratio
  -	These models are all tested with the same train-test data set within the framework of Cross-Validation with t number of iterations.
  
#### How do you plan to evaluate your machine learning algorithm?
•	Regression: 
  o	Framework: K-fold Cross-Validation

  o	Metrics: RMSE, R^2

•	Classification: 
  o	Framework: K-fold Cross-Validation

  o	Metrics: Confusion Matrix, ROC Curve, Precision & Recall Curve
#### Links to one or two relevant datasets.
  - https://archive.ics.uci.edu/ml/datasets/wine+quality
#### One example of prior research on the topic.
    
  - P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier,    47(4):547-553, 2009.

  - https://rstudio-pubs-static.s3.amazonaws.com/354404_c136afece292494593e4632ec8a2d65c.html

  - https://www.winespectator.com/articles/what-do-ph-and-ta-numbers-mean-to-a-wine-5035#:~:text=Low%20pH%20wines%20will%20taste,3.6%20is%20best%20for%20reds.

## MLP 2: Data Preprocessing and Exploratory Analysis

#### Datasets

#### Data preprocessing

#### Exploratory data analysis

#### Preliminary data analysis report
