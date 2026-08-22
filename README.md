# 🌤️ Weather App

A simple desktop **Weather Application** built with **Python, PyQt5, and the OpenWeatherMap API**.

The application allows users to enter a city name and retrieve its current weather information, including temperature, weather description, and a weather emoji.

## 📸 Screenshot

Add a screenshot of your application here:

```text
screenshots/weather-app.png
```

## ✨ Features

* 🌍 Search weather by city name
* 🌡️ Display current temperature in Celsius
* ☁️ Display weather description
* 🌧️ Weather-based emoji
* ⚠️ Handles common API and network errors
* 🖥️ Simple graphical user interface built with PyQt5

## 🛠️ Technologies Used

* **Python 3**
* **PyQt5** — GUI framework
* **Requests** — HTTP requests
* **OpenWeatherMap API** — Weather data

## 📁 Project Structure

```text
weather-app/
│
├── weather_app.py
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
    └── weather-app.png
```

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/weather-app.git
cd weather-app
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your API key

This application uses the OpenWeatherMap API.

Create an account and obtain an API key, then store it securely instead of putting the key directly in your source code.

For example, you can use an environment variable:

```text
OPENWEATHER_API_KEY=your_api_key_here
```

### 5. Run the application

```bash
python weather_app.py
```

## 🌦️ Example

Enter a city such as:

```text
Pune
```

The application will display information similar to:

```text
Pune

28.5°C

☁️

overcast clouds
```
<img width="386" height="512" alt="image" src="https://github.com/user-attachments/assets/12edf449-c549-40f6-bb31-e62147318c9f" />


## ⚠️ Error Handling

The application handles several possible errors, including:

* Invalid city name
* Invalid API key
* Connection errors
* Request timeouts
* HTTP errors
* Server errors
* Too many redirects

## 🔐 Security

**Do not upload your OpenWeatherMap API key to GitHub.**

If your API key has already been pushed to a public repository, revoke/regenerate it from OpenWeatherMap and replace it with a new key.

Use environment variables or another secret-management approach for API credentials.

## 🔮 Future Improvements

Possible improvements include:

* [ ] Add humidity
* [ ] Add wind speed
* [ ] Add feels-like temperature
* [ ] Add weather icons
* [ ] Add 5-day forecast
* [ ] Add country information
* [ ] Add automatic location detection
* [ ] Add loading indicator
* [ ] Improve UI design
* [ ] Add dark mode
* [ ] Store recent searches
* [ ] Add unit selection for Celsius/Fahrenheit
* [ ] Add input validation
* [ ] Move API calls to a background thread
* [ ] Package the application as a Windows executable
