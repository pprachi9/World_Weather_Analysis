# World_Weather_Analysis

## Overview of the Analysis

This analysis looks at different weather patterns around the global. in this analysis we have to add the weather description to the weather data we have already retrieved in this module. Then, we will have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, we created a travel route between the four cities as well as a marker layer map.

## What we are Creating
1: Retrieve Weather Data

2: Create a Customer Travel Destinations Map

3: Create a Travel Itinerary Map

### Deliverable 1: Retrieve Weather Data

- Create a new set of 2,000 random latitudes and longitudes.
- Get the nearest city using the citipy module.
- Perform an API call with the OpenWeatherMap.
- Retrieve the following information from the API call:
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description (for example, clouds, fog, light rain, clear sky)

### Deliverable 2: Create a Customer Travel Destinations Map

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

### Deliverable 3: Create a Travel Itinerary Map

Using the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create      a marker layer map with a pop-up marker for each city on the itinerary.

## Resources and Before Start Notes
- Data File: file.csv
- Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas
