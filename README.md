# Python-API-challenge
by: Dave Wisinski

March 2021

## Project: Python API Homework - WeatherPy and VacationPy

## Description:
This project was created to demonstrate a number of data analysis concepts using a data set generated from calls to various third party APIs including the Open Weather Map API (https://openweathermap.org/api) and the Google Maps and Places APIs (https://developers.google.com/apis-explorer). Data was parsed from these APIs, stored in .csv format and pandas DataFrames, and anylzed using pandas and matplotlib libraries for Python, as well as various built-in functionality from the Google APIs.

## **Important Usage Notes:**
For WeatherPy, observations and analysis based on the data are included at the top of the notebook.

Excel .csv file and image .svg files are exported to the "output_data" folder from the WeatherPy notbook script. Re-running all cells will overwrite the existing output_data files. Specifically for WeatherPy, the scatter plot annotations can be placed according to the plt.annotate "xy" argument (refer to documentation at https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.annotate.html). Scatter plots will change based on the city list and weather on the date the script was last run (last run before push was 3/23/21).