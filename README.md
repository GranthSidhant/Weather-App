# Weather App

A simple weather application that fetches real-time weather data based on the user's input location. It displays temperature, weather conditions, humidity, and wind speed.

## Features
- Fetches real-time weather data using OpenWeatherMap API
- Displays temperature, humidity, wind speed, and weather description
- Responsive design for a better user experience

## Technologies Used
- HTML
- CSS
- JavaScript
- OpenWeatherMap API

## Setup your own API Key
This project uses OpenWeatherMap API. Currently I have added my API key. If you want to use your own API key,
Replace `APIKey` in `script.js` with your own API key:
```js
const APIKey = 'YOUR_API_KEY_HERE';
```
You can get an API key from [OpenWeatherMap](https://openweathermap.org/api).

## Usage
1. Enter a city name in the input box.
2. Click the search button or press Enter.
3. View the current weather details.