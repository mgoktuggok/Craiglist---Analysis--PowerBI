# Craigslist Vehicle Market Analysis  
*(End-to-End Data Analytics, Machine Learning & BI Project)*

## 📌 Project Overview
This project is an **end-to-end analytics and machine learning project** built on the Craigslist Vehicles dataset sourced from Kaggle.

The dataset initially consisted of **raw, noisy, and unstructured listings**.
The goal was to transform this data into a **clean, enriched, and analyzable dataset**, apply **machine learning techniques**, and deliver insights through a **Power BI dashboard**.

The project covers the full data lifecycle:
- Raw data acquisition (Kaggle)
- Data cleaning and feature engineering (Python – Google Colab)
- Machine learning modeling and evaluation
- BI modeling, DAX measures, and visualization (Power BI)

---

## 🎯 Business Problem
Online vehicle marketplaces face challenges such as:
- Inconsistent listing quality
- Large price dispersion for similar vehicles
- Difficulty evaluating vehicle condition objectively
- Limited transparency in pricing efficiency

Key questions addressed:
- What factors drive vehicle prices?
- How can vehicle listings be segmented meaningfully?
- Can vehicle value and condition be estimated using data-driven methods?

---

## 🧹 Data Acquisition & Cleaning (Kaggle → Google Colab)

### Raw Data Issues
The original dataset contained:
- Missing and invalid values
- Extreme outliers in price and mileage
- Free-text categorical noise
- Mixed and incorrect data types

### Cleaning Process (Python)
All preprocessing was performed in **Google Colab using Python (Pandas, NumPy)**.

Key steps:
- Removal of invalid and unrealistic listings
- Outlier filtering for price and mileage
- Standardization of brand, model, fuel type, and transmission fields
- Datatype correction for numerical and date fields
- Rule-based handling of missing values

---

## 🔧 Feature Engineering
Several analytical columns were created to enhance insight quality, including:
- `car_age`
- `price_per_mile`
- `miles_per_year`
- Price bands and mileage bands
- Condition score proxies
- Listing quality segments

These features enabled meaningful comparison across vehicles and supported both ML and BI analysis.

---

## 🤖 Machine Learning Analysis *(Primary Individual Contribution)*

Machine learning models were developed to **analyze vehicle pricing and condition dynamics**.

### Model Highlights
- Regression-based models (XGBoost)
- Evaluation using MAE and R² metrics
- Feature importance analysis

Key findings:
- Price, mileage (odometer), and vehicle year are the strongest predictors
- Model outputs were used for **explanatory and comparative purposes**, not black-box prediction

### Applied Outputs
- Estimated price for specific vehicle examples (e.g. Ford F-150)
- Condition score estimation and comparison with real listings

---

## 📊 Power BI Modeling & Visualization

### Data Modeling
The processed dataset was imported into **Power BI**, where:
- Additional transformations were applied
- Custom DAX measures were written
- Analytical KPIs were created

### DAX Measures
Custom measures enabled:
- Dynamic price and mileage analysis
- Condition score aggregation
- Listing quality segmentation
- Interactive filtering by year, state, vehicle type, and drivetrain

---

## 📈 Dashboard Structure

### General Market Analysis (Group Work)
- Listing volume over time
- Brand and model year distributions
- Engine, drivetrain, fuel, and vehicle type analysis
- Geographic distribution by state

---

### Advanced Pricing & Listing Quality Analysis *(My Responsibility)*
These final two pages represent my **primary individual contribution**.

Key elements:
- Price distribution by mileage and vehicle condition
- Condition score prediction results
- Listing quality segmentation (reliable, average, risky, problematic)
- Feature importance visualization
- ML-based estimated pricing comparisons

Purpose:
Translate machine learning outputs into **interpretable, business-facing insights**.

---

## 👤 My Contribution Summary
My responsibilities included:
- Cleaning and preprocessing raw Kaggle data using Python
- Feature engineering and analytical column creation
- Machine learning model development and evaluation
- Translating ML outputs into business-friendly insights
- Writing DAX measures and building advanced Power BI visuals
- Designing the final pricing and listing quality analysis pages

---

## 🛠️ Tools & Technologies
- **Python (Pandas, NumPy)** – Data cleaning & feature engineering
- **Google Colab** – Development environment
- **Machine Learning (XGBoost)** – Regression & feature importance
- **Power BI** – Data modeling, DAX, and visualization
- **Kaggle** – Raw data source

---
