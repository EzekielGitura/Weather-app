# 🌦️ WeatherWise

<div align="center">
  <img src="https://raw.githubusercontent.com/ezekielgitura/weatherwise/main/public/assets/weatherwise-logo.gif" alt="WeatherWise Logo" width="200"/>
</div>

[![React](https://img.shields.io/badge/React-18.2.0-61dafb?style=for-the-badge&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-3178c6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.3.0-38bdf8?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Electron](https://img.shields.io/badge/Electron-24.0.0-47848f?style=for-the-badge&logo=electron)](https://www.electronjs.org/)
[![React Native](https://img.shields.io/badge/React_Native-0.71.0-61dafb?style=for-the-badge&logo=react)](https://reactnative.dev/)

WeatherWise is a, feature-rich weather application that provides detailed weather information, intelligent activity recommendations, and powerful weather comparison tools.

## ✨ Features

### 🔔 Smart Notifications
- Real-time weather alerts
- Customizable notification preferences
- Location-based weather warnings
- Daily weather summaries

![Notifications Demo](public/assets/notifications-demo.png)

### 🗺️ Advanced Weather Maps
- Multiple weather layers (temperature, precipitation, wind)
- Interactive radar data
- Custom map styles
- Location marking and sharing

![Weather Maps Demo](public/assets/maps-demo.png)

### 📊 Location Comparison
- Side-by-side weather comparison
- Historical data analysis
- Temperature and precipitation trends
- Detailed metrics comparison

![Comparison Demo](public/assets/comparison-demo.png)

### 🎯 Activity Recommendations
- Weather-based activity suggestions
- Personalized recommendations
- Activity planning calendar
- Local event integration

![Activities Demo](public/assets/activities-demo.png)

## 🚀 Installation

### Desktop App (Windows, macOS, Linux)

```bash
# Clone the repository
git clone https://github.com/yourusername/weatherwise.git

# Navigate to the project directory
cd weatherwise

# Install dependencies
npm install

# Start the development server
npm run dev

# Build for production
npm run build
```

### Android App

1. Download the APK from the [latest release](https://github.com/yourusername/weatherwise/releases)
2. Enable "Install from Unknown Sources" in your Android settings
3. Open the APK file to install

Or build from source:

```bash
# Navigate to the android directory
cd android

# Install dependencies
npm install

# Run the development build
npm run android

# Create a release build
npm run android:release
```

## 💻 Development

```javascript
// Example: Adding a custom weather layer
import { WeatherMap } from '../components/maps/WeatherMap';

const CustomLayer = () => {
  return (
    <WeatherMap>
      <LayerControl>
        <WeatherLayer 
          type="temperature" 
          opacity={0.7} 
          colorScale="rainbow" 
        />
      </LayerControl>
    </WeatherMap>
  );
};
```

## 🔧 Configuration

Create a `.env` file in the root directory:

```env
REACT_APP_WEATHER_API_KEY=your_api_key
REACT_APP_MAPBOX_TOKEN=your_mapbox_token
```

## 📱 Screenshots

<div align="center">
  <img src="public/assets/screenshot-1.png" width="200" />
  <img src="public/assets/screenshot-2.png" width="200" />
  <img src="public/assets/screenshot-3.png" width="200" />
  <img src="public/assets/screenshot-4.png" width="200" />
</div>

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenWeatherMap API for weather data
- Mapbox for mapping services
- Icons by [Lucide](https://lucide.dev)
- UI components by [shadcn/ui](https://ui.shadcn.com)
