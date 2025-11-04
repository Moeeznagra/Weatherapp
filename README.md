# Weather App

A modern, responsive weather application that provides real-time weather information and hourly forecasts for any city worldwide.

![Weather App Screenshot](https://github.com/user-attachments/assets/e7a6c026-7a91-41ae-b221-a532aef48da7)

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

This app uses [WeatherAPI](https://www.weatherapi.com/) for fetching weather data. The API key is included in the `script.js` file. For production use, consider:
- Using environment variables to store the API key
- Implementing a backend proxy to secure your API key

## 🌍 Default Location

The app defaults to showing weather for **Saskatoon** on initial load.

## 📄 License

This project is open source and available for personal and educational use.

## 👨‍💻 Author

**Moeez Nagra**

## 🙏 Acknowledgments

- Weather data provided by [WeatherAPI](https://www.weatherapi.com/)
- Icons and fonts from Google Fonts
- Hosted on [Netlify](https://www.netlify.com/)
