# World_Weather_Analysis


## Summary

In this Challenge, we used API requests to gather and visualize data from internet sites:
- retrieve weather data from OpenWeatherMap API
- retrieve hotel data from Google's Places API
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




