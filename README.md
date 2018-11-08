# WebWeather
Website to share visualized weather data from openweathermap api including graphs and data described below. 

Using Python to access APIs and analyze the JSON data this project attempts to prove what we think is the answer to the question, “What is the weather like as we approach the equator?” It attempts to answer this general question in four specific ways. It looks at the weather variation with respect to the latitude in the measurement of temperature, humidity, cloudiness, and wind speed. 
                                                
This analysis begins by selecting 500 unique cities chosen randomly by their latitude. It then uses a series of API calls to OpenWeatherMap to retrieve weather data for these cities. This data is then analyzed using Jupyter Notebook and plotted using Pandas and Matplotlib. The results of this process are a csv file of the data used and the four plots created from the data. These results are all available here.
