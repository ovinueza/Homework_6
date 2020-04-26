# WeatherPi

## Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. This project uses Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you **prove** it?

## Task
This is a 2 part project

In the first part (this repository) I analyze the data performing API calls and retrieve weather information on over 500 random cities. 

After retrieving the data I made scatter plots to show the effect that latitude has in relationship to temperature, humidity, cloudiness and windspeed.

The second part for this project involves adding the reslting graphs into a simple Web Dashboard and can be found [here](https://github.com/ovinueza/Web_Visualization_Dashboard)

## Findings
Based on the analyzed data there is no relationship between latitude and cloudiness.
<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_Cloudiness.png">
</p>

Most of the cities located along the equator have high humidity during the summer.

Cities that have similar latitudes may differ greatly in their levels of humidity, based on how close they are to the ocean and other large bodies of water.

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_Humidity.png">
</p>

Based on data collected in mid July, cities along the equator and 20 degrees latitude have high temperatures, but cities in between the 18 to 42 degree latitudes have the highest temperatures. This may be due to the summer season and geographical location.

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_MaxTemp.png">
</p>

There is not a strong relationship between windspeed and latitude, with most cities having windspeed below 10 mph. The few cities with windspeeds above 20 mph may be in geographical areas where those speeds are common or are experiencing significant weather events. 

<p align="center">
  <img width="320" height="200" src="https://github.com/ovinueza/Web_Visualization_Dashboard/blob/master/WebImages/CityLatitude_vs_WindSpeed.png">
</p>




