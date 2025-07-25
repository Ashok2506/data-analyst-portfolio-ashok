# Rainfall Trends and Anomaly Detection in India (1901–2015)

## 📊 Project Overview

This project analyzes Indian rainfall data from 1901 to 2015 to identify long-term patterns, seasonal insights, and extreme climate events like droughts and excess rainfall. Using Python and machine learning (Isolation Forest), the goal is to detect key trends and anomalies that impact agriculture, water planning, and climate research.

---

## 🧠 Problem Statement

India is heavily reliant on the monsoon for agriculture and water supply. However, fluctuations in rainfall can lead to severe consequences like droughts or floods. This project addresses:

- How has rainfall changed over the last 115 years?
- Which months and seasons contribute most to annual totals?
- When did droughts or excess rainfall years occur?
- Can machine learning help detect these anomalies?

---

## 🔧 Technologies Used

- **Python**
- **Pandas, NumPy** – Data analysis  
- **Matplotlib, Seaborn** – Visualization  
- **Scikit-learn** – Machine Learning (Isolation Forest)

---

## 📁 Dataset

- Source: Kaggle / IMD-based rainfall dataset  
- Period: **1901 – 2020**
- Key Columns:
  - `YEAR`, `ANNUAL`, `Jan` to `Dec`
  - `JUN-SEP`, `OCT-DEC`, `MAR-MAY` (Seasonal)

---

## 📈 Exploratory Data Analysis

### ✅ Annual Rainfall Trends
- **Post-1960**: Clear downward trend in rainfall  
- Used **rolling mean (10 years)** to visualize smooth trends  
- Mean Annual Rainfall: ~**1182 mm**

### ✅ Monthly Analysis
- **July** receives the highest rainfall on average  
- Followed by **August** and **September**  
- **January & February** show very low and uncorrelated values  

### ✅ Seasonal Observations
- **JUN-SEP (Monsoon)** dominates annual totals  
- **OCT-DEC** post-monsoon is lower but important for **South India**  
- **MAR-MAY** (Pre-monsoon) is rising gradually

---

## 🚨 Anomaly Detection

### 📐 Statistical Method
- Drought: Rainfall < (Mean - 1.5 * Std Dev)
- Excess: Rainfall > (Mean + 1.5 * Std Dev)
- Results:
  - **5 Drought Years** (e.g., 2002, 2009)
  - **7 Excess Years**

### 🤖 Machine Learning (Isolation Forest)
- Detected **12 anomaly years**
- ML results matched statistics closely  
- One difference: ML picked **1904** instead of **1988** (slightly lower)

---

## 📊 Visualizations 

- Rolling Mean of Annual Rainfall
- Monthly Rainfall Averages (Bar Graph)
- Seasonal Contributions to Annual Rainfall
- Drought & Excess Years (Scatter)
- ML Anomaly Detection Output

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone (https://github.com/Ashok2506/data-analyst-portfolio-ashok/portfolio_projects/Rainfall_trend_analysis_india)

✅ Future Scope
State-wise rainfall breakdown

El Niño / La Niña effect on rainfall

Correlation with agricultural yield or GDP

Forecasting future rainfall with time series models (ARIMA, LSTM)

✍️ Author
Ashok Kumar R
Aspiring Data Analyst & Machine Learning Engineer

[LinkedIn] (www.linkedin.com/in/ashokkumar-r-) | [GitHub] (https://github.com/Ashok2506)


