# Project-4

### **Group 6**  
__Team members:__\
:point_right:Myrna Deseo\
:point_right:Mohammed Hamdouna\
:point_right:Rasika Senadheera

 ![image](https://user-images.githubusercontent.com/110227464/214265971-b7b7752e-e9aa-4a99-8671-b317adb6cce7.png)


## CO<sub>2</sub> Emissions Quantifying Sources and Emission Levels   (Kaggal)
https://www.kaggle.com/datasets/thedevastator/global-fossil-co2-emissions-by-country-2002-2022

About the dataset:\
This dataset provides an in-depth look into the global CO2 emissions at the country-level, allowing for a better understanding of how much each country contributes to the global cumulative human impact on climate. It contains information on total emissions as well as from coal, oil, gas, cement production and flaring, and other sources. The data also provides a breakdown of per capita CO2 emission per country - showing which countries are leading in pollution levels and identifying potential areas where reduction efforts should be concentrated. This dataset is essential for anyone who wants to get informed about their own environmental footprint or conduct research on international development trends.

## Objective:
1. Visualisations of the CO2 emission by country.
2. Determine the top 15 countries that has highest CO2 emission.
3. Track a country’s progress in reducing CO2 emissions.
4. Determine models that best predict the target parameter (total CO2 emissions) with an accuracy of greater than 75%


### Data Cleanup - checked for missing values using a visual matrix (below)
![image](https://user-images.githubusercontent.com/110227464/215319767-7b6686e7-4efd-4308-be57-f446590e6d23.png)


Visualisations:
![image](https://user-images.githubusercontent.com/110227464/215319900-d2dd9bda-2ec6-4441-8e93-9e9d65d3af68.png)

![image](https://user-images.githubusercontent.com/110227464/215319944-4a75492f-2db7-4773-9028-cafb8cc5d995.png)

![image](https://user-images.githubusercontent.com/110227464/215320078-161cf17c-14f0-4fdc-88a6-ffaca9307d9d.png)


Before choosing the model, following were considered:

- Classification or Regression? (Supervised Learning)
- Clustering or Dimensionality Reduction? (Unsupervised Learning)
- Reinforcement Learning? 

![image](https://user-images.githubusercontent.com/110227464/215320433-2e074957-6b29-4389-a1cd-faa22e397546.png)


### Following achieved using "train_test_split" from sklearn
**Linear Regression**
  + Training Score: 99.99 %
  + Testing Score: 99.99 %

**Lasso Regression**
  + Training Score: 99.99 %
  + Testing Score: 99.99 %

**Ridge Model**
  + Training Score: 99.99 %
  + Testing Score: 99.99 %

**Elastic Net Model**
  + Training Score: 98.48 %
  + Testing Score: 98.89 %


### Using manual split with .loc[] with 70% training data and 30% testing data
**Linear Regression**
+ Training Score: 99.99 %
+ Testing Score: 99.99 %

**Lasso Regression**
+ Training Score: 99.99 %
+ Testing Score: 99.99 %

**Ridge Model**
+ Training Score: 99.99 %
+ Testing Score: 99.99 %

**Elastic Net Model**
+ Training Score: 97.17 %
+ Testing Score: 99.37 %


# Conclusion
* The top 15 CO2 producing countries are consistent through the five main sources (coal, oil, gas, cement, flaring).\
* Clear downward trend in CO2 emission from coal were observed in both the USA and Australia.\
* Four models were used (linear, lasso, ridge and elastic net) to best predict the total CO2 emissions.\
* All four models showed an accuracy of greater than 95%.
