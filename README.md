# Analyzing Weather Data for Travel Itineraries 

## Overview 

I collaborted with a travel company to investigate how to provide more in-depth information on ideal travel destinations based on the user's weather preferences. 

Through the use of the OpenWeatherMap API, we were able to get current weather data for a variety of cities across the world, providing real-time suggestions for each client's travel itinerary and convenient hotel options. 

## Results 

![vacationmap](https://github.com/msprech/World_Weather_Analysis/blob/078ae8af2bda4a19465a41ca86af31d1a76bcfb0/Vacation_Search/WeatherPy_vacation_map.png)

This customized map was created using input statements to personalize the client's preferred weather characteristics and resulting destinations that fit these parameters. 

![travelmap](https://github.com/msprech/World_Weather_Analysis/blob/078ae8af2bda4a19465a41ca86af31d1a76bcfb0/Vacation_Itinerary/WeatherPy_travel_map.png)

This potential travel itinerary shows a route comprised of four different cities that met the weather standards of the potential client. 

### Summary 

Through the use of API calls, loops, try-except blocks, and json data, we were able to generate a random list of latitude and longitude tuples, which were then used to find nearby cities. Through the use of input statements, we then created new, clean dataframes with a more narrow list of cities that met the weather needs of the client. 

We then visualized this data through figures, marker layers, and information boxes to more clearly show all of the available data. 
