# DATA-VISUALIZATION
Exploratory Data Analysis and visualization of housing dataset using Python (Pandas, Matplotlib, Seaborn) to analyze pricing trends and feature impact.
# 🏠 Housing Data Exploration and Visualization

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and visualization on a housing dataset (`Housing.csv`). The objective is to analyze housing price patterns and understand the impact of different features such as area, air conditioning, parking availability, and preferred area on house prices.

The project was implemented using Python in Google Colab.

---

## 🎯 Objectives

1. Analyze number of houses in different price ranges.
2. Compare average house prices for AC vs Non-AC houses.
3. Study relationship between parking availability and house price.
4. Calculate price gap between:
   - Houses < 5000 sqft & No Preferred Area
   - Houses > 5000 sqft & Preferred Area

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Tasks Performed

### ✅ Task 1: Price Range Analysis
- Categorized houses into price bins:
  - 0–25 lakhs
  - 26–50 lakhs
  - 51–75 lakhs
  - 76–100 lakhs
  - >100 lakhs
- Visualized using a Line Chart.

### ✅ Task 2: AC vs Non-AC Comparison
- Calculated average house prices.
- Visualized using Bar Chart.

### ✅ Task 3: Parking vs House Price
- Analyzed relationship between parking spaces and price.
- Visualized using Scatter Plot.

### ✅ Task 4: Price Gap Analysis
- Compared:
  - Small houses (<5000 sqft, non-preferred area)
  - Large houses (>5000 sqft, preferred area)
- Calculated price gap.
- Visualized using Bar Chart.

---

## 📈 Key Insights

- Houses in preferred areas tend to have significantly higher prices.
- AC availability increases average house price.
- More parking spaces generally correlate with higher house prices.
- Larger houses in preferred areas show a strong price premium.

---

## 📂 Project Structure
****Housing-Data-EDA/
│
├── Housing.csv
├── README.mdHousing_Data_Exploration
└── README.md
