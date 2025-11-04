# Weather App

A modern, responsive weather application that provides real-time weather information and hourly forecasts for any city worldwide.

<img width="847" height="477" alt="image" src="https://github.com/user-attachments/assets/912ee5c5-0527-4b9f-96b5-2a60268a92fb" />


## 🌐 Live Demo

Check out the live application: [https://moeezweatherapp.netlify.app/](https://moeezweatherapp.netlify.app/)

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **Hourly Forecast**: View 24-hour weather forecasts
- **Location Detection**: Automatically detect and display weather for your current location
- **City Search**: Search for weather information by city name
- **Weather Icons**: Custom SVG icons for different weather conditions
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Clean UI**: Modern, intuitive interface with smooth animations

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling with custom properties and responsive design
- **JavaScript (ES6+)**: Dynamic functionality and API integration
- **WeatherAPI**: Real-time weather data provider
- **Google Fonts**: Montserrat font family and Material Symbols

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Internet connection for API calls

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Moeeznagra/Weatherapp.git
```

2. Navigate to the project directory:
```bash
cd Weatherapp
```

3. Create a config.js file
```javascript
window.CONFIG = {
    API_KEY: "" # paste your api key here
};
```

3. Open `index.html` in your web browser or use a local server:
```bash
# Using Python 3
python -m http.server 8080

# Using Node.js
npx serve
```

4. Visit `http://localhost:8080` in your browser

## 📖 Usage

1. **Search by City**: Type a city name in the search box and press Enter
2. **Use Current Location**: Click the location button to get weather for your current location
3. **View Hourly Forecast**: Scroll through the hourly forecast section to see upcoming weather conditions

## 🎨 Weather Icons

The app includes custom SVG icons for various weather conditions:
- Clear/Sunny
- Clouds
- Mist/Fog
- Rain (Light and Heavy)
- Snow
- Thunder
- Thunder with Rain

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile phones

## 🔑 API Configuration

This app uses [WeatherAPI](https://www.weatherapi.com/) for fetching weather data.

## 🌍 Default Location

The app defaults to showing weather for **New York** on initial load.

## 📄 License

This project is open source and available for personal and educational use.

## 👨‍💻 Author

**Moeez Nagra**
