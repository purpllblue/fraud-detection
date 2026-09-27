# Fraud Detection Using PCA and DBSCAN

## About the Project

This project analyzes transaction data to identify unusual patterns and potential fraudulent transactions. The analysis applies **Principal Component Analysis (PCA)** for dimensionality reduction and **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** for clustering and outlier detection.

The project includes data preprocessing, feature selection, dimensionality reduction, and clustering using **Python**.

## Key Results

* Selected **CustomerAge** and **AccountBalance** as the key features for clustering.
* Optimized DBSCAN parameters with **ε (eps) = 0.14** and **MinPts = 4**.
* Identified **2 clusters**, including an outlier/noise cluster.
* Achieved a **Silhouette Score of 0.7547**, indicating strong clustering quality.

## Tools & Methods

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **PCA**
* **DBSCAN**
* Data preprocessing & feature selection
* Clustering & outlier detection
