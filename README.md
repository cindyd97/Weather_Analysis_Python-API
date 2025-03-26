# Analyzing Weather and Vacation Recommendations with Python and API
- Weather Analysis
- Vacation Recommendations

### Weather Analysis Description:
This assignment involves creating a python script to visualize the weather of 500 cities of varying distances from the equator. The code utilizes the citipy library and data using an API call. A list of cities is created using latitude and longitude coordinates and an API call is made on the weather data for each city. The data information for each city includes: max temperature, humidity, cloudiness, wind speed, country, and date. The city data is saved to a CSV file. The code includes visualizing the data in scatter plots for both the northern and southern hemispheres to view: latitude vs. temperature, latitude vs. humidity, latitude vs. cloudiness, and latitude vs. windspeed. Then a linear regression is computed for each scatter plot to understand the r-squared value and slope/formula of the linear regression model.

### Vacation Recommendation Description:
This part of the assignment utilizes the city data that was saved to a CSV file in the first part of this assignment. A visual map is created that plots each city in the city dataset and sizes the plots based on humidity. The city data is filtered with parameters specifying ideal weather conditions for humidity, cloudiness, and windspeed. An API call is used to retrieve the nearest resort based on the ideal weather conditions of the filtered data set using the city name and coordinates. Another visual map is created that plots the resorts based on ideal weather conditions showcasing recommended vacation spots to visit.

### Language:
- Python

### Data Source:
- OpenWeatherMap. (n.d.). OpenWeatherMap API [API documentation]. OpenWeatherMap. Retrieved December 13, 2024, from https://openweathermap.org/api
- Geoapify. Geoapify API. Retrieved December 13, 2024, from https://apidocs.geoapify.com/docs/places/

### Details:
- [Weather Analysis code](https://github.com/cindyd97/Weather_Analysis_Python-API/blob/main/WeatherPy/WeatherPy.ipynb)
- [Vacation Recommendation code](https://github.com/cindyd97/Weather_Analysis_Python-API/blob/main/WeatherPy/VacationPy.ipynb)
- [City Data CSV](https://github.com/cindyd97/Weather_Analysis_Python-API/blob/main/WeatherPy/output_data/cities.csv)



