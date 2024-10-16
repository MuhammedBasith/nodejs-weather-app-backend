# Weather Data Saver

This Express.js application retrieves weather data from the OpenWeatherMap API for a specified city and saves it to a MongoDB database. 

## Features

- Connects to a MongoDB database to store weather data.
- Fetches real-time weather information using the OpenWeatherMap API.
- API endpoint (`/save-weather`) accepts a city name as a query parameter to fetch and save weather data.

## Setup

1. Clone the repository.
2. Install dependencies: `npm install`.
3. Create a `.env` file with your OpenWeatherMap API key:  
   `WEATHER_API=your_api_key`
4. Start MongoDB and run the server: `node app.js`.
5. Access the API at `http://localhost:3000/save-weather?city=CityName`.

## Technologies

- Express.js
- Axios
- Mongoose
- MongoDB
