# Car Market Trends Analysis using Car Dekho Dataset

**VOIS Internship Minor Project (Supported by AICTE)**  
**Domain:** Data Analytics & Visualization  
**Environment:** Google Colab / Python  

---

## 📌 Project Overview
This project presents a comprehensive Exploratory Data Analysis (EDA) of the CarDekho used-vehicle dataset. The primary objective is to analyze historical resale patterns, evaluate price depreciation across distinct automotive segments, examine key vehicle specification drivers, and uncover market supply trends using statistical and data visualization techniques.

---

## 🛠️ Technology Stack & Analytical Tools

* **Programming Language:** Python
* **Development Environment:** Google Colab
* **Data Processing & Manipulation:** Pandas, NumPy
* **Data Visualization Libraries:** Matplotlib, Seaborn

---

## 📊 Analytical Techniques & Visualizations Implemented

### Analytical Methods
* Data Cleaning & Type Formatting
* Exploratory Data Analysis (EDA) & Descriptive Statistics
* Feature Engineering (e.g., Depreciation, Percentage Depreciation, Vehicle Age)
* Sub-segment Extraction (e.g., Car vs. Two-Wheeler Isolation)
* Correlation & Value Loss Modeling

### Visualizations & Chart Types
* **Count Plots (Seaborn):** Distribution and inventory density across vehicle models and categories.
* **Vertical Bar Charts (Matplotlib):** Absolute monetary depreciation profiles, owner distributions, and fuel type splits.
* **Horizontal Bar Plots (Seaborn):** Percentage cost depreciation retention by brand (e.g., Royal Enfield vs. Toyota) and top 10 two-wheeler sales volumes.
* **Pie Charts (Matplotlib):** Proportional market splits for Seller Types (Dealer vs. Individual), Transmission Types (Manual vs. Automatic), and Vehicle Categories (Cars vs. Two-Wheelers).
* **Correlation Heatmap (Seaborn):** Multi-variable linear relationship mapping to identify primary drivers of resale pricing ($r = 0.88$).
* **Scatter Plots (Matplotlib/Seaborn):** Continuous feature interaction analyses tracking price decay against Vehicle Age, Kilometers Driven, and Present Price.

---

## 🎯 Key Insights & Findings

* **Primary Pricing Driver:** Original ex-showroom price (`Present_Price`) serves as the strongest determinant of resale value ($r = 0.88$).
* **Depreciation Patterns:** High-ticket luxury vehicles suffer the highest absolute monetary depreciation, whereas two-wheelers retain a higher percentage of initial value over time.
* **Inventory Skew:** Market inventory is heavily dominated by single-owner (**96%**), petrol-powered (**79%**), manual-transmission (**87%**) vehicles sold primarily via dealer networks (**65%**).
* **Usage & Age Impact:** Resale prices decay most sharply within the first 4 years, with total mileage exceeding **100,000 km** acting as a strong ceiling on valuation regardless of model year.

---

## 📁 Repository Structure

```text
├── Data/
│   └── car_dekho_data.csv        # CarDekho used vehicle dataset
├── Notebooks/
│   └── Car_Market_Trends.ipynb   # Complete Google Colab EDA Notebook
|
└── README.md                     # Project documentation
