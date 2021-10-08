# World-Weather-Analysis
## Project Overview
The purpose of this project is to create PlanMyTrip app using Python language for travel company that will use input prefer weather to filter potential travel destinations worldwide using OpenWeatherMap API and Google Maps Platform APIs and Google Maps Platform APIs. After selecting four cities to create a travel itinerary then  create travel routes .

## Software and APIs
Software: Python 3.7, Anaconda, Jupyter Notebook.

Google Maps Platform: Directions API, Places API.

OpenWeatherMap: Current Weather Data.

For this project, it is also necessary to create a config.py file with your specific API key information.
please see the example below.

- weather_api_key="your-weather-api-key-here"
- g_key="your-google-maps-api-key-here"


## Retrieve Weather Data
To start this project, it was necessary to generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition.Generate data will  create a new DataFrame containing the updated weather data


![This is an image](https://github.com/NadaAdem/World-Weather-Analysis/blob/main/Weather_Database/WeatherPy_Database.png)



## Create a Customer Travel Destinations Map
 The user input  the minimum and maximum temperatur to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels.Then, show those destinations on a marker layer map with pop-up markers.
 
![This is an image](https://github.com/NadaAdem/World-Weather-Analysis/blob/main/Vacation_Search/hotel_name.png)

![This is an image](https://github.com/NadaAdem/World-Weather-Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)


## Create a Travel Itinerary Map

The final section of this project is to create a travel itinerary map .Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

![This is an image](https://github.com/NadaAdem/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

![This is an image](https://github.com/NadaAdem/World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_hotel.png)

