# 🛍️ Mall Visitor Segmentation using KMeans Clustering

This project applies unsupervised machine learning to segment mall visitors based on their shopping behavior. By identifying patterns in visitor activity, mall management and store owners can better prioritize real customers, improve marketing strategies, and enhance overall customer experience.

---

## 📁 Files Included

- `clustering_project.ipynb` → Main notebook with full end-to-end clustering logic, preprocessing, visualization, and cluster labeling.
- `mall_visitors.csv` → Synthetic dataset of 4000 mall visitors with features like time spent, shops visited, and purchase history.
- `requirements.txt` → Required Python packages to run the notebook.

---

## 🎯 Project Objective

To cluster mall visitors using **KMeans** and interpret their behavior using PCA visualization. The idea is inspired by the real-world challenge of distinguishing time-passers from potential buyers using mall camera data and visit history.

---

## 🧠 Features Used

The dataset includes the following key features:
- `VisitorID`
- `Total_Visits`
- `Total_Purchases`
- `Avg_Time_Spent`
- `Avg_Amount_Spent`
- `Time_Since_Last_Visit`
- `Unique_Shops_Visited`
- `Purchase_to_Visit_Ratio`
- `Last_Visit_Purchase`

---

## 🔍 Approach

1. **Data Preprocessing**
   - Missing value imputation
   - Standard scaling
   - One-hot encoding of categorical data

2. **KMeans Clustering**
   - Elbow Method to determine optimal `k`
   - Final clustering with `k=5`

3. **Dimensionality Reduction**
   - PCA used to visualize clusters in 2D

4. **Cluster Interpretation**
   - Clusters labeled based on behavioral patterns:
     - Loyal Customers
     - Frequent Buyers
     - Quick Visitors
     - Average Explorers
     - Window Shoppers

---

## 📊 Final Output

- A well-labeled dataset with customer segments (`Cluster_Label`)
- 2D scatter plot showing clear cluster separation
- Insights into customer types for personalized targeting

---

## 📦 Setup

Install the required packages with:

```bash
pip install -r requirements.txt
