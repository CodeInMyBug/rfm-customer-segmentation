# 🔍 RFM Customer Segmentation

This project clusters customers based on Recency-Frequency-Monetary (RFM) metrics and telco-style behavioral data using unsupervised learning.

---

## 🧠 Project Summary
- 📊 **Problem**: Unsupervised learning – identify customer segments
- 🏗️ **Tech Stack**: Python, Pandas, scikit-learn, KMeans, PCA
- 🎯 **Objective**: Discover meaningful customer groups to guide targeting, re-engagement, or upselling

---

## 📁 Files

| File | Description |
|------|-------------|
| `01_generate_segmentation_data.ipynb` | Generates a synthetic dataset of customers with RFM and usage features |
| `03_segmentation_rfm.ipynb` | Performs clustering and PCA visualization |
| `data/segmentation_customers.csv` | The generated dataset |

---

## 📊 Features Used
- `recency_days`: Days since last transaction
- `frequency`: Number of past transactions
- `monetary_value`: Total spend
- `avg_call_duration_min`: Average call time
- `num_support_tickets`: Service interaction
- `data_usage_gb`: Mobile/internet usage
- `app_opens_weekly`: Engagement via app

---

## 🎯 Clustering Approach
- Standardized features
- KMeans with `k=4`
- PCA for 2D visualization

---

## 📈 Result
- Segments uncovered include low-engagers, loyalists, potential churners, and high-value users
- Visualized with PCA
- Summarized with cluster-wise averages for business insights

---

## 🔮 Use Cases
- Targeted promotions per segment
- Personalize onboarding or retention efforts
- Discover high-risk or high-potential groups

---
