# Python-API-Challenge

# Part 1: WeatherPy

## AIM: To create a Python script to visualise the weather of over 500 cities of varying distances from the equator.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude.
### Objectives:
### - To fulfill the first requirement use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. 
### - Create a series of scatter plots to showcase the following relationships:
#### - Latitude vs. Temperature
#### - Latitude vs. Humidity
#### - Latitude vs. Cloudiness
#### - Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression for Each Relationship.
### Objectives: 
### - To compute the linear regression for each relationship. 
### - Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
### - Create a series of scatter plots including the following plots:
#### - Northern Hemisphere: Temperature (C) vs. Latitude
#### - Southern Hemisphere: Temperature (C) vs. Latitude
#### - Northern Hemisphere: Humidity (%) vs. Latitude
#### - Southern Hemisphere: Humidity (%) vs. Latitude
#### - Northern Hemisphere: Cloudiness (%) vs. Latitude
#### - Southern Hemisphere: Cloudiness (%) vs. Latitude
#### - Northern Hemisphere: Wind Speed (m/s) vs. Latitude
#### - Southern Hemisphere: Wind Speed (m/s) vs. Latitude

# Part 2: VacationPy

## AIM: To use your weather data skills to plan future vacations. Also, to use Jupyter Notebooks, the geoViews Python library, and the Geoapify API.

### Requirement 1: The main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualisations.
### Objectives: 
### - Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each town.
### - Narrow down the city_data_df DataFrame to find your ideal weather condition. 
#### - For example:
####        A max temperature lower than 27 degrees but higher than 21
####        Wind speed less than 4.5 m/s
####        Zero cloudiness
### - Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
### - For each city, use the Geoapify API to find the first hotel located within 10,000 metres of your coordinates.
### - Add the hotel name and the country as additional information in the hover message for each city on the map.
