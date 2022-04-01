# World_Weather_Analysis


## Overview
How might we provide real-time suggestions for our client's ideal hotels? Your first task was to define what you meant by "ideal." So, over the course of the conversation, you narrowed that to hotels that were (1) within a given range of latitude and longitude and that (2) provided the right kind of weather for the client.

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

Since only about 30% of Earth is land mass, we need to generate at least 1500 (500/.3) coordinate pairs in order to get 500 cities

## Resources
Data Source: 

city_data.csv

ride_data.csv



## Results
The table below summarizes ride-sharing statistics for three city types - rural, suburban, and urban.
  
![Pyber_data_summary](analysis/Pyber_data_summary.png)
  
* Urban cities had the highest number of rides, number of drivers and total fares, and the lowest averge fare per ride and average fare per driver 
* Rural cities had the lowest number of rides, number of drivers and total fares, and the highest average fare per ride and average fare per driver
* Suburban city statistics fall in between those of Rural and Urban
* In urban cities, there were far more available drivers than demand for rides (avg fare per driver is $17), suggesting there is an imbalance between supply and demand
* In rural cities, the opposite is true - there were far more rides relative to available drivers (avg fare per driver is $55)

The chart below shows weekly fares by city type from January to April 2019. Suburban fares were roughly half those of Urban fares, while fares in Rural cities were significantly lower than Urban and Suburban.

![PyBer_fare_summary](analysis/PyBer_fare_summary.png)
 


## Summary

Recommendations based on the analysis:
1. In urban cities where there is a robust supply of drivers, PyBer can try to generate more demand for ride-sharing to increase revenue
2. Similarly, PyBer can try to generate more demand for ride-sharing in suburban and rural areas, although demand may be limited due to higher car ownership in these areas
3. To better meet demand for rides in rural cities, PyBer should try to increase the number of available drivers


