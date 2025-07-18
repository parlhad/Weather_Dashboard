# 🌦️ Weather Dashboard using API and Power BI

An interactive Weather Dashboard displaying real-time and forecast data like temperature, humidity, air quality, and rain chances for cities including Hyderabad, using weather APIs in a user-friendly visual format.

---
## 🔗 Live Dashboard

👉 [View Dashboard in Power BI](https://app.fabric.microsoft.com/view?r=eyJrIjoiNzMxOGE4ZDQtMTYwOS00ZTEyLWE5MTctMzcwMDI5MzVkMGQ0IiwidCI6ImY5YTQzODQwLWY3OGUtNDE3Yy05ZDgwLTg5NTJhMmJhN2Y0YiJ9)
## 🖼️ Sample Screenshot

![Dashboard Screenshot](screenshots/weather_dashboard_ui.png)
---

## 📘 Project Overview

### 🔹 Main Features

- **Current Weather Conditions**: City-specific temperature, humidity, wind speed, pressure, and visibility.
- **7-Day Forecast**: Line chart with daily temperatures and weather icons.
- **Air Quality Index (AQI)**: Visual representation of pollutants like PM10, PM2.5, SO2, NO2, O3, CO.
- **Sunrise & Sunset Time**: Displays accurate timings based on selected city.
- **Rain Probability**: Horizontal bar chart for daily rain percentage.
- **Multi-City Tabs**: View weather reports for Amravati, Hyderabad, and Lucknow.

---

## 🛠️ Technologies Used

| Tool                     | Purpose                                          |
|--------------------------|--------------------------------------------------|
| Power BI                | Data visualization & interactive dashboard       |
| REST APIs (OpenWeather) | Fetching real-time weather and pollution data    |
| Figma (UI Design)       | Designing background and visual layout           |
| DAX / Power Query       | Data transformation, cleaning, and filtering     |
| Custom Icons & Cards    | Enhancing UI with consistent, intuitive elements |

---

## 📊 Dashboard Sections Breakdown

### 🌡️ Current Conditions
- **City Selector**: Switch between Hyderabad, Amravati, and Lucknow.
- **Temperature Display**: Shows temperature in Celsius with weather conditions.
- **Realtime Stats**: Humidity, Wind Speed, Pressure, and Visibility.

### 📈 Forecast Weather
- **7-Day Temperature Chart**: Interactive line graph displaying trends.
- **Weather Icons**: Symbols indicate rain, clouds, or sunshine.

### 🌄 Sunrise and Sunset
- **Sunrise**: e.g., 5:50 AM  
- **Sunset**: e.g., 6:53 PM

### 💧 Rain Probability
- **Rain Chances**: Daily bar chart with percentage values.

### 🌬️ Air Quality Index (AQI)
- **AQI Status**: Color-coded circle chart (e.g., Good, Moderate).
- **Pollutants Tracked**:
  - PM10
  - PM2.5
  - O3 (Ozone)
  - CO (Carbon Monoxide)
  - SO2 (Sulfur Dioxide)
  - NO2 (Nitrogen Dioxide)

---

## 🧠 Skills Demonstrated

- API Integration with Power BI
- Real-time and forecast data visualization
- Dashboard layout and UI planning using Figma
- Understanding and representation of environmental data
- Professional storytelling using visual design and metrics

---

## 📁 Folder Structure

```plaintext
weather-dashboard/
│
├── assets/                  # Images, backgrounds, icons
│   └── background.png
│
├── PowerBI/                 # PBIX file with full dashboard
│   └── Weather_Dashboard.pbix
│
├── screenshots/             # UI previews and readme assets
│   └── weather_dashboard_ui.png
│
├── README.md                # Project documentation
└── .gitignore               # Ignore unnecessary files
cture

