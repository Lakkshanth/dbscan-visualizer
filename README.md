# DBSCAN-Interactive-Visualizer
A Python app to visualize DBSCAN clustering

# 📊 DBSCAN Interactive Visualizer

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?style=for-the-badge&logo=streamlit)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-DBSCAN-orange?style=for-the-badge&logo=scikitlearn)
![License](https://img.shields.io/badge/License-Academic-lightgrey?style=for-the-badge)

---

# 📖 Overview

DBSCAN Interactive Visualizer is a web-based educational application that enables users to explore and understand the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm through interactive visualizations.

Developed using **Streamlit** and **scikit-learn**, the application allows users to upload datasets, tune clustering parameters, visualize each stage of the clustering process, analyze results, and export outputs directly from the browser without additional setup.

The project is intended for students, educators, and machine learning enthusiasts who want to gain practical insight into density-based clustering.

---

# 🌐 Live Demo

🚀 **Try the application here:**

https://dbscan-visualizer-ycfrxf7rz58uvrsgy3efhn.streamlit.app/

---

# ✨ Features

## 📂 Dataset Management

- Upload custom CSV datasets
- Automatic feature detection
- Built-in synthetic dataset generator
- Support for datasets with or without class labels

---

## ⚙ Interactive Parameter Tuning

- Adjustable **Epsilon (ε)**
- Adjustable **Minimum Points (MinPts)**
- Instant re-clustering
- Interactive controls with real-time updates

---

## 📈 Data Visualization

- Scatter Plot
- K-Distance Graph
- Density Visualization
- Core / Border / Noise Classification
- Cluster Formation Process
- Final Cluster Plot
- Class vs Cluster Comparison

---

## 📚 Step-by-Step Learning Mode

The application demonstrates the complete DBSCAN workflow in six stages.

| Step | Description |
|------|-------------|
| 1 | Raw Dataset Visualization |
| 2 | Density Neighborhood Visualization |
| 3 | Core, Border and Noise Point Identification |
| 4 | Cluster Expansion Process |
| 5 | Final Cluster Visualization |
| 6 | Ground Truth vs Predicted Clusters |

---

## 📊 Cluster Analytics

The application provides:

- Number of clusters
- Number of noise points
- Silhouette Score
- Cluster membership
- Point type statistics

---

## 📥 Export Options

Users can export:

- Clustered dataset (.csv)
- Visualization images (.png)

---

# 🏗 Project Structure

```
dbscan-visualizer/
│
├── app.py
├── requirements.txt
├── large.csv
└── README.md
```

---

# ⚙ Technologies Used

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Web Framework | Streamlit |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |

---

# 🔬 Algorithm Overview

DBSCAN is a density-based clustering algorithm that groups together points with high neighborhood density while identifying isolated observations as noise.

Unlike centroid-based algorithms, DBSCAN:

- Does not require specifying the number of clusters beforehand.
- Detects clusters of arbitrary shapes.
- Naturally identifies outliers.
- Performs well on datasets containing irregular cluster structures.

---

# ⚙ Parameters

## Epsilon (ε)

Defines the maximum distance between neighboring points.

A larger epsilon creates larger clusters, while a smaller epsilon produces more isolated points.

---

## Minimum Points (MinPts)

Defines the minimum number of neighboring points required for a point to become a Core Point.

Increasing MinPts generally produces denser clusters.

---

# 🎯 Point Classification

| Point Type | Description |
|------------|-------------|
| Core Point | Has at least MinPts neighbors within ε |
| Border Point | Connected to a Core Point but has fewer than MinPts neighbors |
| Noise Point | Does not belong to any cluster |

---

# 🚀 Installation

## Requirements

- Python 3.9 or above

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install streamlit pandas numpy matplotlib scikit-learn
```

---

## Launch the Application

```bash
streamlit run app.py
```

The application will automatically open in your web browser.

---

# 💻 Using the Application

1. Upload a CSV dataset or generate sample data.
2. Select the desired feature columns.
3. Adjust **Epsilon** and **MinPts**.
4. Analyze the K-Distance Graph.
5. Execute DBSCAN clustering.
6. Explore the six-step visualization.
7. Review cluster metrics.
8. Compare predicted clusters with true labels (if available).
9. Export the clustered dataset and plots.

---

# 📂 Input Dataset

Supported format:

- CSV (.csv)

Dataset requirements:

- Numeric feature columns
- Optional class label column

A sample dataset (`large.csv`) is included with the repository.

---

# 📊 Performance Metrics

The application displays:

- Cluster Count
- Noise Count
- Silhouette Score
- Cluster Distribution
- Point Classification Summary

---

# 📖 Educational Objectives

This project demonstrates practical implementation of:

- Density-Based Clustering
- DBSCAN Algorithm
- K-Nearest Neighbor Search
- Distance Metrics
- Cluster Evaluation
- Parameter Optimization
- Interactive Data Visualization
- Machine Learning Workflows

---

# 📷 Screenshots

## Home Page

> *(Insert application screenshot here)*

---

## Cluster Visualization

> *(Insert clustering output screenshot here)*

---

## Step-by-Step Visualization

> *(Insert walkthrough screenshot here)*

---

# 📚 References

- DBSCAN — Ester et al. (1996)
- Scikit-learn Documentation
- Streamlit Documentation
- DBSCAN Wikipedia

---

# 👨‍💻 Contributors

**Roohith R**

**Lakkshanth R**

---

## 🎓 Mentor

**Prof. Swaminathan Annadurai**

VIT Chennai

---

# 📄 License

This project is intended for academic and educational purposes only.

© 2026 Roohith R & Lakkshanth R
