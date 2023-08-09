# Weather Data API Web Application

Welcome to the Weather Data API Web Application project! This Flask-based web application allows you to access and visualize weather data from various stations. It provides endpoints to retrieve weather information for specific dates, years, and stations.

## Overview

The Weather Data API Web Application leverages the Flask framework to create a user-friendly interface for accessing weather data. The app offers the following features:

- **Home Page (`home.html`)**: Displays a table of available weather stations. Provides links to access weather data APIs.

- **API Endpoints (`main.py`)**: Offers several API endpoints to retrieve weather data, including specific dates, years, and complete station data.

- **About Page (`about.html`) and Tutorial Page (`tutorial.html`)**: Informational pages about the project and website, including navigation links and sample images.

## Files and Structure

- `main.py`: The core Flask application that defines the API endpoints and runs the server.
- `templates/home.html`: The HTML template for the home page, displaying station data and API instructions.
- `static/`: Contains images and other static resources used in the templates.
- `templates/about.html`: An about page with a simple message.
- `templates/tutorial.html`: A tutorial page with navigation links and sample images.
- `data_small/`: Holds weather data files for various stations.
  
## How to Run

1. Install the required dependencies using `pip install Flask pandas`.

2. Run the Flask app: `python main.py`.

3. Access the app in your web browser at `http://127.0.0.1:5001`.

## Usage

- Visit the home page to see a list of available weather stations and links to API endpoints.

- Use the API endpoints to retrieve weather data for specific stations, dates, and years.

## Dependencies

- Python 3.x
- Flask
- Pandas

## Note

- This project demonstrates using Flask to create a web application with APIs. For production, consider security and performance enhancements.

- Weather data files in the `data_small/` directory are used for demonstration purposes.

## Conclusion

The Weather Data API Web Application project showcases how Flask can be used to build a web interface for data retrieval. Explore weather trends and access data with ease.

---
