# 2017-Yellow-Taxi-Trip-in-NYC-Data-table-analysis-using-regression-model
The New York City Taxi and Limousine Commission (TLC) is an agency responsible for licensing and regulating New York City's taxi cabs and has partnered with Automatidata to develop a regression model that helps estimate taxi fares before the ride, based on data that TLC has gathered. 

## Overview 

Our project is focused on revolutionizing the taxi industry by implementing a predictive model to estimate taxi fare amounts prior to the ride. To accomplish this, we began with thorough Exploratory Data Analysis (EDA) on the dataset, where we unearthed significant insights. Notably, our analysis revealed a strong linear relationship between fare_amount, mean_duration, and mean_distance. Leveraging this discovery, we constructed a multiple regression model that utilizes these variables. Our model showcases impressive performance metrics, with an R^2 value of 0.86, indicating a high degree of variance explained. Furthermore, the model boasts a Mean Absolute Error (MAE) of 2.13, Mean Squared Error (MSE) of 14.32, and a Root Mean Squared Error (RMSE) of 3.78, affirming its accuracy and reliability for predicting taxi fares.

## Business Understanding

The problem we aim to address is a critical one in the taxi industry: the ability to predict fare amounts before the commencement of a ride. This challenge has significant implications for both taxi drivers and passengers. Predicting fares in advance can provide passengers with more transparency and control over their transportation expenses, allowing for better budgeting and planning. For taxi companies and drivers, accurate fare predictions can lead to improved customer satisfaction and better utilization of resources.

## Data Understanding 

This project used a dataset called "2017_Yellow_Taxi_Trip_Data.csv." merged with "nyc_preds_means.csv" The data in "2017_Yellow_Taxi_Trip_Data.csv" was gathered by the New York City Taxi & Limousine Commission and published by the city of New York as part of their NYC Open Data program. Refer to [NYC taxi dataset](https://data.cityofnewyork.us/Transportation/2017-Yellow-Taxi-Trip-Data/biws-g3hs) for more informations.

## Modeling and Evaluation 

During our modeling and evaluation phase, we put our trust in a multiple regression model to work its magic and predict fare amounts with precision. Now, take a look at the chart below. you'll see the real fare amounts and what our model predicted side by side. It proves that our model is the real deal, offering dependable fare estimates for taxi drivers and passengers, making everyone's journey a bit smoother.

Image

## Conclusion

In conclusion, our multiple regression model is a game-changer in the realm of predicting taxi fare amounts. With its ability to provide accurate and dependable fare estimates, it has the potential to revolutionize the taxi industry. Passengers can now plan their budgets more effectively, and taxi companies can optimize resource allocation.
