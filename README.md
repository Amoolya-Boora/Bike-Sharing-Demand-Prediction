# Bike Sharing Demand Prediction

This repository contains the Jupyter notebook and related files for predicting the demand for shared bikes using multiple linear regression. The project is aimed at understanding the factors affecting the demand for shared bikes in the American market.

## Project Description

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

BoomBikes, a US bike-sharing provider, has recently suffered considerable dips in their revenues due to the ongoing COVID-19 pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to COVID-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

The company wants to understand the factors affecting the demand for these shared bikes in the American market. The goal is to model the demand for shared bikes with the available independent variables and understand how exactly the demands vary with different features. This understanding will help in manipulating the business strategy to meet the demand levels and meet customer expectations.

## Dataset

The dataset used for this project is `day.csv`, which contains daily bike rental data. The data dictionary is provided in `Readme (1).txt`.

### Dataset Fields:
- instant: record index
- dteday: date
- season: season (1:spring, 2:summer, 3:fall, 4:winter)
- yr: year (0: 2018, 1:2019)
- mnth: month (1 to 12)
- holiday: whether the day is a holiday or not
- weekday: day of the week
- workingday: whether the day is a working day or not
- weathersit: weather situation (1: Clear, Few clouds, Partly cloudy, Partly cloudy, 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist, 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds, 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog)
- temp: temperature in Celsius
- atemp: feeling temperature in Celsius
- hum: humidity
- windspeed: wind speed
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

## Files in the Repository

- `bike_sharing_demand_prediction.ipynb`: Jupyter notebook containing the data preprocessing, EDA, model building, and evaluation.
- `day.csv`: Dataset containing daily bike rental data.
- `Readme (1).txt`: Data dictionary explaining the dataset fields.
- `README.md`: This file.

## Steps to Run the Notebook

   Open the Jupyter notebook:
   jupyter notebook bike_sharing_demand_prediction.ipynb
   Run the cells in the notebook to see the data preprocessing, EDA, model building, and evaluation steps.
   Conclusion
The notebook builds a multiple linear regression model to predict the demand for shared bikes. The model helps in understanding the significant factors affecting bike demand and provides insights that can be used to manipulate business strategies to meet customer needs and stand out in the market.
