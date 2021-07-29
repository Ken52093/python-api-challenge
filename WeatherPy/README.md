# Python API Homework - What's the Weather Like?

## Part I - WeatherPy

In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, you'll be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

* For Part I, you must include a written description of three observable trends based on the data.
1. Highest temperature is found between 20 to 49 latitude and as the latidude increases or decreases, temperature drops.
2. Cloudiness data and wind speed are both widely spread across the latitude. Therefore, latitude doesn't have a strong iinfluence on cloudiness and wind speed. The speed of the wind is controlled by the strength of the air pressure gradient, the stronger the pressure gradient the higher the wind speed.

Your first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (c) vs. Latitude
![](../output_data/City_Latitude_vs_Max_Temperature.png)
* Humidity (%) vs. Latitude
![](../output_data/City_Latitude_vs_Humidity.png)
* Cloudiness (%) vs. Latitude
![](../output_data/City_Latitude_vs_Cloudiness.png)
* Wind Speed (mph) vs. Latitude
![](../output_data/LatitudeWind.png)


