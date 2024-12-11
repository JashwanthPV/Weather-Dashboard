# Weather-Dashboard
A web app where users can enter a city name and get the current weather using a public API like OpenWeatherMap.

2. Weather Dashboard

Description

A web-based weather dashboard where users can enter a city name and get the current weather using the OpenWeatherMap API.

Features

Input a city name to fetch weather data.

Displays the temperature, city name, and weather condition.

Fetches real-time data using OpenWeatherMap API.

Technologies Used

Python

Flask

HTML/CSS (Bootstrap for styling)

OpenWeatherMap API

Installation Instructions

Clone the repository or download the code.

Navigate to the project directory.

Create a virtual environment and activate it:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install flask requests

Obtain an API key from OpenWeatherMap and replace your_openweathermap_api_key in app.py with your key.

Run the application:

python app.py

Open your browser and visit http://127.0.0.1:5000/.

Usage

Enter a city name in the input field and click "Get Weather".

The app will display the current temperature and weather condition for the specified city.

File Structure
weather_dashboard/
├── app.py
├── templates/
│   └── index.html
└── requirements.txt
