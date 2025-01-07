# API-INTEGRATION-AND-DATA-VISUALIZATION-1

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: KRISH SHAH

**INTERN ID**: CT6WGXL

**BATCH DURATION**: DECEMBER 30TH, 2024 TO FEBRUARY 15TH, 2025

**MENTOR NAME**: NEELA SANTHOSH

# DESCRIPTION
This Python script fetches weather forecast data for a specified city from the OpenWeatherMap API, processes it, and visualizes the results using Matplotlib and Seaborn.

**Purpose**:
- To demonstrate how to interact with a public API, process JSON responses, and create meaningful visualizations from the data.
- To provide users with an easy way to explore temperature patterns for a city of their choice.

**Key Features**:
1) Fetches 5-day weather forecast data in 3-hour intervals using the OpenWeatherMap API.
2) Processes the retrieved data to extract timestamps, temperatures, and weather descriptions.
3) Generates visualizations:
   - A line plot showing temperature trends over time.
   - A bar plot displaying temperature distributions across timestamps.

**Functions**:
+ **fetch_weather_data(city, api_key, units="metric")**: Makes a GET request to the OpenWeatherMap API and retrieves forecast data for the specified city.
- **process_weather_data(data)**: Extracts and organizes timestamps, temperatures, and weather descriptions from the API response.
* **create_visualizations(dates, temperatures, descriptions)**: Generates temperature visualizations using Matplotlib and Seaborn.

 **Usage**:
+ Replace 'your_openweathermap_api_key' with your valid API key from OpenWeatherMap.
- Customize the 'CITY' variable to specify the city for which you want the weather forecast.
* Run the script to fetch the weather data and display the visualizations.
