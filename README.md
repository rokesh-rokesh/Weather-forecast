# Python Flask Weather Web Application

## Description:
This is a simple web application built with Python Flask framework to display current weather information based on user input of city name. It utilizes the OpenWeatherMap API to fetch real-time weather data.

## Features:

 User-friendly interface allowing users to input city name
    Fetches and displays current weather information including temperature, humidity, wind speed, etc.
    Responsive design for optimal viewing on various devices

# Requirements:
    Python 3.
    Flask
    Requests library
    OpenWeatherMap API key (sign up for a free API key at https://openweathermap.org/)

## Installation:
    
### Clone or download the repository to your local machine:

git clone https://github.com/rokesh-rokesh/Weather-forecast.git

 ###  Navigate to the project directory:


cd flask-weather-app

 ###  Install dependencies using pip:

pip install -r requirements.txt

### Configuration:
  Sign up for a free API key at https://openweathermap.org/ and note it down.
    Open the config.py file and replace "YOUR_API_KEY" with your actual OpenWeatherMap API key.

API_KEY = "YOUR_API_KEY"
### Running the Application:
  After configuring the API key, you can start the Flask application by running the following command:
python app.py
    Once the server is running, you can access the application by navigating to http://localhost:5000 in your web browser.

## Usage:
  Enter the name of the city for which you want to check the weather in the input field.
    Click on the "Get Weather" button.
    The current weather information for the entered city will be displayed on the screen.

## Contributing:

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or create a pull request.
