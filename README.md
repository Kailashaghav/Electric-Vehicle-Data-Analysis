# 🚗 SHOW EV – Electric Vehicle Data Analysis Dashboard

An interactive Electric Vehicle (EV) analytics dashboard built to analyze EV adoption trends, vehicle distribution, manufacturer performance, and CAFV eligibility across the United States.

## 📌 Project Overview

SHOW EV provides comprehensive insights into Electric Vehicle population data through interactive visualizations and KPI tracking.

The dashboard helps stakeholders understand:

- Growth of EV adoption over time
- State-wise EV distribution
- Leading EV manufacturers
- Most popular EV models
- Battery Electric Vehicle (BEV) vs Plug-in Hybrid Electric Vehicle (PHEV) market share
- CAFV Eligibility statistics

---

## 📊 Key Performance Indicators (KPIs)

### Total Vehicles
Displays total electric vehicles available in the dataset.

### Average Electric Range
Shows the average electric driving range across all EVs.

### Total BEV Vehicles
Total number of Battery Electric Vehicles and their percentage contribution.

### Total PHEV Vehicles
Total number of Plug-in Hybrid Electric Vehicles and their percentage contribution.

---

## 📈 Dashboard Visualizations

### 1. Total Vehicles by Model Year
- Area/Line Chart
- Shows EV growth trends from 2010 onwards.

### 2. Total Vehicles by State
- Map Visualization
- Displays geographical distribution of EVs across the United States.

### 3. Top 10 Vehicles by Make
- Horizontal Bar Chart
- Highlights leading EV manufacturers.

### 4. CAFV Eligibility Distribution
- Donut Chart
- Shows CAFV eligible, non-eligible and unknown vehicles.

### 5. Total Vehicles by Model
- Treemap/Table
- Displays most popular EV models.

---

## 📂 Project Structure
SHOW-EV/
│
├── Dataset/
│   └── Electric_Vehicle_Population_Data.csv
│
├── Dashboard/
│   ├── EV DATA Analysis 1.twbx
│   └── Dashboard Screenshot.png
│
├── Assets/
│   ├── EV Logo.png
│   ├── Header Banner.png
│   └── Background.jpg
│
├── Presentation/
│   └── Electric Vehicle Presentation.pptx
│
└── README.md
---

## 🛠 Tools Used

- Tableau
- Microsoft PowerPoint
- CSV Dataset
- Data Visualization Techniques

---

## 📊 Dashboard Insights

### Market Overview

- Total Vehicles: 150,413
- Average Electric Range: 67.83 Miles
- Total BEV Vehicles: 116,745
- Total PHEV Vehicles: 33,668

### Leading Manufacturer

Tesla dominates the EV market with the highest number of registered vehicles.

### Most Popular Models

- Tesla Model Y
- Tesla Model 3
- Nissan Leaf
- Tesla Model S

### Growth Trend

A significant increase in EV adoption is observed after 2020, indicating accelerated market growth.

---

## 🎯 Business Objectives

- Analyze EV market trends
- Understand regional adoption patterns
- Identify leading manufacturers and models
- Evaluate CAFV eligibility impact
- Support strategic decision-making through data-driven insights

---

## 🚀 Future Enhancements

- Real-time EV registration updates
- Charging station analysis
- Predictive EV adoption forecasting
- Cost and ownership analysis
- Interactive web dashboard deployment

---

## 📸 Dashboard Preview

<img width="3198" height="1798" alt="Dashboard 1 (1)" src="https://github.com/user-attachments/assets/b9e966f5-2f5e-4bd8-9a48-5ae02a2db83f" />

# Dataset

This project uses the Electric Vehicle Population Data dataset from Kaggle.

Dataset Source:
https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data

### Load Dataset Using Python

# Install dependencies
# pip install kagglehub[pandas-datasets]

import kagglehub
from kagglehub import KaggleDatasetAdapter

file_path = ""

df = kagglehub.load_dataset(
    KaggleDatasetAdapter.PANDAS,
    "ratikkakkar/electric-vehicle-population-data",
    file_path
)

print(df.head())

## Features

- EV adoption trend analysis
- BEV vs PHEV comparison
- State-wise EV distribution
- Manufacturer performance analysis
- CAFV eligibility insights
- Interactive Tableau dashboard

## Project Files

- Electric_Vehicle_Population_Data.csv – Dataset
- EV DATA Analysis 1.twbx – Tableau Workbook
- Electric Vehicle Presentation.pptx – Project Presentation
- Dashboard screenshots and branding assets

## Tech Stack

- Tableau
- Python
- Pandas
- KaggleHub
- CSV Data Processing

## Dashboard KPIs

- Total Vehicles
- Average Electric Range
- Total BEV Vehicles
- Total PHEV Vehicles
- CAFV Eligibility Analysis

## Author

Kailash Mahadev Aghav
---



Data Science Student | Data Analyst | Tableau Developer

---

## 📄 License

This project is available under the MIT License.
