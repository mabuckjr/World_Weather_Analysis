# World Weather Analysis
Resources: Python, PANDAS, SciPy, Google API's, Open Weather API
## Overview
In this project, we were tasked with coming up with a program that would generate a roadtrip for a customer. This involved using random latitudes and longitudes and accessing the Open Weather API to get the weather data we needed from the nearest city. We then used the Google Maps API to create interactive maps with pins to the cities that they could go to. Lastly we created a theoretical road trip for them, mine occurring on the west coast of mainland Mexico.
## Analysis
### Weather Datbase
First, we created our weather database. This required us to generate some random coordinates and then use the Open Weather API to find cities near those coordinates. The API was able to give us weather information that would be used later (see table below):
![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_Table.PNG)
### Vacation Search
Once we had our weather and city database, we were able to start the search for our customers based on the temperature they desired. We then used the google api to try to find a hotel in the cities with the preferred weather. The result table looks something like this:
![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search_Table.PNG)

And the map that was generated looked like this:
![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)
### Vacation Itinerary
Lastly, we were able to take the data that we gathered and create a vacation itinerary for our customer. I selected four nearby cities for them to do a roadtrip on, and was able to create this table:
![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary_Table.PNG)

And these two maps for their reference:
![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

![](https://github.com/mabuckjr/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
## Summary
This project was a very different experience than the others so far. Taking real, live data from an API was challenging but rewarding. I really enjoyed seeing how it all changed when I had to redo certain aspects; it's a project that can have a different result every time you run the code. Using these two API's was great, and I'm looking forward to exploring this topic more in the future.
