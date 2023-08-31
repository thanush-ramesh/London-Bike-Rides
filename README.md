# London Bike Rides
This repository contains my analysis for the [London Bike Rides](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) dataset offered by Kaggle. This README provides an overview of the project, its purpose, data sources, and the Tableau Dashboard. Moreover, used [Python](https://github.com/thanush-ramesh/London-Bike-Rides/blob/main/London-Bike-Data-Python-File.ipynb) to read the csv file in pandas dataframe, data manipulation as well as data exploration ( such as finding the Unique values in seasons column and weather code column, to rename the columns, to create a dictionary for weather and season to map the integer to actual written values, to write final dataframe into an excel sheet.

## Purpose
The purpose of this project is to analyze the London Bike Rides data and get insights from the data such as : Moving Average Bike Rides, Total bike rides in London between any given dates, Popular weather to ride bikes, Peak time to ride bikes. By visualizing the insights on Tableau, made the data more readable, interactive and easy to understand. 

## Data Source
The source of data is from [Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset) or [Source Dataset](https://github.com/thanush-ramesh/London-Bike-Rides/blob/main/london_merged.csv). The dataset includes information such as :
- timestamp"       - timestamp field for grouping the data
- "cnt"            - the count of a new bike shares
- "t1"             - real temperature in C
- "t2"             - temperature in C "feels like"
- "hum"            - humidity in percentage
- "wind_speed"     - wind speed in km/h
- "weather_code"   - category of the weather
- "is_holiday"     - boolean field - 1 holiday / 0 non holiday
- "is_weekend"     - boolean field - 1 if the day is weekend
- "season"         - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

## Tableau Visualization
The Tableau Dashboard provides for a interactive experience with the dataset, which sums up all the insights into one place.
I have visualized the data for : Moving Average Rides, Total Number of Bike Rides, Heatmap( which displays the count of new bike shares in a Temperature vs Wind Speed map), Peak Ride time, Popular weather to ride Bikes.

[Click here](https://public.tableau.com/app/profile/thanush.ramesh3122/viz/LondonBikeRides_16933440804420/Dashboard1) for Tableau Visualization

