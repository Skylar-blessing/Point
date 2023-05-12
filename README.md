# Point
This code seems to be a React application that displays weather information and a search feature to retrieve the weather information for different locations.

# Installation
To run the application locally, clone the repository and run the following commands:

npm init vite@latest
npm install tailwindcss postcss autoprefixer
npm install react-select-async-paginate

(npm run dev) to start our application.

# Usage
After starting the application, enter a city name or zip code into the search bar and press the "Search" button. The app will display the current weather information for the location.

# Features
Search for weather information by city name or zip code
Display current weather information, including temperature, humidity, wind speed, and weather conditions
Error handling for invalid searches

# Technologies Used
React
OpenWeather API

# Contributing
Group Six



# Components Explained
The CurrentWeather component displays the current weather information for a specific location. It receives a data object as a prop containing information about the city, weather description, temperature, feels like, wind speed, humidity, and pressure.
The Forecast component displays the weather forecast for the next seven days. It receives a data object as a prop containing an array of objects with weather information for each day.
The Search component provides a search feature to retrieve weather information for different locations. It uses the AsyncPaginate component from the react-select-async-paginate library to display a searchable dropdown menu with a list of cities. It receives an onSearchChange function as a prop to pass the selected city data to the parent component.
The code also imports various React and third-party components, APIs, and CSS styles.

# License
This project is licensed under the MIT License.






