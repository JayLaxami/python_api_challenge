# python_api_challenge_


** Clone the repository.
** Generate an API key and Geoapify Key. Add the key to .gitignore file.
** Push back to your repo.

1. Part 1- WeatherPy

In this, we are looking for weather data across cities. The python script utilizes python lib, citiPy and makes API calls to OpenWeatherMap to retrieve data. we made scatter plot and correlation-regression of Latitude with Max Temp, Humidity, Cloudiness and Wind Speed. Also had Northern and Southern Hemisphere dataframes based on latitude. 

Save a CSV of all retreived data and PNG image for each scatter plot in output folder.

Analysis of relationship studied- 

The relation between Latitude and Max Temp - In Northern Hemisphere, the value clearly shows that there is very strong relationship between Latitude and Max Temp. But in Southern Hemisphere, there is a less strong (weak) relationship between Latitude and Max Temp.

In Latitude and Humidity relationship- In Northern Hemisphere, there is very weak relationship between Humidity and Latitude but in Southern Hemisphere, there is negligible (~no) to very weak relationship between Latitude and Humidity.

In Latitude and Cloudiness relationship- In Northern Hemisphere, there is very weak (negligible) relationship between Latitude and Cloudiness but in Southern Hemisphere, there is very weak relationship between Latitude and Cloudiness.

In Latitude and Wind Speed relationship- In Northern Hemisphere, there is negligible to no relationship between Latitude and Wind Speed but in Southern Hemisphere, there is negligible (~no) relationship between Latitude and Wind Speed.

2. Part 2- VacationPy

In this, we will use weather data from Part 1 and plan vacation by finding Hotel name and will have geoapify key. We will also make map with latitude. longitude and using Humidity as size pont. We will make another map and add Hovers column of Hotel name and Country. 
