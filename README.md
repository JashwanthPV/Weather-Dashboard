# Weather-Dashboard
A web app where users can enter a city name and get the current weather using a public API like OpenWeatherMap.

1. URL Shortener

Description

A simple URL shortening service where users can input a long URL and receive a short, unique link that redirects to the original URL.

Features

Input a long URL and generate a shortened version.

Redirect to the original URL using the shortened link.

In-memory storage for simplicity (no database).

Technologies Used

Python

Flask

HTML/CSS (Bootstrap for styling)

Installation Instructions

Clone the repository or download the code.

Navigate to the project directory.

Create a virtual environment and activate it:

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install flask

Run the application:

python app.py

Open your browser and visit http://127.0.0.1:5000/.

Usage

Enter a long URL in the input field and click "Shorten".

A shortened URL will be displayed, which you can use to redirect to the original URL.

File Structure
url_shortener/
├── app.py
├── templates/
│   └── index.html
└── requirements.txt
