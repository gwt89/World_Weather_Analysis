# World_Weather_Analysis
This analysis filtered weather data to create weather preferences which will be used to find hotels and locate potential travel destinations. From the list of potential travel destinations 4 cities will be chosen to create a travel itinerary. Finally, using the Google Maps Directions API a travel route between the 4 cities will be created, as well as a marker layer map.

## Weather Database
A set of 2,000 random latitudes and longitudes was created. Then I performed an API call with the OpenWeatherMap.
I retrieved the following information from the API call:

o	Latitude and longitude

o	Maximum temperature

o	Percent humidity

o	Percent cloudiness

o	Wind speed

o	Weather description (for example, clouds, fog, light rain, clear sky)

Then I added the data to a new DataFrame which was then used for Vacation_Search.
## Vacation Search
I used the Google Maps API to create a marker layer map of locations between a low of 75 and high of 100 degrees Fahrenheit.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/105949411/179136937-d6612718-97c2-4b53-8fb5-c1b6c7cdba7e.png)

## Vacation Itinerary
I used the Google Maps API to create a marker layer map of 4 chosen locations to form a Vacation Itinerary.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/105949411/179137038-10cd8dfb-c804-4d9f-bbd0-1dba9062bb61.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/105949411/179137053-7c1bfc8e-5fb2-42d9-9434-ee0338481279.png)
