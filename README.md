# python-api-challenge
UNC CH BC HW5

About these notebooks:

**WeatherPy** generates latitude and longitude values and a list of corresponding cities.
This list of cities and weather conditions is placed in a .csv in the output_data folder (will be used by VacationPy). 
The weather data for these cities is pulled from the open weather API. 
Several scatter plots and linear regression analysis of weather data and latitude are generated.
The plots are saved as .png in the outpute_data folder.
A brief description/analysis of each plot is included directly below the plot in a markdown cell.

**VacationPy** uses the list of cities from WeatherPy and gmaps to first create heatmaps based on humidity.
Because this notebook needs the output data from WeatherPy, the output_data folder must be in the same directory.
The data is filtered based on the author's ideal weather conditions. 
Then, google places api is used to locate hotels near the cities with the ideal weather conditions.
Finally, markers with hotel info are generated and placed on top of a heatmap with humidity conditions.