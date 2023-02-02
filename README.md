# World_Weather_Analysis

## Project overview
For this project, we helped PLANMYTRIP, a top travel technology company specializing in internet-related services in the hotel and lodging industry. We assisted the head of analysis, Jack, in collecting and presenting data for customers via the search page, which they can filter based on their preferred travel criteria to find their ideal hotel anywhere in the world.

We made improvements to the app and had beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. The beta tester chose four cities from the list of possible travel destinations to create a travel itinerary. We then used Geoapify Routing API, to create a travel route between the four towns and a marker layer map.

## Summary

### Weather Database

We generated a set of a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap. The informartion that we gathered through the API call was:
-Latitude and longitude

-Maximum temperature

-Percent humidity

-Percent cloudiness

-Wind speed

-Weather description

### Vacation Search

We employed input statements to retrieve customer weather preferences. We then used those preferences to identify potential travel destinations and nearby hotels, and showed the below map of possible destinations.


![WeatherPy_vacation_map](https://user-images.githubusercontent.com/117063056/216284708-df125cd0-d6ca-4eac-a700-1910719a65ee.png)


### Vacation Itenerary

We used the Geoapify Routing API to create a travel itenerary that shows the route between the four cities chosen from the curstomer's possoble travel destinations. We highlighted each of the four cities with a marker, and presented the customer with the map below. 

