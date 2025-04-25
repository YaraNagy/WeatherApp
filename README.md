# WeatherApp

A simple, clean web application that displays the current weather conditions for a specified city using the OpenWeatherMap API.

## Features

*   **City Search:** Enter any city name to get its current weather.
*   **Current Weather Display:** Shows temperature (°C), city name, humidity (%), and wind speed (km/h).
*   **Dynamic Icons:** Displays relevant weather icons (Clear, Clouds, Rain, Drizzle, Mist) based on the current conditions.
*   **Responsive Design:** Basic responsive layout suitable for different screen sizes.
*   **Error Handling:** Displays a message if the entered city name is invalid or not found.

## Technologies Used

*   **HTML5:** For the structure of the web page.
*   **CSS3:** For styling the application, including the card layout and gradient background.
*   **Vanilla JavaScript:** For fetching data from the API, handling user input, and dynamically updating the DOM.
*   **OpenWeatherMap API:** To retrieve real-time weather data.


## Setup and Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YaraNagy/WeatherApp.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd WeatherApp
    ```
3.  **Open `weather.html` in your web browser.** No further build steps or installations are required.

4.  **Using the App:**
    *   Enter the name of a city in the search input field.
    *   Click the search button (magnifying glass icon).
    *   The weather information for the specified city will be displayed.
    *   If the city is not found, an "Invalid City Name!" error message will appear.

## API Key

This project uses an API key from [OpenWeatherMap](https://openweathermap.org/). The key is currently included directly in the `weather.js` file:

