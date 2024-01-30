# python-api-challenge
## Description
This repository finds a random set of latitude and longitudes, finds the cities closest to those coordinates, analyzes weather data from the cities found, and plots the cities on a geographic map. The parameters for ideal weather conditions can be changed and the location of a hotel within 10,000m of the location, if found, will be returned. The WeatherPy folder is used to find and analyze the weather for the cities that were located. The VacationPy folder is used to plot the cities on the geographic map and find the location of a hotel based on the requested weather conditions.
## Requirements
The pandas, hvplot.pandas, matplotlib.pyplot, numpy, scipy.stats, and requests modules are required for this project. API keys for the OpenWeatherMap API and Geoapify API are also required.
## Installation
Clone the repository: git@github.com:KeeganDavis/python-api-challenge.git
## Usage
Select a python kernel and run all code blocks to generate the weather data and analyze the data in the WeatherPy folder. Select a python kernel and run all code blocks to generate the geographic map with the cities and locate the hotels for the specified locations in VacationPy.
## Code Sources
-Change color based on size of data (https://stackoverflow.com/questions/59076441/different-color-in-hvplot-box)  \
-Color maps for hvplot (https://holoviews.org/user_guide/Colormaps.html) \
