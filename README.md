# World_Weather_Analysis

## Deliverable 1

For this project, we generated 2,000 random latitudes and longitudes. Then, using citipy, we retrieved the nearest city to those coordinates. After this, we performed an API call with the OpenWeatherMap. With this, we retrieved the latitude, longitude, maximum temperature, percent humidity, percent cloudiness, wind speed, and the current weather description for each city. In total, we ended with 675 cities with all of this information. We exported this data to a new DataFrame and exported this as a CSV file.

## Deliverable 2

Using this new CSV file, we added two input statements for users to enter their preferred maximum and minimum temperatures. This was to help identify potential travel destinations and nearby hotels. We performed an API call with Google Directions to search for hotels within 5,000 meters of each city. Once we found a hotel for each city, we exported this data to a CSV file. We successfully found hotel information for 202 of our cities. In addition, we used the gmaps function to create a map with Google Maps to show the location of each hotel as well as the hotel name, city, country, current weather description, and maximum temperature.

## Deliverable 3

Using the newest CSV file which included hotel names, we mapped the hotels again and chose four cities in Australia where we want to create a vacation itinerary. For this project, we chose Yulara, Alice Springs, Mount Isa, and Katherine, Australia. Using the Google Directions API, we added our new DataFrames for each city in a direction layer to map the driving route between these four cities. Then, we added all of these DataFrames together using the concat() function. Finally, we added markers for each hotel in each city and mapped them using the gmaps function.
