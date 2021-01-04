# Python API Challenge - What's the Weather Like?

## Background
Answering the question: "What's the weather like as we approach the equator?" using Python requests, APIs and JSON traversals


![Equator](Images/equatorsign.png)


## Part I - WeatherPy

In this section, we create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

There will be 
1. scatter plots to show the following:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude


2. Linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


Here are the three observations based on the research data
1. Temperature increase as the latitude nears the equator.
2. In the Northern Hemisphere, the humidity decreases. This might be because as it gets colder up there, it tends to get drier.
3.


### Part II - VacationPy



* Heatmap that displays the humidity for every city from the part I of the homework.

  ![heatmap](Images/heatmap.png)

Ideal weather conditions and show the hotels within these weather conditions:
  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness.

  

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

  ![hotel map](Images/hotel_map.png)


### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
