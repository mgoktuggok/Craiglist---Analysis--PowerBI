# Craigslist Vehicle Market Analysis (Power BI)

## 🎯 Business Problem
Second-hand vehicle listings suffer from inconsistent pricing and unclear quality indicators.
This project analyzes pricing, mileage, and condition patterns to support better buyer–seller decisions.

## 🧱 Data Source
- Craigslist vehicle listings (USA)
- ~400K records
- Cleaned and modeled in BigQuery

## 🔧 Data Modeling
- Star schema
- Fact: listings
- Dimensions: vehicle, location, time

## 📊 Key Metrics
- Average & median price
- Price per mile
- Condition score (engineered)
- Mileage bands

## 🧠 Key Insights
- Vehicles aged 5–8 years show the best price–mileage balance
- Price variance explodes above 120k miles
- Condition score strongly correlates with price per mile

## 🛠 Tools
- BigQuery (SQL)
- Power BI
- Python (feature engineering)
