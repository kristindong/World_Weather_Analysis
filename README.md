# World_Weather_Analysis


## Summary

In this Challenge, we used API requests to gather and visualize data from internet sources:
- retrieve weather data using OpenWeatherMap API
- retrieve hotel data using Google's Places API
- create map visualizations using Google's Maps JavaScript API and Directions APIs
- we requested the data in json format, which organizes data in lists and dictionaries

To get weather and location data, we first had to generate coordinates (latitude-longitude pairs)
- the coordinates were generated using the numpy random number generator
- we then used the "citipy" module to map the coordinates to city names
- we used the zip/list functions to store and retrieve the large set of coordinates


In the module but not in the Challenge, we also explored linear regression using the "linregress" module from "scipy.stats" library:
- from scipy.stats import linregress
- (slope, intercept, r_value, p_value, std_err) = linregress(x_values, y_values)
- regress_values = x_values * slope + intercept


Map showing cities where current temperature is between 75 and 90 degrees

![WeatherPy_vacation_map](Vacation_Search/WeatherPy_vacation_map.png)


Map showing Google driving route for a sample 4-city itinerary

![WeatherPy_travel_map](Vacation_Itinerary/WeatherPy_travel_map.png)


Map showing location and weather condition for the 4 cities

![WeatherPy_travel_map_markers](Vacation_Itinerary/WeatherPy_travel_map_markers.png)



