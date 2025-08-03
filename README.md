# 💳 Credit Card Customer Segmentation using Clustering

This project was developed by **[Your Full Name]** as part of a personal initiative to understand and apply **unsupervised learning** techniques for solving real-world business problems.

---

## 🧠 What is this project about?

Banks and credit card companies often struggle to understand the different types of customers they serve. Using clustering algorithms, this project segments credit card users into meaningful groups based on their behavior (spending, payments, cash advances, etc.).

---

## 📊 What was done?

- 📦 **Dataset**: Cleaned and preprocessed data of ~9,000 credit card customers.
- 🔧 **Feature Engineering**: Derived useful behavioral features like revolving balance percentage and installment ratio.
- 📉 **Dimensionality Reduction**: Used **PCA** to simplify and visualize the customer data.
- 🤖 **Clustering**: Applied and compared:
  - K-Means
  - K-Medoids
  - Agglomerative Clustering
- 🧪 **Evaluation**: Used silhouette score and visual plots to evaluate cluster quality.
- 🏆 **Best Result**: 4 clusters using **K-Medoids with Cosine distance** gave the most interpretable and stable grouping.

---

## 🔍 Clusters Identified

1. **Balance Spenders** – Heavy one-time spenders.
2. **Money Hoarders** – Low spend, high balance holders.
3. **Potential Whales** – Moderate spenders with growth potential.
4. **Credit Lovers** – Prefer installment-based spending.

---

## 🚀 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook

---
