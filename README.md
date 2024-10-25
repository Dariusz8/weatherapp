# Weather App README

## Overview

This Python application retrieves and displays weather data along with a related image for a specified city. The app utilizes two different APIs: one for fetching weather data and another for obtaining a relevant image based on the city name. 

## Features

- Fetch current weather information (temperature, humidity, conditions, etc.)
- Retrieve an image that represents the city's weather or scenery
- User-friendly command-line interface for city input
- Simple and clean output format

## Requirements

- Python 3.7 or higher
- `requests` library
- `json` library (included with Python)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install required packages:
   ```bash
   pip install requests
   ```

3. Set up API keys for the weather and image APIs:
   - Sign up for [OpenWeatherMap API](https://openweathermap.org/api) and obtain your API key.
   - Sign up for [Unsplash API](https://unsplash.com/developers) and obtain your API key.

4. Create a configuration file named `config.py` in the project directory:
   ```python
   WEATHER_API_KEY = 'your_openweathermap_api_key'
   IMAGE_API_KEY = 'your_unsplash_api_key'
   ```

## Usage

1. Run the application:
   ```bash
   python weather_app.py
   ```

2. When prompted, enter the name of the city you want to check the weather for.

3. The app will display the current weather information and an image related to the city.

## Example Output

```
Enter city name: London

Weather in London:
- Temperature: 15°C
- Humidity: 82%
- Conditions: Overcast clouds

Image: [URL of the image]
```

## API References

- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- [Unsplash API Documentation](https://unsplash.com/documentation)

## Troubleshooting

- Ensure that your API keys are correctly entered in `config.py`.
- Check your internet connection.
- If you encounter any errors, refer to the console output for more information.


## Contact

For questions or feedback, reach out at dariusz.czeczuk@hotmail.com and/or liamgilmore1@gmail.com
