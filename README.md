# WeatherNest 🌦️

WeatherNest is a simple, user-friendly weather application that allows users to get real-time weather updates for any city worldwide. It utilizes the OpenWeather API to fetch and display weather details such as temperature, weather description, and the city’s country.

## Live Demo
Experience WeatherNest live at: [WeatherNest Live](https://weather-nest-omega.vercel.app/)

## Features
- Search for weather updates by city name.
- Displays the current temperature in Celsius.
- Shows the weather description (e.g., cloudy, sunny).
- Provides the name of the country for the searched city.
- Simple and responsive UI, optimized for both desktop and mobile devices.

## How It Works
1. Enter the name of the city in the input field.
2. Click the "Get Weather" button.
3. Weather details (temperature, description, and country) are displayed below.

## Installation and Setup
To run WeatherNest locally:
1. Clone the repository.
2. Open the HTML file (`index.html`) in a browser.
3. Ensure internet connectivity to fetch data from the OpenWeather API.

## Code Overview
### HTML Structure
- **Input Field:** Allows users to enter a city name.
- **Button:** Triggers the weather-fetching process.
- **Weather Display Area:** Dynamically updates to show city name, temperature, country, and description.

### CSS Styling
- Clean and responsive design, with media queries for mobile optimization.
- Background image provides a weather-related theme.

### JavaScript Functionality
- Fetches weather data from OpenWeather API using a city name.
- Handles API responses and displays appropriate messages for errors or invalid inputs.
- Converts temperature from Kelvin to Celsius for user-friendly display.

## API Information
This application uses the [OpenWeather API](https://openweathermap.org/api).  
API Key used in this project: `6294cb8c59ad21dc6bdf5432e18b4a18` (replace this key in production for security purposes).

## Project Structure
- **HTML**: Contains the structure and main layout.
- **CSS**: Inline styling for responsiveness and aesthetics.
- **JavaScript**: Handles API calls and dynamic updates to the UI.

## Future Enhancements
- Add a feature to display a 5-day weather forecast.
- Implement a favorites feature for saving commonly searched cities.
- Enhance UI with additional weather icons and animations.
- Secure the API key using environment variables or a backend service.

## License
This project is open-source and free to use under the MIT License.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request with your improvements.

## Feedback
If you have any feedback or feature requests, please feel free to open an issue or reach out.

---
Enjoy using WeatherNest and stay updated on the weather! 🌤️
