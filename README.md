# Vacation Travel Itinerary based on Weather Analysis

## Background

>Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data project that has already be developed. Then, the beta testers will use the input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, a travel route between the four cities will be created along with a marker layer map.

### Retrieve Weather Data
>Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap.  From the API call the following fields will be pulled – Latitude and Longitude, Maximum Temperature, Percent Humidity, Percent Cloudiness, Wind Speed and the new field for the current Weather Description. This information will then compiled into a new DataFrame for the weather data.

### Create a Customer Travel Destinations Map

>Input statements will be created to retrieve the customers minimum and maximum temperature preferences and then used to identify potential travel destinations and nearby hotels. Those potential destinations will then be displayed on a marker layer map with pop-up markers as seen the below image.
![](https://github.com/timbialek/World_Weather_Analysis_2022/blob/main/Vacation_Search/WeatherPy_vacation.map.png)

### Create a Travel Itinerary Map

>Using the Google Directions API, a travel itinerary will be created that shows the route between four cities chosen from the customer’s possible travel destinations. Then, a marker layer map will be created with a pop-up marker for each city on the itinerary. Below are the images of where the customer selected Australia as there destination.

## Australia, Queensland Travel Maps

Travel Route Between the 4 Cities:
![](https://github.com/timbialek/World_Weather_Analysis_2022/blob/main/Vacation_Itinerary/Weather_travel_map.PNG)


Marker Layer map with City Information:
![](https://github.com/timbialek/World_Weather_Analysis_2022/blob/main/Vacation_Itinerary/Weather_travel_map_markers.PNG)
