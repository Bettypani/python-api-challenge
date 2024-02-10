# python-api-challenge

WeatherPy
Overview:
WeatherPy is a Python script designed to visualize the weather of over 500 cities located at varying distances from the equator. It utilizes the citipy Python library, the OpenWeatherMap API, and various Python coding techniques to create representative models of weather across cities.

Requirements:

Python 3.x
Jupyter Notebook
Dependencies: citipy, requests, matplotlib, scipy
Instructions:

Open the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file.
Run the notebook cells sequentially to generate random geographic coordinates and retrieve weather data from the OpenWeatherMap API.
The notebook will guide you through the process of creating scatter plots to showcase the relationships between weather variables and latitude.
Requirements Fulfillment:

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Requirement 2: Compute Linear Regression for Each Relationship

Compute linear regression for each relationship, separating the plots into Northern Hemisphere (≥ 0° latitude) and Southern Hemisphere (< 0° latitude).
Include the linear regression line, the model's formula, and the r values in the scatter plots.
Credits:
WeatherPy was created as part of a project assignment. It utilizes the citipy library for city lookup based on geographic coordinates and the OpenWeatherMap API for weather data retrieval.


VacationPy

Overview:
VacationPy is a Python script designed to assist in planning future vacations by utilizing weather data and creating map visualizations. It employs Jupyter notebooks, the geoViews Python library, and the Geoapify API to visualize city data and find suitable vacation destinations based on specified weather conditions.

Requirements:

Python 3.x
Jupyter Notebook
Dependencies: pandas, geoViews, Geoapify
Instructions:

Open the VacationPy.ipynb Jupyter notebook provided in the starter code.
Run the notebook cells sequentially to import required libraries, load the CSV file containing weather and coordinates data, and execute the code to create map visualizations.
Follow the instructions within the notebook to generate the required map displaying points for every city with the size of the point representing the humidity in each city.
Narrow down the DataFrame to find ideal weather conditions based on specified criteria such as maximum temperature, wind speed, and cloudiness.
Create a new DataFrame called hotel_df to store city, country, coordinates, and humidity.
Utilize the Geoapify API to find the first hotel located within 10,000 meters of each city's coordinates.
Add the hotel name and country as additional information in the hover message for each city on the map.
Requirements Fulfillment:

Create a map displaying a point for every city in the DataFrame with the size of the point representing humidity.
Narrow down the DataFrame to find ideal weather conditions based on specified criteria.
Create a new DataFrame to store city, country, coordinates, and humidity.
Utilize the Geoapify API to find the first hotel located within 10,000 meters of each city's coordinates.
Add hotel name and country information in the hover message for each city on the map.

Credits:
VacationPy was created as part of a project assignment. It utilizes the geoViews library for map visualizations and the Geoapify API for retrieving hotel information.
