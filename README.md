# python-api-challenge

Justin Boggs
01/25/20

This challenge contains two challenges, WeatherPy and VacationPy.

WeatherPy creates random geocoordinate data and pulls the current weather conditions useing citipy. This data is then analyzed based on latitude, humidity levels, temperature, cloudiness, and wind speed. Scatterplots are created to investigate the relationships between these data points and the plots are saved in the output_data folder in the WeatherPy folder. A .csv file containing a list of the cities and corresponding weather data is also saved to this folder.

VacationPy uses the city list created in WeatherPy to pick an ideal vacation spot. The list is sorted based on specific temperature, wind speed, and cloudiness values determined by myself. Using this new narrowed city list and gmaps, the nearest hotel is found for each city. A .csv file containing the data is created in the output_data folder under the VacationPy folder. A Google heatmap based on humidity is then created and markers are placed at each hotel location with the hotel name, city, and country.