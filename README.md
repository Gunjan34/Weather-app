# 🌦️ Weather App

A simple and responsive Weather App built using **HTML**, **CSS**, and **JavaScript**. It fetches real-time weather data using the [OpenWeatherMap API](https://openweathermap.org/api) and displays temperature, humidity, weather description, and wind speed based on the user’s location input.

## 🚀 Features

- 🔍 Search for weather by city name
- 🌡️ Displays temperature in Celsius
- 🌤️ Shows weather description and corresponding icons
- 💧 Displays humidity
- 💨 Displays wind speed
- 📛 Error handling for invalid locations
- 🎨 Responsive and clean user interface

## 🖥️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)
- [OpenWeatherMap API](https://openweathermap.org/api)
- Font Awesome Icons

## 📁 Project Structure

weather-app/
├── index.html
├── stylle.css
├── script.js
├── images/
│ ├── cloud.png
│ ├── clear (1).png
│ ├── rain.png
│ ├── mist.png
│ ├── snow.png
│ ├── 404.png
│ ├── 219816.png # Humidity icon
│ └── images.png # Wind icon
└── README.md



> 📌 **Note**: Make sure all images used (like `cloud.png`, `404.png`, etc.) are placed correctly inside the `/images` folder.

## 🛠️ How to Run

1. Clone the repository or download the project files.
2. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api).
3. Replace the API key in `script.js`:

```js
const api_key = "YOUR_API_KEY_HERE";
Open index.html in any modern web browser.




🌱 Future Improvements
Add current date and time

Add location-based weather detection using Geolocation API

Support for temperature units (°F/°C toggle)

Add loading animation during fetch

🤝 Acknowledgements
OpenWeatherMap API

Font Awesome
