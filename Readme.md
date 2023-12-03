Weather Application

This Weather Application is a simple web application that allows users to fetch weather data based on their current location. The application consists of two main pages: index.html and weather.html. The user can click the "Fetch Data" button on the index page to navigate to the weather page and view detailed weather information.
Table of Contents

    Getting Started
    Usage
    Folder Structure
    Styles
    JavaScript Functions
    API Integration
    Contributing

Getting Started

To run the Weather Application, simply open the index.html file in a web browser. Click the "Fetch Data" button to navigate to the weather.html page, where you can view your current location, a map, and detailed weather information.
Usage

    Fetch Data Button: Clicking the "Fetch Data" button on the index page redirects you to the weather page.

    Weather Page: The weather page displays your current location, a map with your latitude and longitude, and detailed weather information including location, wind speed, humidity, time zone, pressure, wind direction, UV index, feels like temperature, description, and current time.

Folder Structure

    index.html: The main page with the "Fetch Data" button.
    weather.html: The page displaying detailed weather information.
    style.css: Styles for the index page.
    weather.css: Styles for the weather page.
    script.js: JavaScript file containing common functions and page-specific functionality.

Styles

The application uses CSS to style the user interface. Styles are separated into style.css for the index page and weather.css for the weather page. These styles ensure a visually appealing and responsive design.
JavaScript Functions

    Common Functions: Shared functions between index.html and weather.html are defined in the script.js file. These include handling location errors and determining cardinal wind directions.

    Index Page Functions: The fetchDataBtn click event redirects the user to the weather.html page.

    Weather Page Functions: The fetchLocationAndDisplayMap function fetches the user's location and displays a map. Weather data is fetched using the OpenWeatherMap API, and the displayWeatherData function shows the retrieved information on the weather page.

API Integration

The Weather Application integrates with the OpenWeatherMap API to fetch real-time weather data based on the user's location. Replace the API key in the fetchWeatherData function with your own OpenWeatherMap API key.
Contributing

Contributions to the Weather Application are welcome! Feel free to open issues or pull requests to suggest improvements, report bugs, or add new features.

