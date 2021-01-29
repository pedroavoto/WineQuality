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

##### Descriptive Statistics:
- White wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105935969-bf923600-6007-11eb-975e-fbb1ee2e1771.PNG">
   </p>
- Red wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936055-e18bb880-6007-11eb-816d-93cc5e6367dd.PNG">
   </p>
   
 ##### Boxplot:
 
 - White wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936762-22d09800-6009-11eb-90c7-2eb65e02ece6.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936857-47c50b00-6009-11eb-967d-a70b6fd9f9ee.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936932-67f4ca00-6009-11eb-9c94-9c8b0fc45080.PNG">
   </p>
   
 - Red wine:
 
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105936997-8955b600-6009-11eb-821e-16ef65463f52.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937039-9bcfef80-6009-11eb-9321-59e8677a7001.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937068-abe7cf00-6009-11eb-915e-ff7ba4ef28b0.PNG">
   </p>
   
##### Histogram:

- White wine:
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937722-fddd2480-600a-11eb-847a-a92a593f7406.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937762-0f263100-600b-11eb-9315-235b56d7a5d0.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937792-1cdbb680-600b-11eb-9a08-cc125fd21564.PNG">
   </p>

- Red wine:
 
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937827-311fb380-600b-11eb-830c-40530cd4da9f.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937864-40066600-600b-11eb-9e36-d54a5300cd26.PNG">
   </p>
   <p align="center">
      <img src= "https://user-images.githubusercontent.com/49216807/105937891-4c8abe80-600b-11eb-8534-3c406aab6067.PNG">
   </p>
