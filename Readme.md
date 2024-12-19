# Project Title: Village Soul of India Restaurant Data Prediction

The project is implemented in Python using Jupyter Notebooks and includes three major modules:

1. **Get Lowest Local Price**: Retrieves the lowest local price for products.
2. **Get Busy Times & Bad Weather**: Determines peak activity periods and adverse weather conditions.
3. **Display Village Menu with Predicted Prices**: Utilizes ML algorithms to predict and display optimal prices.

---

## Features

- **Weather Integration**: Automatically fetches real-time weather data and converts temperature from Kelvin to Fahrenheit.
- **Busyness Detection**: Identifies peak times using historical or live data.
- **Dynamic Pricing**: Adjusts product prices based on weather and busyness conditions. 

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt

## API Setup

1. Google Places API
    Obtain an API key from [Google Places API](https://developers.google.com/maps/documentation/places/web-service/get-api-key)
    Add the key to the respective notebook under **GOOGLE_API_KEY**.
2. Weather API
    Obtain an API key from [OpenWeather](https://openweathermap.org/)
    Add the key to the respective notebook under **WEATHER_API_KEY**.