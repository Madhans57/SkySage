# 🌤️ SkySage - Weather Forecast App

**SkySage** is a sleek, feature-rich weather forecasting web app built with React. It provides real-time weather updates, interactive forecasts, and curated weather news — all inside a clean and responsive interface.

🔗 **Live Demo:** [https://sky-sage-weather.netlify.app/](https://sky-sage-weather.netlify.app/)

---

## 🚀 Features

- 🌍 Global city search with recent history
- 📆 3-hour and 5-day weather forecasts
- 📈 Interactive graphs for:
  - Temperature 🌡️
  - Pressure 🔽
  - Humidity 💧
- 📰 Weather-related news feed with clickable sources
- 🌡️ Toggle between Celsius and Fahrenheit
- 💨 Wind speed, 🌅 Sunrise & 🌇 Sunset in local time
- 📱 Fully responsive layout for all devices
- 👤 Personal accounts (coming soon)

---

## 🛠️ Tech Stack

- **Frontend:** React.js
- **APIs:** OpenWeatherMap, News API
- **Data Viz:** Recharts / Chart.js
- **Styling:** Custom CSS
- **Deployment:** Netlify

---

## ⚙️ Getting Started

To set up and run the project locally, follow these steps:

```bash
# 1. Clone the repository
git clone https://github.com/your-username/sky-sage.git
cd sky-sage

# 2. Install dependencies
npm install

# 3. Add API keys (create a .env file in the root folder)
echo "REACT_APP_WEATHER_API_KEY=your_openweathermap_api_key" >> .env
echo "REACT_APP_NEWS_API_KEY=your_newsapi_key" >> .env

# 4. Start the app
npm start
