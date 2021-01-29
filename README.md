# Python APIs

### Part I - WeatherPy

Creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Using the [OpenWeatherMap API](https://openweathermap.org/api), create a representative model of weather across world cities.

First: create a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Second: run linear regression on each relationship, separating them into Northern Hemisphere and Southern Hemisphere:

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Part II - VacationPy

Use jupyter-gmaps and the Google Places API  to plan future vacations..



- Create a heat map that displays the humidity for every city from the part I of the homework.

- Narrow down the DataFrame to find your ideal weather condition.

- Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

  Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.