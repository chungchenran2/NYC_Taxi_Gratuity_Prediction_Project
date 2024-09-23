# NYC Taxi Gratuity Prediction Project

## Overview

The goal of this project was to create a multiple linear regression, random forest, and XGBoost model to predict high rider gratuity or not. This project utilized yellow taxi trips taken in New York City during 2017. The final random forest model performed with 68.7% accuracy, 67.5% precision, and 77.9% recall in determining which riders would be generous tippers and which riders would be non-generous tippers. The final XGBoost model performed with 67.9% accuracy, 67.7% precision, and 74.5% recall in determining which riders would be generous tippers and which riders would be non-generous tippers. Based on the XGBoost model, the Taxicab Passenger Enhancements Program (TPEP) provider, predicted ride fare, and mean trip duration were most influential in determining a generous tipper (>20%) vs a non-generous one (<20%).

## Business Understanding

According to salary.com the average salary for a New York Taxi Driver is around $45,000. This salary is significantly low compared to a median rent value of $6,500 per month. It is important to understand what factors encourage riders to leave tips in order to help drivers obtain a livable wage.

## Data Understanding

The NYC Taxi and Limousine Commission data came from NYC.gov. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. 
![Non-Generous vs Generous Tippers](https://github.com/chungchenran2/NYC_Taxi_Gratuity_Prediction_Project/blob/main/Images/Non-Generous_Generous_Tippers.png)
In connection to this, a feature was engineered to represent if a ride was taken during rush hour or not. Multiple redundant columns were dropped and reformatted into the proper data type.

## Modeling and Evaluation



## Conclusion

