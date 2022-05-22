# World_Weather_Analysis

Basic Project Plan:
Here's an outline of the project plan:

Task: Collect and analyze weather data across cities worldwide.

Purpose: Plan MyTrip will use the data to recommend ideal hotels based on clients' weather preferences.

Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

# Project Description: 

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data we have already retrieved in this module. Then, we had the beta testers use input statements to filter the data for their weather preferences, which used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester chose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, we created a travel route between the four cities as well as a marker layer map.

# Three technical analyses
**This new assignment consists of three technical analyses. We submited the following deliverables:

Deliverable 1: Retrieve Weather Data
- Used the NumPy module to generate 2,000 random latitudes and longitudes.
- Used the citipy module to list the nearest city to the latitudes and longitudes.
- Used the OpenWeatherMap API to request the current weather data from each unique city. 
- Parse the JSON data from the API request.
- Collected the following data from the JSON file and add it to a DataFrame:
- City, country, and date
- Latitude and longitude
- Maximum temperature
- Humidity
- Cloudiness
- Wind speed
- Current Description
 
**Deliverable 2: Create a Customer Travel Destinations Map:
- Input statements to retrieve customer weather preferences.
- created a new DataFrame based on minimum and maximum temperature.
- The travel destinations and nearby hotels names.
- A marker layer map with pop-up markers for the cities

**Deliverable 3: Create a Travel Itinerary Map
- four DataFrame are created.
- Latitude and Longitude pair for each of the four cities are retrieved.
- A direction layer map.
- A marker layer map.

![image](https://user-images.githubusercontent.com/92646311/169721295-48fa15a0-c413-4cb6-9b2b-87a08fedb9a1.png)
