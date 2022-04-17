# python-api-challenge

Part 1: WeatherPy
* Created a Python script to visualize the weather of 500+ cities of varying distance from the equator
* Used a Python library and the OpenWeatherMap API to create a representative model of weather across cities

Created a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Computed the linear regression for each relationship:
* By separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Part 2: VacationPy
Worked with weather data to plan future vacations
* Used Jupyter-gmaps and the Google Places API 

Created a heat map that displays the humidity for every city from Part 1

Narrowed down the DataFrame to find ideal weather condition:
* A max temperature lower than 80 degrees but higher than 70
* Wind speed less than 10 mph
* Zero cloudiness

Used Google Places API to find the first hotel for each city located within 5,000 meters of specific coordinates
* Ploted the hotels on top of the humidity heatmap, with each pin containing the Hotel Name, City, and Country
