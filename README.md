# World_Weather_Analysis

## Obtain Weather Data
After generating 2,000 random latitudes and longitudes, I retrieved the nearest city and performed an API call with OpenWeatherMap to gather the following information:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description

![City_data_df](https://user-images.githubusercontent.com/60076980/152699849-266cd40e-6a32-49a6-af5c-8796c50bc8ec.png)


![WeatherPy_vacation_map](https://user-images.githubusercontent.com/60076980/152699483-105d1526-a3c3-4a31-b8da-2e9b0ac46580.png)

## Create a customer Travel Destinations Map
I then used customer preference inputs (minimum temperature 70 degrees, maximum temperature 95 degrees) to identify potential travel destinations.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/60076980/152699491-9e9c389a-41f9-420e-894a-1615d1cfe630.png)

## Create a Travel Itinerary Map
After identifying four cities in Indonesia that met the temperature requirements, I created a travel itinerary map using Google Directions API.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/60076980/152699495-31f0fda2-537b-47a0-94e1-063135ba55bc.png)
