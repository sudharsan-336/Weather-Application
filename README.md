# 🌦️Weather Application
## Overview
The **Weather Application** is a modern React-based web application that allows users to search for any city and view real-time weather information. It fetches live weather data from the OpenWeatherMap API and displays the current temperature, humidity, wind speed, and weather condition with dynamic icons.

## Features
### City Search
- Search weather by entering any city name.
- Supports search using the Enter key or the search button.

### Live Weather Information
Displays:
- Current Temperature (°C)
- City Name
- Humidity
- Wind Speed
- Dynamic Weather Icon

### API Integration
- Retrieves real-time weather data from the OpenWeatherMap API.
- Displays appropriate weather icons based on weather conditions.

### Error Handling
- Shows an error message if the entered city is invalid.
- Handles API errors gracefully.

### Loading Indicator
- Displays a loading message while fetching weather data.

### Responsive UI
- Modern card design
- Gradient background
- Responsive layout
- Clean and user-friendly interface

## Technologies Used
- React.js
- Vite
- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

## API Used
- OpenWeatherMap Current Weather API →  https://openweathermap.org/current

## Project Structure
```
Weather-Application/
│
├── public/                    # Static assets
├── src/
│   ├── assets/                # Weather icons and images
│   ├── components/
│   │   ├── Weather.jsx        # Main Weather component
│   │   └── Weather.css        # Weather component styling
│   ├── App.jsx                # Root component
│   ├── App.css                # Global styles
│   └── main.jsx               # Application entry point
│
├── .env                       # OpenWeatherMap API key
├── .gitignore                 # Git ignored files
├── package.json               # Project dependencies
├── package-lock.json          # Dependency lock file
├── vite.config.js             # Vite configuration
├── index.html                 # Main HTML file
└── README.md                  # Project documentation
```

## Software Requirements
- Node.js (v18 or later)
- npm
- Visual Studio Code (Recommended)
- Modern Web Browser (Chrome, Edge, Firefox)


## Environment Variables
Create a **.env** file in the root directory.
```
VITE_APP_ID=YOUR_OPENWEATHERMAP_API_KEY
```
Replace `YOUR_OPENWEATHERMAP_API_KEY` with your own API key from OpenWeatherMap.


## Installation
Clone the repository
```bash
https://github.com/sudharsan-336/Weather-Application.git
```
Install dependencies
```bash
npm install
```
Start the server
```bash
npm run dev
```
Open your browser and visit
```
http://localhost:5173
```

## How It Works
1. User enters a city name.
2. Clicks the Search icon or presses Enter.
3. The application sends a request to the OpenWeatherMap API.
4. The API returns current weather details.
5. The application displays:
   - Weather Icon
   - Temperature
   - City Name
   - Humidity
   - Wind Speed
6. If the city is invalid, an error message is displayed.