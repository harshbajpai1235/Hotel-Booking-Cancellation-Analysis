# Hotel Booking Cancellation Analysis

This project explores patterns in hotel booking cancellations using real-world data from City and Resort hotels between 2015 and 2017. The goal is to uncover the key factors influencing reservation cancellations and provide actionable strategies to reduce them.

## 📌 Business Problem

Both City and Resort Hotels have experienced high cancellation rates, leading to revenue loss and underutilized rooms. This project aims to:
- Identify major drivers of cancellations
- Compare booking behavior across hotel types
- Support smarter pricing and promotional decisions

## 📊 Dataset Overview

- **Rows**: 119,390 bookings
- **Columns**: 36 features (hotel type, lead time, booking channel, ADR, guest details, etc.)
- **Period**: 2015–2017

## 🧹 Data Preprocessing

- Removed irrelevant personal columns (e.g., name, email, credit card)
- Handled missing values and dropped sparse columns (`agent`, `company`)
- Converted dates to datetime format
- Filtered out extreme outliers (e.g., ADR > 5000)

## 🔍 Exploratory Analysis

- ~37% of total bookings were canceled
- City hotels had higher cancellation rates (~42%) compared to resort hotels (~28%)
- January had the highest cancellation rate
- ADR (Average Daily Rate) was significantly higher for canceled bookings
- Most cancellations came from guests booking through Online Travel Agencies (OTA)
- Portugal had the highest number of cancellations by country

## 📈 Key Visualizations

- Count plots of cancellations by hotel type and month
- Line graphs comparing ADR trends for canceled vs. completed bookings
- Pie charts of top countries with cancellations
- Market segment distribution analysis

## 💡 Insights & Recommendations

- **Pricing Strategy**: Consider reducing prices during peak cancellation periods (e.g., January)
- **OTA Dependence**: Reduce reliance on online travel agencies by incentivizing direct bookings
- **Targeted Promotions**: Offer discounts for repeat guests or during weekends in City Hotels
- **Country-Specific Actions**: Improve guest experience and incentives for regions with high cancellation rates (e.g., Portugal)

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

**Author**: Harsh Bajpai  

