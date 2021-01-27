# Predicting Wine Quality

## MLP 1: Project Design and Milestone

### Design Document
### Motivation: What problem are you tackling?
Wine is a very popular alcoholic beverage worldwide. There are many wine applications allowing users to get professional and normal consumer ratings for a particular wine. But producers of wine would like to preemptively know the perceived quality of the wine before its distribution. 
Knowing the perceived quality of a wine allows for proper pricing of the wine and to maximize profit by focusing on those types of wine which are cheapest to produce while generating the highest perceived quality. In addition, winemakers use pH to measure ripeness in relation to acidity. Low pH wines taste tart and crisp, while higher pH wines are more susceptible to bacterial growth. Most wine pH’s fall around 3 to 4 with 3.0 to 3.4 being desirable for white wines and 3.3 to 3.6 being desirable for red wine. It would be very useful to predict the wine pH level to ensure the highest quality wine. 
This study aims to research two specific industry problems:

1.	How to predict a wine’s quality base on its physicochemical properties.
2.	How to predict the pH for wine base on other physicochemical properties 
Based on data of red and white wines from Portugal, we will try to predict the outcomes by using a regression, classification and Neural Network algorithms.
### Method: What machine learning techniques are you planning to apply or improve upon?
•	Regression: Linear Regression with different regularizations

•	Classification: K Nearest Neighbor (KNN), Naïve Bayesian, Decision Tree, Random Forest Classifier
### Intended experiments: What experiments are you planning to run?
•	Regression:&nbsp; 

  o	Compare Model Experiment:

  -	Algorithm: linear regression with different regularization
  -	Independent Variable: learning algorithms
  -	Dependent Variable: Model performance (metrics)
  
  o	Tuning Best Model Experiment:
  - Generally: Find best testing-training set ratio 
  
•	Classification:&nbsp;

  o	Compare Model Experiment: 

  - Algorithm: K Nearest Neighbor (KNN), Naïve Bayesian, Decision Tree, Random Forest Classifier
  - Independent Variable: learning algorithms
  - Dependent Variable: Model performance (metrics)
  
  o	Tuning Best Model Experiment:

  -	Generally: Find best testing-training set ratio
  -	These models are all tested with the same train-test data set within the framework of Cross-Validation with t number of iterations.
  
### How do you plan to evaluate your machine learning algorithm?
•	Regression:&nbsp; 

  o	Framework: K-fold Cross-Validation

  o	Metrics: RMSE, R^2

•	Classification:&nbsp; 

  o	Framework: K-fold Cross-Validation

  o	Metrics: Confusion Matrix, ROC Curve, Precision & Recall Curve
### Links to one or two relevant datasets.
  - https://archive.ics.uci.edu/ml/datasets/wine+quality
### One example of prior research on the topic.
    
  - P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier,    47(4):547-553, 2009.

  - https://rstudio-pubs-static.s3.amazonaws.com/354404_c136afece292494593e4632ec8a2d65c.html

  - https://www.winespectator.com/articles/what-do-ph-and-ta-numbers-mean-to-a-wine-5035#:~:text=Low%20pH%20wines%20will%20taste,3.6%20is%20best%20for%20reds.

## MLP 2: Data Preprocessing and Exploratory Analysis

### Datasets

The dataset selected are related to red and white wine from a specific region called Minho in the north-western of Portugal. The dataset has attributes such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol that was measured from samples in the laboratory. Moreover, the dataset also contains classification of the wine measured by a group of three assessors, using blind tastes, that is qualified from 0 to 10 the quality of the wine.  
##### Dataset Size:  

  - Red wine: 1599 records, 12 attributes

  - White wine: 4898 records, 12 attributes
  
##### Data samples
   - White wine:
    <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935340-a76de700-6006-11eb-926e-4ee285d75c54.PNG">
    </p>
    <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935380-bb194d80-6006-11eb-8ac1-79a5926cb820.PNG">
    </p>
    
   - Red wine:
    <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935508-e9972880-6006-11eb-973c-8d18333459bc.PNG">
    </p>
    <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935550-fe73bc00-6006-11eb-9c07-d46d180b10e1.PNG">
    </p>

##### Brief description of each attribute: 

- Fixed acidity: most acids involved with wine or fixed or nonvolatile (do not evaporate readily) --- (tartaric acid - g / dm^3)

- Volatile acidity: the amount of acetic acid in wine, which at too high of levels can lead to an unpleasant, vinegar taste --- (acetic acid - g / dm^3)

- Citric acid: found in small quantities, citric acid can add ‘freshness’ and flavor to wines --- (g / dm^3)

- Residual sugar: the amount of sugar remaining after fermentation stops, it’s rare to find wines with less than 1 gram/liter and wines with greater than 45 grams/liter are considered sweet --- (g / dm^3)

- Chlorides: the amount of salt in the wine --- (sodium chloride - g / dm^3)

- Free sulfur dioxide: the free form of SO2 exists in equilibrium between molecular SO2 (as a dissolved gas) and bisulfite ion; it prevents microbial growth and the oxidation of wine --- (mg / dm^3)

- Total sulfur dioxide: amount of free and bound forms of S02; in low concentrations, SO2 is mostly undetectable in wine, but at free SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and taste of wine --- (mg / dm^3)

- Density: the density of water is close to that of water depending on the percent alcohol and sugar content --- (g / cm^3)

- pH: describes how acidic or basic a wine is on a scale from 0 (very acidic) to 14 (very basic); most wines are between 3-4 on the pH scale --- (pH)

- Sulphates: a wine additive which can contribute to sulfur dioxide gas (S02) levels, wich acts as an antimicrobial and antioxidant --- (potassium sulphate - g / dm3)

- Alcohol: the percent alcohol content of the wine --- (% by volume)

- Quality: output variable --- (based on sensory data, score between 0 and 10)
    
##### Appropriate measures of the central tendency and dispersion for attributes: 
- White wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935969-bf923600-6007-11eb-975e-fbb1ee2e1771.PNG">
   </p>
- Red wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936055-e18bb880-6007-11eb-816d-93cc5e6367dd.PNG">
   </p>

### Data preprocessing

### Exploratory data analysis

### Preliminary data analysis report
