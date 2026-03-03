# 🌦️ Weather-Web

A simple and responsive web application that provides real-time weather
information for any city using the OpenWeatherMap API.

------------------------------------------------------------------------

## 📌 Overview

Weather-Web is a lightweight frontend project built using HTML, CSS, and
JavaScript.\
It allows users to search for a city and instantly view current weather
conditions including temperature, humidity, wind speed, and weather
status icon.

This project demonstrates API integration, asynchronous JavaScript
(fetch), and dynamic DOM manipulation.

------------------------------------------------------------------------

## 🚀 Features

-   🌍 Search weather by city name
-   🌡️ Displays real-time temperature
-   💧 Shows humidity levels
-   🌬️ Displays wind speed
-   🌥️ Weather condition icon display
-   ❌ Error handling for invalid city names
-   📱 Responsive and clean UI design

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   HTML5 -- Page structure\
-   CSS3 -- Styling and responsive design\
-   JavaScript (ES6) -- API calls and DOM updates\
-   OpenWeatherMap API -- Live weather data source

------------------------------------------------------------------------

## 📂 Project Structure

Weather-Web/ │ ├── index.html \# Main webpage structure\
├── style.css \# Styling for the UI\
├── script.js \# API integration and dynamic updates\
└── README.md \# Project documentation

------------------------------------------------------------------------

## ⚙️ How It Works

1.  User enters a city name in the search bar.
2.  JavaScript sends a request to the OpenWeatherMap API.
3.  API returns weather data in JSON format.
4.  The app dynamically updates the UI with:
    -   Temperature
    -   Humidity
    -   Wind Speed
    -   Weather Icon
5.  If the city is not found, an error message is displayed.

------------------------------------------------------------------------

## 🔑 API Setup

To run this project:

1.  Get a free API key from https://openweathermap.org/
2.  Open `script.js`
3.  Replace the existing API key with your own:

``` javascript
const apiKey = "YOUR_API_KEY";
```

------------------------------------------------------------------------

## ▶️ How to Run

1.  Download or clone the repository.
2.  Open `index.html` in your browser.
3.  Enter a city name and view the weather details.

No backend or server setup required.

------------------------------------------------------------------------

## 🌍 Applications

-   Beginner API integration project
-   Web development practice
-   Portfolio frontend project
-   Learning asynchronous JavaScript

------------------------------------------------------------------------

## 🔐 Limitations

-   Requires internet connection
-   Depends on OpenWeatherMap API availability
-   Shows only current weather (no forecast)

------------------------------------------------------------------------

