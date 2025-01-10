# Weather App

A simple weather application that allows users to search for weather information by entering the name of a city. The app fetches real-time data from the OpenWeatherMap API and displays key weather information such as temperature, humidity, wind speed, and weather-related images.

## Features

- Search for weather information by entering the name of a city.
- Displays the current temperature, city name, humidity, and wind speed.
- Shows weather-related images, such as the sun, clouds, or rain, based on the weather conditions.
- Utilizes the `fetch` method to communicate with the OpenWeatherMap API and retrieve data.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **API**: OpenWeatherMap API (https://openweathermap.org/)
- **Methods**: `fetch` for making API requests.

## Setup Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your browser to start using the app.

## How It Works

1. Enter the name of a city in the search bar.
2. Click the search button to retrieve weather data from the OpenWeatherMap API.
3. The app will display:
   - **Temperature**: The current temperature in the city.
   - **City Name**: The name of the city searched.
   - **Humidity**: The current humidity percentage.
   - **Wind Speed**: The wind speed in meters per second.
   - **Weather Image**: An image representing the current weather (e.g., sun, clouds, or rain).

## Example

Search for a city like "New York" and see the weather information displayed on the screen.

## API Key Setup

To use this app, you need an API key from OpenWeatherMap:

1. Go to [OpenWeatherMap](https://openweathermap.org/).
2. Sign up and get your free API key.
3. Replace the API key in the JavaScript file (`app.js` or wherever the fetch request is made).

