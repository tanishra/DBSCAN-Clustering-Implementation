# 🌀 DBSCAN Clustering on make_moons Dataset

This project demonstrates the application of **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** on the classic `make_moons` dataset using **scikit-learn**. It highlights how DBSCAN effectively clusters non-convex data structures and separates noise.

---

## 📌 Table of Contents

- [About DBSCAN](#about-dbscan)
- [Dataset Description](#dataset-description)
- [Results](#results)
- [Insights & Analysis](#insights--analysis)

---

## 📖 About DBSCAN

**DBSCAN** is a density-based clustering algorithm that groups together points that are closely packed, while marking outliers (points in low-density regions) as noise. Unlike KMeans, it does not require the number of clusters to be specified in advance and can find arbitrarily shaped clusters.

**Key Parameters:**
- `eps`: The maximum distance between two samples for them to be considered in the same neighborhood.
- `min_samples`: The number of samples in a neighborhood to form a core point.

---

## 🧪 Dataset Description

The `make_moons` dataset is a synthetic, non-linearly separable dataset commonly used to test clustering and classification algorithms.

- **Samples:** 250
- **Noise:** 0.05 (added to make clustering harder and realistic)
- **Shape:** Two interleaving half circles

---

## 📊 Results

DBSCAN successfully identified the two interleaving half-moon shapes as separate clusters without requiring a predefined number of clusters.

---

## 💡 Insights & Analysis

- DBSCAN works particularly well on non-linear and non-convex shapes.
- It can detect noise (outliers) in the data.
- Compared to KMeans, it avoids the assumption of spherical clusters.
- Selecting the right eps and min_samples is critical and often done using a k-distance plot.

---

## 🤝 Contributions
Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

