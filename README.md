# Bike Sharing Demand Prediction
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. As a part of Bike Sharing Demand Prediction, build a multiple linear regression model for the prediction of demand for shared bikes. 




## Table of Contents
* [General Info](#general-information)
* [Business Goals](#business-goals)
* [Model Building](#model-building)
* [Steps For Model Building](#steps-for-model-building)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, the company aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends.

The company wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands
3. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

## Business Goals
Bike Demand has to be modelled with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Model Building
In the dataset provided, you will notice that there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

## Steps for Model Building
1. Reading and Understanding Data
2. Visualising the Data
3. Data Preparation
4. Splitting the Data into Training and Testing Sets
5. Feature Scaling on the train data
6. Building the Model
7. Residual Analysis of the train data
8. Making predictions using final model
9. Model Evaluation

## Conclusions
Driving Factors for bike sharing demand:
1. Temp is the most significant with the largest coefficient and with increase in temp, cnt will increase.
2. Followed by season winter which influence demand (cnt) in positive way. However Spring season is predicted to have least demand.
3. Bike rentals is less for the month of november and july.
4. The rentals reduce Mist and Cloudy weather and Light Snow and Rain weather patterns.
5. Windspeed also has negative impact on the demand.

This indicates that the bike rentals is majorly affected by temperature, season, month, weather conditions and windspeed.



## Technologies Used
Below python libraries were used:
- pandas
- numpy
- matplotlib
- seaborn
- datetime
- calender
- sklearn
- statsmodels



## Acknowledgements
Created by Sugandha Saurabh | github - @sugandhasaurabh


## Contact
Sugandha Saurabh | github - @sugandhasaurabh



