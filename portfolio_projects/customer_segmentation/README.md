# 🧠 Customer Segmentation using K-Means Clustering

## 📌 Objective

This project aims to segment customers into distinct groups based on their **Annual Income** and **Spending Score**, helping businesses understand customer behavior and design targeted marketing strategies.

---

## 📊 Dataset Overview

- **Source:** Mall Customer Dataset
- **Rows:** 200 customers
- **Features:**
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Exploration
- Loaded the dataset and verified structure, types, and missing values.
- Summary statistics for numerical features.
- Gender distribution and value counts.

### 2. Data Visualization
- Plotted histograms of Age, Income, and Spending Score
- Box plot of Spending Score by Gender
- Scatter plot of Income vs Spending Score revealed natural grouping tendencies

### 3. Clustering with K-Means
- Selected two key features: `Annual Income` and `Spending Score`
- Applied the **Elbow Method** to find optimal clusters (`k = 5`)
- Used **KMeans** from `sklearn` to assign cluster labels
- Visualized the clusters and centroids

---

## 📈 Results & Business Insights

| Cluster | Profile | Business Insight |
|--------|---------|------------------|
| 0 | High Income, Low Spending | Conservative buyers — nurture with premium offers |
| 1 | Low Income, Low Spending | Least profitable — minimal investment needed |
| 2 | High Income, High Spending | Best customers — prioritize with loyalty programs |
| 3 | Average Income & Spending | Stable group — potential to upsell |
| 4 | Low Income, High Spending | Risky segment — watch for overspending behavior |

---

## 💡 Key Learnings

- Learned the **concept and code** of clustering for the first time
- Understood how to use the **elbow method** and `fit_predict()` of KMeans
- Discovered how **real businesses use segmentation** to increase revenue and reduce risk
- Experienced the complete **project cycle**: EDA → ML → Interpretation → Documentation

---

## 📂 Project Structure
customer_segmentation/
├── customer_segmentation.ipynb # Notebook with full code and visuals
├── data.csv # Dataset used (Mall Customers)
└── README.md # This file


---

## 🚀 Future Enhancements

- Add Power BI dashboard to visualize segments interactively
- Try more features like Age or Gender in clustering
- Apply other clustering methods (DBSCAN, Hierarchical)

---

> 🧑‍💻 Made with curiosity and consistency by Ashok Kumar  



