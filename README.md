# 🌦️ Weather Intelligence Dashboard (Power BI)

A modern, interactive **Weather Analytics Dashboard** built using **Power BI**, powered by real-time weather API data and transformed into a structured dataset (`masterReport.csv`).

---

## 📌 Overview

The dashboard provides a comprehensive view of weather conditions, including:

- Current temperature and conditions  
- Multi-city comparison  
- 7-day forecast trends  
- Air quality metrics  
- Rain probability analysis  
- Key environmental indicators  

The project follows a complete pipeline:  
**API → Data Transformation → Data Modeling → Visualization → CSV Export**

---

## 🚀 Features

- Real-time weather data integration (API-based)  
- Interactive and visually rich dashboard  
- Multi-location comparison (Mumbai, Pune, Shimla)  
- Forecast trend visualization (line chart)  
- Air Quality Index (PM10, CO, NO2, SO2, O3)  
- Rain probability tracking  
- Sunrise & sunset insights  
- Clean dark-themed modern UI  

---

## 🛠️ Tech Stack

- **Power BI Desktop** – Visualization  
- **Weather API** – Data source  
- **Power Query** – Data transformation  
- **DAX** – Measures & calculations  
- **CSV (masterReport.csv)** – Dataset  

---

## 📂 Dataset

- **File Name:** `masterReport.csv`  
- **Source:** Weather API (converted from JSON)  

**Includes:**
- Location details  
- Current weather metrics  
- Forecast (hourly & daily)  
- Air quality data  

---

## 🔄 Workflow

### 1. Data Collection
- Extracted weather data using API (JSON format)

### 2. Data Transformation
- Flattened nested JSON using Power Query  
- Cleaned and structured columns  
- Handled missing values  

### 3. Data Modeling
- Created relationships between tables  
- Built calculated measures using DAX  

### 4. Dashboard Development
- Designed UI-focused dashboard with:
  - KPI cards  
  - Charts & graphs  
  - Comparative visuals  

### 5. Data Export
- Converted API data into CSV (`masterReport.csv`)  
- Enabled reuse and GitHub integration  

---

## 📊 Dashboard Components

- **Current Weather Panel** – Temperature & condition  
- **Forecast Chart** – Temperature trends  
- **Air Quality Section** – Pollution metrics  
- **Weather Cards** – Humidity, Wind, Pressure, Visibility  
- **Rain Probability** – Daily analysis  
- **Sunrise & Sunset** – Time indicators  

---

## 💡 Key Learnings

- API integration in Power BI  
- Handling complex JSON data  
- Data modeling using DAX  
- Dashboard UI/UX design  
- Converting API data into CSV  

---

## 🔮 Future Enhancements

- Automate API → CSV pipeline  
- Add dynamic location filters  
- Deploy dashboard online  
- Integrate ML-based predictions  

---

## 📁 Project Structure
Weather-Dashboard/
│── dataset/
│ └── masterReport.csv
│── dashboard/
│ └── weather_dashboard.pbix
│── README.md

---

## 📷 Preview

<img width="1284" height="713" alt="Screenshot 2026-04-03 220647" src="https://github.com/user-attachments/assets/d6697275-9fa2-42eb-aac7-128baa8bbe84" />



