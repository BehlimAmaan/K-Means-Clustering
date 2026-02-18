# 📌 K-Means Clustering Project

## 📖 Project Overview

This project implements **K-Means Clustering**, an unsupervised machine learning algorithm used to group similar data points into clusters.

The objective of this project is to:

Understand how unsupervised learning works
Implement K-Means from scratch and using Scikit-learn
Visualize clusters using Matplotlib
Evaluate clustering performance using inertia and silhouette score

---

## 🧠 What is K-Means?

K-Means is an unsupervised learning algorithm that divides data into **K clusters** based on similarity.

It works in the following way:

First, choose the number of clusters (K).
Randomly initialize K centroids.
Assign each data point to the nearest centroid using Euclidean distance.
Recalculate the centroid as the mean of assigned points.
Repeat until centroids stop changing.

The goal is to minimize the **Within-Cluster Sum of Squares (WCSS)**.

---

## 📂 Project Structure

```
KMeans-Clustering/
│
├── src/
│   └── kmeans.ipynb
│   ├── pca.ipynb
├── requirements.txt
└── README.md
```

---

## 🛠️ Technologies Used

Python
NumPy
Pandas
Matplotlib
Scikit-learn

---

## 📊 Evaluation Metrics

Inertia (WCSS)
Elbow Method
Silhouette Score

---

## ▶️ How to Run

1. Clone the repository
2. Install dependencies
   pip install -r requirements.txt
3. Run the notebook or Python file



