```markdown
# 🌤️ WeatherNow

A sleek, responsive weather application built with modern web technologies. Get real-time weather data and beautiful 7-day forecasts powered by the free Open-Meteo API.

![Design preview for the Weather app](./preview.jpg)

[![GitHub Stars](https://img.shields.io/github/stars/filipecosgom/WeatherNow?style=social)](https://github.com/filipecosgom/WeatherNow)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

- 🔍 **Location Search** - Find weather for any location worldwide
- 📊 **Current Weather** - Temperature, "feels like", humidity, wind speed, and more
- 📅 **7-Day Forecast** - Plan ahead with daily high/low temperatures
- ⏰ **Hourly Forecast** - Hour-by-hour temperature changes throughout the day
- 🔄 **Unit Toggle** - Switch between Celsius/Fahrenheit and metric/imperial units
- 📱 **Fully Responsive** - Optimized layouts for mobile, tablet, and desktop
- ⚡ **No API Key Required** - Uses the free Open-Meteo API
- 🎨 **Beautiful UI** - Modern design with smooth animations

---

## 📱 Mobile Design

### Metric Units (Celsius & km/h)
![Mobile - Metric Units](./design/mobile-metric.png)

### Imperial Units (Fahrenheit & mph)
![Mobile - Imperial Units](./design/mobile-imperial.png)

---

## 🖥️ Desktop Design

### Main View - Metric Units
Displays weather with Celsius temperatures and metric measurements
![Desktop - Metric Units](./design/desktop-metric.png)

### Main View - Imperial Units
Same layout showing Fahrenheit temperatures and imperial measurements
![Desktop - Imperial Units](./design/desktop-imperial.png)

---

## 🎯 Interactive States

### Units Menu - Open
Users can switch between different measurement units
![Desktop - Units Menu](./design/desktop-units-menu.png)

### Units Menu - Expanded
Full dropdown showing all unit options with checkmarks
![Desktop - Units Menu Expanded](./design/desktop-units-menu-expanded.png)

### Units Menu - Hover State
Visual feedback when hovering over units dropdown
![Desktop - Units Hover](./design/desktop-units-hover.png)

---

## ⚙️ Loading & Error States

### Loading State
Animated skeleton screens while fetching weather data
![Loading State](./design/desktop-loading.png)

### No Search Results
User-friendly message when location is not found
![No Results](./design/desktop-no-search-results.png)

### Search in Progress
Live search suggestions displayed as user types
![Search Progress](./design/desktop-search-in-progress.png)

### Error State
Connection error handling with retry button
![Error State](./design/desktop-error.png)

---

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **SCSS** - Modular styling with variables and mixins
- **JavaScript** - Dynamic functionality and API integration
- **Open-Meteo API** - Free weather data
- **Figma Design** - Professional UI/UX design

---

## 🚀 Quick Start

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No API key needed!

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/filipecosgom/WeatherNow.git
   cd WeatherNow
   ```

2. **Open in browser**
   Simply open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

3. **Visit the app**
   Open `http://localhost:8000` in your browser

---

## 📖 How to Use

1. **Search for a location** - Enter a city name or select from suggestions
2. **View current weather** - See temperature, conditions, and detailed metrics
3. **Check forecasts** - Browse 7-day outlook and hourly predictions
4. **Toggle units** - Use the Units dropdown to switch between metric/imperial
5. **Select different days** - Click on days to see their hourly forecast

---

## 🌐 API Details

This project uses the **Open-Meteo API** - a free, open-source weather API.

- **Documentation**: [open-meteo.com](https://open-meteo.com/)
- **Rate Limits**: Unlimited for personal use
- **Authentication**: None required
- **Coverage**: Worldwide weather data

### Example API Call
```
https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&current_weather=true
```

---

## 📁 Project Structure

```
WeatherNow/
├── assets/
│   ├── fonts/           # Typography files
│   └── images/          # Icons and backgrounds
├── design/              # Design files (mobile & desktop)
├── src/
│   └── scss/            # Modular SCSS files
│       ├── _variables.scss
│       ├── _typography.scss
│       ├── _layout.scss
│       ├── _components.scss
│       ├── _cards.scss
│       ├── _searchbar.scss
│       ├── _loading.scss
│       └── main.scss
├── index.html
├── style.css
└── script.js
```

---

## 💡 Future Enhancements

- [ ] Weather alerts and warnings
- [ ] User location detection
- [ ] Weather history graphs
- [ ] Multiple location bookmarks
- [ ] Dark/light theme toggle
- [ ] PWA offline support

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Filipe Gomes**
- GitHub: [@filipecosgom](https://github.com/filipecosgom)
- Email: filipe.cosgom@gmail.com

---

## 🙏 Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io) - For the design challenge
- [Open-Meteo](https://open-meteo.com/) - For the free weather API

---

<div align="center">
  Made by Filipe Gomes
</div>
```

If the filenames in your design folder are different, just let me know and I'll update the paths. The image paths assume they follow a naming pattern like `mobile-metric.png`, `desktop-metric.png`, etc.
