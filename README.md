# Weather Dashboard 🌦️

A responsive weather dashboard built using **HTML, CSS, and JavaScript**. It displays current weather information, location-based forecasts, weather details, recent searches, and a 7-day forecast.

## Live Demo

🔗 **Live Demo:** `PASTE_YOUR_LIVE_DEMO_LINK_HERE`

## Snapshot

📸 **Project Screenshot:**

`PASTE_YOUR_SCREENSHOT_HERE`

---

## Overview

This project is a weather dashboard that allows users to search for locations and view their current weather conditions and upcoming forecast.

Weather data is fetched using the **Open-Meteo API**, with location search handled through Open-Meteo's geocoding service.

---

## Features

* Current location and date
* Current temperature
* Highest and lowest temperature
* Current weather condition
* Smart location search
* Location search suggestions
* Search for cities and locations
* Recently searched locations
* View all recent searches
* 7-day weather forecast
* Daily high and low temperatures
* Temperature forecast graph
* Humidity
* Chance of rain
* Wind speed
* Wind direction
* Air pressure
* Feels-like temperature
* UV Index
* Sunrise
* Sunset
* Precipitation
* Weather condition icons
* Dynamic weather background
* Different backgrounds based on time of day and weather condition
* Responsive layout

---

## Data Flow

```text
Search Location
      ↓
Open-Meteo Geocoding API
      ↓
Latitude + Longitude
      ↓
Open-Meteo Weather API
      ↓
Weather & Forecast Data
      ↓
JavaScript
      ↓
Dashboard UI
```

---

## Technologies

* HTML5
* CSS3
* JavaScript
* Fetch API
* Async / Await
* REST API
* SVG
* CSS Media Queries

---

## APIs

### Open-Meteo

Used to retrieve:

* Current weather
* Temperature
* Humidity
* Apparent temperature
* Wind speed
* Wind direction
* Air pressure
* Precipitation
* UV Index
* Sunrise and sunset
* Rain probability
* 7-day forecast

### Open-Meteo Geocoding

Used for searching locations and getting their:

* Latitude
* Longitude
* Location name
* Country
* Administrative region

---

## Design

* Dark weather dashboard
* Minimal interface
* Responsive layout
* Weather-based backgrounds
* Weather information cards
* SVG-based weather icons
* Clean temperature and forecast presentation

---

## Page Sections

### Header

* Current location
* Current date
* Smart search

### Current Weather

* Current temperature
* High temperature
* Low temperature
* Weather condition

### Recently Searched

* Recently searched locations
* See All option
* Search history modal

### Forecast

* 7-day forecast
* Daily temperatures
* Weather conditions
* Temperature graph

### Weather Details

* Feels Like
* Humidity
* Wind Speed
* Wind Direction
* Air Pressure
* UV Index
* Sunrise
* Sunset
* Precipitation
* Chance of Rain

---

## Responsive Design

The dashboard is designed to work across:

* Desktop
* Tablet
* Mobile devices

The layout adjusts according to the available screen size.

---

## Usage

1. Open the project in a browser.
2. Use the smart search to search for a location.
3. Select a location from the suggestions.
4. View the current weather information.
5. Check the weather details and 7-day forecast.
6. Use the recently searched section to access previously searched locations.

---

## Project Structure

```text
Weather Dashboard/
│
├── index.html
├── morningsunny.jpg
├── morningcloudy.jpg
├── morningrainy.jpg
├── afternoonsunny.jpg
├── afternooncloudy.jpg
├── afternoonrainy.jpg
├── eveningsunny.jpg
├── eveningcloudy.jpg
├── eveningrainy.jpg
├── nightsunny.jpg
├── nightcloudy.jpg
└── nightrainy.jpg
```

---

## Project

**Weather Dashboard**

Built using native **HTML, CSS, and JavaScript**.
