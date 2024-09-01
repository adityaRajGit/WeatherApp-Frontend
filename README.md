# WeatherApp-Catching-Frontend

## Project Overview
WeatherApp-Catching-Frontend is a responsive web application that provides current weather information and a 5-day weather forecast for any city. It allows users to search for a city's weather, view recent search history, and toggle between Celsius and Fahrenheit temperature units. The app fetches weather data from the SheCodes Weather API and displays it in an easy-to-read format.

## Instructions to Set Up and Run the Project Locally

### Prerequisites
Before setting up the project, ensure you have the following installed:
- Node.js (v14 or higher)
- npm (v6 or higher)

### Setup Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/adityaRajGit/WeatherApp-Catching-Frontend.git
   cd WeatherApp-Catching-Frontend

2. **Install**:
    ```bash
    npm install


3. **Run the Application**:
    ```bash
    npm start

### API Usage Details
**This project uses the SheCodes Weather API to fetch weather data.**

### Endpoints Used:

```
Current Weather:

URL: https://api.shecodes.io/weather/v1/current
Query Parameters:
query: Name of the city.
key: Your API key.
5-Day Forecast:

URL: https://api.shecodes.io/weather/v1/forecast
Query Parameters:
query: Name of the city.
key: Your API key.
units: Units of measurement (metric for Celsius).
```

## Approach
**The WeatherApp-Catching-Frontend is designed with simplicity and user experience in mind. The main components of the app include:**
```
* SearchEngine: Handles user input for searching city weather.

* Forecast: Displays the current weather and 5-day forecast.

* Axios: Used for making API requests to fetch weather data.

* Responsive Design: The app is designed to be fully responsive, providing a seamless experience across different screen sizes.
```