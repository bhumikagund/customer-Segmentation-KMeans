# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project aims to group customers of a retail store based on their purchase history and demographic data. By using **Unsupervised Machine Learning**, we identify distinct customer segments to help businesses tailor their marketing strategies.

## 🛠️ Technologies Used
* **Python** (Core programming)
* **Pandas** (Data manipulation)
* **Matplotlib & Seaborn** (Data visualization)
* **Scikit-Learn** (K-Means Clustering algorithm)

## 📊 Methodology
1. **Data Collection:** Sourced Mall Customer data via GitHub Raw URL.
2. **Feature Selection:** Analyzed 'Annual Income' and 'Spending Score'.
3. **Elbow Method:** Used the Within-Cluster Sum of Squares (WCSS) to determine that **K=5** is the optimal number of clusters.
4. **Clustering:** Applied K-Means to segment the data into 5 groups.

## 📈 Results
The model successfully identified 5 types of customers:
* **Target:** High Income, High Spending.
* **Careful:** High Income, Low Spending.
* **Sensible:** Low Income, Low Spending.
* **Careless:** Low Income, High Spending.
* **Standard:** Average Income, Average Spending.
