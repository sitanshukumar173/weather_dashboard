# weather_dashboard


# Weather Forecast Application

## Summary

This project is a Weather Forecast application that provides users with current weather conditions and forecasts for their location or any city they search for. The application fetches weather data using the Open-Meteo API and geocoding data using the OpenCage Geocoding API. The weather data includes current temperature, wind speed, sunrise and sunset times, and daily and weekly forecasts.

### Features

- **Live Time and Date**: Displays the current time and date based on the user's location.
- **Current Weather**: Provides current weather conditions including temperature, wind speed, and air quality.
- **Daily Forecast**: Displays hourly weather forecast for the current day.
- **Weekly Forecast**: Provides a 7-day weather forecast.
- **Dynamic Background**: Changes the background image every minute to reflect different weather conditions.
- **Loading Animation**: Shows a loading animation while fetching weather data.
- **Responsive Design**: Ensures compatibility with various screen sizes and devices.

### How It Works

1. **Fetch Weather Data**: The application fetches weather data using the Open-Meteo API based on the user's current location or a city name entered by the user.
2. **Geolocation**: If the user opts to fetch weather data for their current location, the application uses the browser's Geolocation API to get the latitude and longitude.
3. **City Search**: Users can search for weather data by entering a city name. The application uses the OpenCage Geocoding API to convert the city name to geographic coordinates.
4. **Display Data**: The fetched weather data is displayed in various sections including current weather, hourly forecast, and weekly forecast.
5. **Progress Circle**: A progress circle shows the percentage of the day that has passed, with dynamic color changes based on the time.
6. **Loading Animation**: A loading animation is displayed while the application fetches weather data.

### Technologies Used

- HTML
- CSS
- JavaScript
- Open-Meteo API
- OpenCage Geocoding API
- Font Awesome Icons
- Google Fonts
- Bootstrap Icons

### Authors

- Sitanshu Kumar ([sitanshukumar173](https://github.com/sitanshukumar173))
- Harsh Sharma ([PentagonCoder](https://github.com/PentagonCoder))



### Notes

- Ensure you have an API key for the OpenCage Geocoding API and replace the placeholder in the code with your actual key.
- The application is designed to provide a smooth user experience with dynamic background changes and responsive design.

Feel free to explore and contribute to this project by submitting issues or pull requests on GitHub. 
