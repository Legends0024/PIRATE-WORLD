# Weather App in Python

## 📌 Introduction
This is a simple Weather App built using Python. The application fetches real-time weather data based on user input and displays temperature, humidity, and weather conditions.

## 🛠 Features
- Fetches real-time weather data
- Displays temperature, humidity, and weather conditions
- Uses `requests` module to fetch data from an API
- User-friendly console interface

## 📂 Project Structure
```
📁 Weather-App
│-- weather_app.py  # Main Python script
│-- config.py  # Configuration file for API key
│-- README.md  # Project documentation
```

## 🚀 Requirements
Ensure you have the following dependencies installed before running the project:

- Python 3.x
- `requests` module (for API calls)

Install missing dependencies using:
```sh
pip install requests
```

## 🖥 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```
2. Get an API key from [OpenWeatherMap](https://openweathermap.org/api) and add it to `config.py`:
   ```python
   API_KEY = 'your_api_key_here'
   ```
3. Run the script:
   ```sh
   python weather_app.py
   ```
4. Enter the city name to fetch weather details.

## 📝 Usage Example
```
Enter city name: New York
Weather: Clear sky
Temperature: 25°C
Humidity: 60%
```

## 🛠 Future Improvements
- GUI-based weather app
- Hourly weather updates
- Support for multiple weather APIs



---
Feel free to modify this README to suit your project! 🚀

