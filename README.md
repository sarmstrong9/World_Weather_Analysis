# World_Weather_Analysis - API Project

## Deliverables 
- Deliverable 1
	- Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. 
	- Use API skills to retrieve the current weather description for each city. 
		- Latitude and longitude
		- Maximum temperature
		- Percent humidity
		- Percent cloudiness
		- Wind speed
		- Weather description (for example, clouds, fog, light rain, clear sky)
	- Create a new DataFrame containing the updated weather data and export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder
	- Outputs are:
		- The Weather_Database.ipynb file
		- The WeatherPy_Database.csv file
		
- Deliverable 2
	- Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels.  Then, show those destinations on a marker layer map with pop-up markers.
	- Deliverables are:
		- Input statements written to prompt the customer for their minimum and maximum temperature preferences.
		- A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped.
		- The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped.
		- The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv.
		- A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information:
			- Hotel name
			- City
			- Country
			- Current weather description with the maximum temperature
	- The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png
	- Outputs are:
		- The Vacation_Search.ipynb file
		- The WeatherPy_vacation.csv file
		- The WeatherPy_vacation_map.png image
		
- Deliverable 3
	- Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.
	- Deliverables are:
		- Four DataFrames are created, one for each city on the itinerary. (10 pt)
		- The latitude and longitude pairs for each of the four cities are retrieved. (5 pt)
		- A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. (10 pt)
		- A DataFrame that contains the four cities on the itinerary is created. (10 pt)
		- A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the following information: (5 pt)
			- Hotel name
			- City
			- Country
			- Current weather description with the maximum temperature
	- Outputs are:
		- The Vacation_Itinerary.ipynb file
		- The WeatherPy_travel_map.png image
		- The WeatherPy_travel_map_markers.png
	
	