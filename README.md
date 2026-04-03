🌦️ Weather Analytics Dashboard (Power BI)

A modern, interactive Weather Analytics Dashboard built using Power BI, powered by real-time data from a weather API and transformed into a structured dataset (masterReport.csv).

This project focuses on data analysis + UI/UX design, delivering actionable weather insights through a clean, visually rich dashboard.

📌 Overview

The dashboard provides a comprehensive view of weather conditions, including:

Current temperature and conditions
Multi-city comparison
7-day forecast trends
Air quality metrics
Rain probability analysis
Key environmental indicators

The data pipeline involves API extraction → transformation → modeling → visualization → CSV export.

🚀 Features
Real-time weather data integration (API-based)
Interactive and responsive dashboard
Multi-location comparison (e.g., Mumbai, Pune, Shimla)
Forecast trend visualization (line chart)
Air Quality Index (AQI) breakdown (PM10, CO, NO2, SO2, O3)
Rain probability visualization
Sunrise & sunset tracking
Clean dark-themed UI with modern design principles
🛠️ Tech Stack
Power BI Desktop – Data visualization
Weather API – Data source
Power Query – Data transformation
DAX – Calculations & measures
CSV (masterReport.csv) – Structured dataset
📂 Dataset
Name: masterReport.csv
Source: Weather API (converted from JSON to CSV)
Contents:
Location details
Current weather metrics
Hourly & daily forecast
Air quality indicators
🔄 Workflow
1. Data Collection
Extracted weather data using API (JSON format)
2. Data Transformation
Flattened nested JSON using Power Query
Cleaned and formatted columns
Handled missing values and datatypes
3. Data Modeling
Built relationships between datasets
Created calculated measures using DAX
4. Dashboard Development
Designed UI-focused dashboard with:
KPI cards
Line charts
Progress indicators
Comparative visuals
5. Data Export
Converted API data into reusable CSV (masterReport.csv)
Used for GitHub integration and project portability
📊 Dashboard Components
Current Weather Panel – Temperature & condition
Forecast Chart – Trend over days
Air Quality Section – Pollution metrics
Weather Metrics Cards – Humidity, Wind, Pressure, Visibility
Rain Probability – Daily chances
Sunrise & Sunset – Time indicators
💡 Key Learnings
Integrating APIs with Power BI
Transforming complex JSON data
Data modeling and DAX calculations
Designing user-friendly dashboards
Converting dynamic data into static datasets
🔮 Future Enhancements
Automate API to CSV pipeline
Add dynamic location selection
Deploy dashboard to web
Integrate predictive analytics (ML models)
📁 Project Structure
Weather-Dashboard/
│── dataset/
│   └── masterReport.csv
│── dashboard/
│   └── weather_dashboard.pbix
│── README.md
📷 Preview





⭐ Acknowledgment

Inspired by a Weather API + Power BI implementation, extended with custom dataset handling and UI enhancements.
