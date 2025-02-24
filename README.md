# Weather App

A simple weather app built with vanilla JavaScript that allows users to check the current weather conditions for any city. The app fetches weather data from the [OpenWeatherMap API](https://openweathermap.org/).

## Features

- Search for weather by city name
- Displays current temperature, humidity, weather description, and more
- Responsive design

## Demo

[Live Demo](https://guilhermesgsilva-weather-app.netlify.app/)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   ```
2. Navigate to the project directory:
   ```sh
   cd weather-app
   ```
3. Open `index.html` in your browser.

## Set up your development environment

1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your free API key.


2. Create a file named `config.js` in the root of the project and add the following code:
   
   ```js
   window.ENV = {
     API_KEY: "your_api_key", // Replace with your OpenWeatherMap API key
     API_URL: "https://api.openweathermap.org",
   };
   ```

## Usage

1. Enter a city name in the search bar and click "Search".
2. View current weather details including temperature, humidity, and weather condition.
3. Refresh the page to search for a new location.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap API
