# API-WeatherPy

## Background

In this Project, we will create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

## Steps involved

* Generate a random 500+ cities list by [citipy library](https://pypi.python.org/pypi/citipy).
* Perform weather infomation check on each city using [OpenWeatherMap API](https://openweathermap.org/api).
* Clean data
* Build a series of scatter plots to showcase the following relationships:
   * Temperature (F) vs. Latitude
   * Humidity (%) vs. Latitude
   * Cloudiness (%) vs. Latitude
   * Wind Speed (mph) vs. Latitude
* Save cities weather data retrieved as a CSV file in fold "output_data"
* save png images for each scatter plot in fold "output_data"
* Three observable trends based on the data

## Technologies Used
* Python, Numpy, Pandas
* OpenWeatherMap API, requests, json
* Matplotlib
* Jupyter Notebbok
