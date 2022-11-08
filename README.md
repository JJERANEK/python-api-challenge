# python-api-challenge

## WeatherPy Description - See WeatherPy.ipynb for full analysis

In this assignment, students were asked to create a Python script for two variables. For the first variable, the script would be made to visualize weather of over 500 cities of varying distances from the equator. To fulfill the first requirement, using Jupyter Notebook and the OpenWeatherMap API, a series of scatter plots must be created to showcase the following relationships:
- Lattitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

To fulfill the second requirement, the linear regression would need to be computed for each relationship. The data would be separated into Northern Hemisphere and Southern Hemisphere, and then scatter plots would be used to show the linear regression for analysis. The following plots would be created:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

## VacationPy Description - See VacationPy.ipynb for attempt

For the second variable of this assignment, the original instructions stated to use Jupyter Notebook along with geoViews and the Geoapify API to complete data analysis. However, geoViews and hvplot (which the original instructions included) no longer functioned with Jupyter Notebook by the time this assignment was assigned. Therefore, the instruction team decided that Plotly could be used instead.

In this assignment, a map visualization was to be created to show the humidity of cities from the WeatherPy section. Then, after using Pandas to create a new DataFrame for the student's ideal weather condition, a second map would be created showing hotel data for the areas selected. In order to find the hotel information, an API call to Geoapify was required. Many students, including myself, had various issues with the API Key generated from Geoapify. In the end, I was unable to complete this portion of this assignment due to an unforeseen API Key error.