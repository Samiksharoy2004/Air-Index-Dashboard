#  Real-Time Air Quality & Weather Dashboard - Power BI

This repository showcases a **real-time, interactive Power BI dashboard** that visualizes **air quality and weather metrics** for 5 major metropolitan cities in India. The project integrates **live weather data from WeatherAPI**, performs **data preprocessing**, and presents insights using **custom DAX measures** and rich visuals.

---

##  Dashboard Features

-  **Live Weather Metrics**  
  - Temperature, Humidity, Pressure, Wind Speed, UV Index, Visibility
-  **Forecast Weather**  
  - 7-day temperature trend line  
  - Daily rain probability with interactive bar charts
- **Sunrise & Sunset Timings**
   **Air Quality Index (AQI)**  
  - Real-time monitoring of PM10, PM2.5, SO2, NO2, CO, and O3  
  - AQI health classification (Good, Moderate, etc.) with color-coded indicators
-    Cities Covered - Pune, Bangalore, Chandigarh, Chennai, Mumbai
---

## Tools & Technologies

- **Power BI Desktop**  
  - Data Modeling (Star Schema), DAX Measures, KPI Cards, Visualizations
- **Power Query (M Language)**  
  - JSON Parsing, Data Transformation, Cleaning, and Shaping
- **WeatherAPI**  
  - Live API integration via Web Connector for real-time updates
- **DAX**  
  - Measures for AQI classification, rain probability, and dynamic visual indicators

---

## 🔧 Data Preprocessing Workflow

1. **API Integration**  
   - Connected WeatherAPI JSON endpoints using Power BI Web Data Connector.
2. **Data Transformation (Power Query)**  
   - Flattened nested JSON  
   - Handled missing values, converted units, formatted datetime
3. **Data Modeling**  
   - Built relationships and created calculated columns for categorization.
4. **Measure Creation (DAX)**  
   - Created dynamic measures for AQI classification, rolling averages, and conditional formatting.

---

## 📈 Visual Design Highlights

- **Custom themes** with intuitive color palettes (e.g., salmon for alerts, blue for safe levels)
- **Interactive visuals**: line plots, bar charts, gauge KPIs, icons
- **User-friendly layout** with responsive design for real-time analysis

---

## 🚀 Future Enhancements

- 🌍 Add Geo-mapping for AQI zones
- 📱 Mobile-optimized dashboard views
- ☁️ Deploy to Power BI Service with scheduled auto-refresh

#Tags  
`#PowerBI` `#DataAnalytics` `#AirQuality` `#LiveData` `#WeatherAPI` `#BusinessIntelligence` `#DAX` `#PowerQuery` `#DataVisualization` `#SmartCities`
