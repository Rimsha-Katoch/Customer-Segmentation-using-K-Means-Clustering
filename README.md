# 🛍️ Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs customer segmentation using K-Means clustering based on customer demographics and spending behavior. The goal is to group similar customers together to help businesses make data-driven marketing decisions.

---

## 📊 Dataset
- Source: Mall Customer Dataset (Kaggle)
- Features used:
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## ⚙️ Steps Performed

1. Data Loading and Exploration
2. Data Cleaning (No missing values found)
3. Feature Selection
4. Data Normalization using StandardScaler
5. Applying K-Means Clustering
6. Finding optimal clusters using Elbow Method
7. Visualization of clusters

---

## 📈 Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

👉 Optimal clusters found: **4**

---

## 📉 Visualization

Clusters were visualized using:
- Annual Income vs Spending Score

Each color represents a different customer segment.

---

## 🔍 Key Insights

- Identified distinct customer segments based on income and spending
- High-income high-spending customers are premium targets
- High-income low-spending customers have potential for growth
- Low-income high-spending customers show impulsive behavior
- Average customers form the majority segment

---

## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository: