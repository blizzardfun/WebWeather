# WebWeather
Website to share visualized weather data from openweathermap api including graphs and data described below. 

Using Python to access APIs and analyze the JSON data this project attempts to prove what we think is the answer to the question, “What is the weather like as we approach the equator?” It attempts to answer this general question in four specific ways. It looks at the weather variation with respect to the latitude in the measurement of temperature, humidity, cloudiness, and wind speed. 
                                                
This analysis begins in the Jupyter Notebook which will retrieve the weather of 500+ cities across the world at varying distances from the equator. Cities are chosen randomly by longitude and latitude. Current weather is used for data. Using scatter plots it will show the following relationships
* 1-Temperature (F) vs. Latitude
* 2-Humidity (%) vs. Latitude
* 3-Cloudiness (%) vs. Latitude
* 4-Wind Speed (mph) vs. Latitude

It uses Python Citipy and the OpenWeatherMap API for data which is then plotted using Pandas and Matplotlib. The results of this process are a csv file of the data used and the four plots created from the data. These results are all available here.

*NOTE:To retrieve new data use the WeatherPy Jupyter notebook. You will need api keys from OpenWeatherMap in a config.py file. View the results by rendering index.html in your browser.