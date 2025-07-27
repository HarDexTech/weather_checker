# Weather Checker App 🌤️

A clean, responsive web application that provides real-time weather information for any city worldwide. Built with vanilla HTML, CSS, and JavaScript.

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **Responsive Design**: Optimized for all screen sizes (320px to 1200px+)
- **Clean UI**: Modern design with glassmorphic effects
- **Easy Search**: Search by city name with Enter key support
- **Comprehensive Info**: Temperature, feels-like temp, conditions, humidity, and wind speed
- **Error Handling**: User-friendly messages for invalid cities or network issues

## 🚀 Demo

To try the app locally, simply open `index.html` in your web browser after following the setup instructions below.

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox, CSS Grid, and media queries
- **JavaScript (ES6+)**: Fetch API for weather data retrieval
- **OpenWeatherMap API**: Real-time weather data source
- **Google Fonts**: Open Sans font family

## 📋 Prerequisites

Before running this project, you'll need:

- A modern web browser
- Internet connection
- OpenWeatherMap API key (free registration required)

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. **Get an API key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate an API key

3. **Configure the API key**
   - Open `index.html`
   - Replace the existing API key in the JavaScript section:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   ```

4. **Launch the application**

## 🎯 Usage

1. Enter a city name in the search box
2. Click the search button (🔍) or press Enter
3. View the weather information including:
   - Current temperature
   - Feels-like temperature
   - Weather conditions
   - Humidity percentage
   - Wind speed

## 📱 Responsive Breakpoints

The app is optimized for the following screen sizes:

- **Large screens**: 1200px and above
- **Desktop**: 769px - 1199px
- **Tablet**: 640px - 768px
- **Mobile landscape**: 480px - 639px
- **Mobile portrait**: 360px - 479px
- **Small mobile**: 320px - 359px

## 🎨 Customization

### Colors
The app uses a green color scheme. To customize:

```css
/* Main background */
body { background: #CDF4E0; }

/* Card background */
.main { background-color: #8ed968; }

/* Input/button background */
.search input, .search button { background: #ebfffc; }
```

### Fonts
Currently uses Google Fonts' Open Sans. To change:

```css
@import url("https://fonts.googleapis.com/css2?family=YourFont:wght@200;300;400;500;600;700&display=swap");

* { font-family: 'YourFont', Arial, sans-serif; }
```

## 🔍 API Information

This app uses the OpenWeatherMap Current Weather API:
- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Units**: Metric (Celsius, meters/second)
- **Rate Limit**: 1000 calls/day (free tier)

## 🚧 Known Issues

- API key is exposed in client-side code (consider using environment variables for production)
- No offline functionality
- Limited to current weather (no forecast)

## 🔮 Future Enhancements

- [ ] Weather icons for different conditions
- [ ] 5-day weather forecast
- [ ] Geolocation support
- [ ] Temperature unit toggle (°C/°F)
- [ ] Search history/favorites
- [ ] Weather maps integration
- [ ] Dark/light theme toggle
- [ ] Progressive Web App (PWA) features

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Your Name**
- GitHub: [@HarDexTech](https://github.com/HarDexTech)
- LinkedIn: [Adesina Ayomide](https://www.linkedin.com/in/HarDexTech/)
- Email: adesinayomide2@gmail.com

## 🙏 Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API
- [Google Fonts](https://fonts.google.com/) for the Open Sans font
- Icons and inspiration from various web design resources

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ Internet Explorer (not recommended)

---

⭐ **If you found this project helpful, please give it a star!** ⭐
