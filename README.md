
# Weather App

This is a simple web-based weather application that allows users to check the current weather conditions for a specified location. The app fetches real-time weather data using the OpenWeather API and displays it in an intuitive interface.

## Features

- **Location-Based Weather Search**: Enter any location to retrieve current weather data.
- **Weather Details**: Displays temperature, weather description, humidity, and wind speed.
- **Error Handling**: Notifies the user if the location is not found.
- **Responsive Design**: Adjusts to different screen sizes.

## Technologies Used

- **HTML**: Structure of the app.
- **CSS**: Styling and layout (with animations and transitions for a smooth user experience).
- **JavaScript**: Fetching weather data and updating the UI.
- **OpenWeather API**: Provides real-time weather information.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. **Set up API Key**:
   - Sign up at [OpenWeather](https://openweathermap.org/) to get a free API key.
   - Open `script.js` and replace the placeholder API key with your own:
     ```javascript
     const APIKey = 'your-api-key-here';
     ```

3. **Run the App**:
   - Open `index.html` in your web browser.

## File Structure

- `index.html`: Main structure of the web page.
- `style.css`: Contains all styling for the app.
- `script.js`: JavaScript file for fetching data from the API and updating the DOM.

## Screenshots

Include screenshots of the application here if desired.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
