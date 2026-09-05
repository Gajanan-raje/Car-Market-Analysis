# Car-Market-Analysis
VOIS AICTE DIY Project - Car Market Analysis

This project was completed as part of the **VOIS AICTE Virtual Internship Program**, under the DIY (Do It Yourself) Project track.

VOIS AICTE DIY Project - Car Market Analysis
This project was completed as part of the **VOIS for Tech Program on Data Analytics**, a CSR initiative by VOIS and Vodafone Idea Foundation — a 4-week Virtual Internship on Data Analytics.

Car Market Analysis
DIY Project | Batch 1, 2026-2027

## 👤 Submitted By
**Name:** Gajanan Harinarayan Raje
**College:** MGM's College of Computer Science & IT, Nanded
**Course:** BCA (5th Semester), SRTMU University

## 📌 Project Overview
**Dataset Size:** 299 records (after removing 2 duplicates) × 9 columns (Car Name, Year, Selling Price, Present Price, Kms Driven, Fuel Type, Seller Type, Transmission, Owner)
This project analyzes used-car market data from Car Dekho, covering vehicles with varying prices, fuel types, transmission types, and usage levels. The goal is to identify the key factors that influence a used car's selling price and provide data-driven insights for buyers, sellers, and dealers.

## 📂 Repository Structure
├── dataset/
│   └── car_data.csv
├── notebook/
│   └── Car_Market_Analysis_Gajanan.ipynb
├── graphs/
│   ├── 01_selling_price_distribution.png
│   ├── 02_fuel_type_count.png
│   ├── 03_transmission_count.png
│   ├── 04_price_by_fuel_type.png
│   ├── 05_price_by_transmission.png
│   ├── 06_age_vs_price.png
│   ├── 07_kms_vs_price.png
│   ├── 08_price_by_seller_type.png
│   └── 09_correlation_heatmap.png
├── presentation/
│   └── Car_Market_Analysis_Gajanan.pptx
└── README.md

## 🎯 Objective
- Explore and clean the used-car dataset
- Identify which factors most affect a car's selling price
- Compare pricing across fuel type, transmission, seller type, and ownership
- Provide data-driven insights for buying, selling, and pricing decisions

## 🛠️ Tools & Technologies
- **Language:** Python
- **Platform:** Google Colab (Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 🔍 Methodology
1. **Data Cleaning** — Removed duplicate rows; checked for missing values
2. **Feature Engineering** — Created Car_Age column from manufacturing year
3. **Exploratory Data Analysis (EDA)** — Explored dataset structure and summary statistics
4. **Univariate Analysis** — Distribution of selling price, fuel type and transmission counts
5. **Bivariate Analysis** — Compared price across fuel type, transmission, seller type, and ownership
6. **Correlation Analysis** — Identified which numerical factors most affect selling price

## 📊 Key Findings
| Category | Average Selling Price |
|---|---|
| Diesel | ₹10.10 Lakhs |
| Petrol | ₹3.26 Lakhs |
| Automatic | ₹9.07 Lakhs |
| Manual | ₹3.92 Lakhs |

- Diesel cars sell at nearly **3x the price** of Petrol cars on average
- Automatic transmission cars have significantly higher resale value than Manual
- **Present Price** shows the strongest correlation with Selling Price (0.88)
- Car Age has a moderate negative effect on Selling Price (-0.23)
- Kilometers Driven shows very weak correlation with Selling Price (0.03)

## 💡 Recommendations
- Sellers with Diesel/Automatic cars can price more competitively due to higher demand
- Present Price (original showroom price) is the most reliable indicator for estimating resale value
- Kilometers driven alone should not heavily influence pricing decisions
- Buyers should factor in fuel type and transmission when comparing similar-aged cars

- 
