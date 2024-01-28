# Lab 2 - Accessing Web Resources with Python
## Overview
This Jupyter notebook (visitseattle.ipynb) is designed to scrape event data from a website, obtain geolocation information for each event, and fetch the corresponding weather forecast. It outputs a CSV file (event_weather.csv) containing the event name, address, longitude, latitude, and weather forecast.

## Requirements
1. Python 3.x
2. Jupyter Notebook
3. Libraries: requests, beautifulsoup4, csv
    To install the required libraries, you can use the following command:
    ** pip install notebook requests beautifulsoup4 **

## Running the Notebook
1. Ensure you have Jupyter Notebook installed. If not, you can install it using pip:
    ** pip install notebook **
2. Clone this repository or download the visitseattle.ipynb notebook.

## Navigate to the directory containing the notebook and start the Jupyter Notebook server:
1. Open the visitseattle.ipynb notebook in the Jupyter interface that opens in your browser.
2. Run the cells in the notebook sequentially to perform the scraping, geocoding, and weather data fetching.

## Notebook Structure
The notebook is divided into several sections, each performing specific tasks:

1. Event Data Scraping: Extracts event details like name, date, location, type, and region.
2. Geocoding Event Locations: Utilizes the Nominatim API to convert event locations to latitude and longitude.
3. Fetching Weather Forecasts: Retrieves weather forecasts for the event locations using the National Weather Service API.
4. CSV File Generation: Compiles the data into a event_weather.csv file.

## Output
The notebook will generate a CSV file named event_weather.csv with columns for event name, date, location, type, region, longitude, latitude, and weather forecast.

## Disclaimer
This notebook is for educational purposes only. Ensure compliance with the terms of service for the website being scraped and the APIs used.