# Travel Planner App 

## Overview

A web application called Travel Planner helps users organize and schedule their travels. By indicating their destination and departure date, users can add excursions. The application retrieves location information, including latitude, longitude, and country, through integration with the Geonames API and presents it on the trip card. The program also lets users add or remove excursions from the list and calculates the countdown to the trip departure date.

## Features
  -Travel Planning: To add trips, enter the departure and destination dates.
  -Location Data Retrieval: Use the Geonames API to retrieve country, latitude, and longitude data.
  -Journey Countdown: Determine and show the number of days left in the journey automatically.
  -Trip Management: Organize your trip list by adding or removing trips.
  -A user-friendly interface that adjusts to various screen sizes is known as responsive design.

## APIs

# 1. Geonames API

# Purpose:
  To retrieve location details such as latitude, longitude, and country based on the entered destination.

# Endpoint Used:
  http://api.geonames.org/searchJSON

# Parameters:
  -q: The name of the location (e.g., city, country).
  -maxRows: The maximum number of rows to return
  -username: the API username

# 2.  Weatherbit API

# Purpose:
  Retrieve current weather data for the destination.

# Endpoint Used:
  https://api.weatherbit.io/v2.0/current

# Parameters:
  -lat: Latitude of the location.
  -lon: Longitude of the location.
  -key: Your Weatherbit API key.

# 3. Pixabay API

# Purpose:
  Fetch images related to the destination to display on the trip cards.

# Endpoint Used:
  https://pixabay.com/api/

## Parameters:
  -q: Query string (location name).
  -key: Your Pixabay API key.

## Additional Features
  - Allow the user to remove the trip.
  -Use Local Storage to save the data so that when they close, then revisit the page, their information is still there.

## How to run the code
1. npm run build
2. npm start

## Node version
v20.15.1

## npm version
10.8.2

## Project is running at :
  -Loopback: http://localhost:8080/s
