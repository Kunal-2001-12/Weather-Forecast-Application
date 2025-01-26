# Weather Forecast Application Development

## Overview
The Weather Forecast Application is a web-based application that provides users with real-time weather updates and forecasts for their selected cities. It utilizes the OpenWeather API to fetch weather data and presents it in a user-friendly interface.

## Project Structure
```
Weather-Forecast-Application-Development
├── src
│   ├── index.html        # HTML structure of the application
│   ├── app.js            # JavaScript code for API integration and UI management
│   └── styles.css        # Custom CSS styles for the application
├── package.json          # npm configuration file
└── README.md             # Documentation for the project
```

## Setup Instructions
1. **Clone the repository**:
   ```
   git clone < https://github.com/Kunal-2001-12/Weather-Forecast-Application.git >
   cd Weather-Forecast-Application-Development
   ```

2. **Install dependencies**:
   Ensure you have Node.js installed, then run:
   ```
   npm install
   ```

3. **Open the application**:
   Open the `src/index.html` file in your web browser to view the application.

## Usage
- **Search by City Name**: Enter the name of a city in the search bar and click the search button to get the current weather and 5-day forecast for that city.

- **Use Current Location**: Click the "Use Current Location" button to get the current weather and 5-day forecast for your current location.

- **Recently Searched Cities**: Select a city from the dropdown menu to quickly view the weather and forecast for previously searched cities.

## Features
- Real-time weather updates using the OpenWeather API.
- Search for weather forecasts by city name.
- Get weather forecasts for the current location.
- View a 5-day weather forecast with temperature, wind speed, and humidity.
- Dropdown menu for recently searched cities.
- Error handling and validation for user inputs.

## API Integration
The application uses the OpenWeather API to fetch weather data. You need to replace the placeholder API key in `app.js` with your own OpenWeather API key.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
