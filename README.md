# Weather Forecast Application Development

## Overview
The Weather Forecast Application is a web-based application that provides users with real-time weather updates and forecasts for their selected cities. It utilizes the OpenWeather API to fetch weather data and presents it in a user-friendly interface.

## Project Structure
```
Weather-Forecast-Application-Development
├── src
│   ├── index.html        # HTML structure of the application
│   ├── app.js           # JavaScript code for API integration and UI management
│   └── styles.css       # Custom CSS styles for the application
├── package.json          # npm configuration file
└── README.md             # Documentation for the project
```

## Setup Instructions
1. **Clone the repository**:
   ```
   git clone <repository-url>
   cd Weather-Forecast-Application-Development
   ```

2. **Install dependencies**:
   Ensure you have Node.js installed, then run:
   ```
   npm install
   ```

3. **Run the application**:
   Open `src/index.html` in your web browser to view the application.

## Features
- Search for weather updates by city name.
- Use current location to fetch weather data.
- Display current weather conditions and a 5-day forecast.
- Responsive design using Tailwind CSS for a modern look.
- Error handling for invalid city names or API issues.
- Store and retrieve recently searched cities using local or session storage.

## Usage Guidelines
- Enter a city name in the search bar and click the search button to get the current weather.
- Click the "Use Current Location" button to fetch weather data based on your geographical location.
- The application will display the current temperature, weather conditions, and a 5-day forecast.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.