🌤️ Weather Forecasting Dashboard using API + Power BI

🚀 Project Overview
Designed and developed a dynamic weather forecasting dashboard using Power BI connected to a real-time REST API (https://www.weatherapi.com/)

Automated the entire ETL process using Power Query M, fetching weather data for multiple cities directly from the API.

Built interactive dashboards to visualize temperature, humidity, wind speed, and weather conditions in real-time.

Integrated scheduled refresh to ensure the dashboard stays up-to-date without manual intervention.

https://github.com/Piyush-tikiya/API/blob/main/weather%20dash%20v1.png

[🔗 Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=785e75ac-1c86-4ede-a7a6-9829dfe6a15a&autoAuth=true&ctid=c6e549b3-5f45-4032-aae9-d4244dc5b2c4&actionBarEnabled=true&reportCopilotInEmbed=true)


Tools Used:

Power BI (Query Editor, Data Modeling, Custom Visuals)
Data Transformation & Cleaning
Power Query M
API Integration
JSON Data Handling
Power BI Services - Scheduled Refresh

🧠 Key Features

🌍 Multi-City Weather Fetching – Automatically pulls weather data for a list of cities

⚙️ API Integration with Power Query – GET request to REST endpoint using Web.Contents

📥 JSON Parsing & Transformation – Extracted nested fields such as main.temp, wind.speed, weather.description

♻️ Scheduled Refresh Automation – Updates data at set intervals without manual refresh

📊 Interactive Dashboard – Real-time display of temperature, humidity, and wind trends

🔁 Unit Conversion Logic – Converted temperature units from Kelvin/Fahrenheit to Celsius

🧪 Error Handling with try...otherwise – Handled missing/null API responses gracefully

Challenge I faced while doing this project:

Yes, I created a live weather forecasting dashboard using an external API. The API returned JSON, so I had to parse nested records, convert units for eg. Fahrenheit to Celsius), handle missing values and make sure it worked across multiple locations. Everything was automated using scheduled refreshes — no Excel involved.
