# Weather App

A simple weather app that allows users to enter a city name and retrieve current weather information, such as the condition, temperature, wind speed, and humidity.

## Features

- Get current weather details for any city.
- Displays weather condition, temperature, wind speed, and humidity.
- Responsive design for mobile devices.
- Error handling for invalid city names.
- Stylish and user-friendly interface.

## Demo

You can try the Weather App by entering a city name and clicking on the "Get Weather" button.

## Technologies Used

- **HTML5**: Markup language for creating the structure of the page.
- **CSS3**: For styling the page and making it visually appealing.
- **JavaScript**: To handle fetching weather data from an external API (`wttr.in`).

## How to Use

1. Open the `index.html` file in your web browser.
2. Enter a city name in the input field.
3. Click the "Get Weather" button to retrieve the weather details.
4. The app will display the weather condition, temperature, wind speed, and humidity.
5. If an invalid city name is entered, an error message will be displayed.

## How It Works

The app uses the **wttr.in** API to fetch the weather data. It sends an HTTP request to fetch weather information in a specified format and displays it on the page.

1. **User Input**: The user enters the city name in the input field and clicks the "Get Weather" button.
2. **Fetch Weather Data**: The JavaScript fetches weather data from the API based on the entered city name.
3. **Display Weather**: The weather information is parsed and displayed in the page, showing the current condition, temperature, wind speed, and humidity.
4. **Error Handling**: If the city name is invalid or no city is entered, an error message is shown.

## Installation

There is no installation required. Simply open the `index.html` file in any modern web browser.

## Usage Example

- Enter "New York" in the input field.
- Click on "Get Weather."
- The app will display weather information such as:
  - **Condition**: Clear
  - **Temperature**: 23°C
  - **Wind**: 5 km/h
  - **Humidity**: 75%

## License

This project is open-source and available under the [MIT License](LICENSE).
