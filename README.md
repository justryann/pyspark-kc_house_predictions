# PySpark King County House Analysis & Marketing Segmentation

This repository contains advanced data science notebooks for real estate price modeling and customer segmentation using PySpark and scikit-learn. The main focus is on the King County House dataset, with implementations for Random Forest regression, K-Nearest Neighbors (KNN) regression, and marketing segmentation via KMeans clustering.

---

## Contents

-   PySpark notebook for data cleaning, feature engineering, and Random Forest regression on the King County House dataset.

-   PySpark and scikit-learn notebook for KNN regression, including feature engineering, hyperparameter tuning, and model evaluation.

-  Notebook for customer segmentation using KMeans clustering, silhouette analysis, and cluster profiling.

---

## Features

- **Data Cleaning & EDA:**  
  - Handling missing values and duplicates  
  - Outlier detection (IQR method)  
  - Correlation analysis and visualization

- **Feature Engineering:**  
  - Creation of domain-specific features (e.g., price per sqft, total rooms, ratios)

- **Modeling:**  
  - Random Forest regression with hyperparameter tuning (PySpark MLlib)
  - KNN regression (scikit-learn) with cross-validation and feature importance analysis

- **Segmentation:**  
  - KMeans clustering for marketing segmentation  
  - Elbow method and silhouette score for optimal cluster selection  
  - 2D/3D visualization and cluster profiling

- **Visualization:**  
  - Matplotlib and Seaborn for data and result visualization

---

## Getting Started

### Prerequisites

- Python 3.8+
- PySpark
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- findspark

### Installation

1. **Clone the repository or download the notebooks.**

2. **Install dependencies:**
   ```sh
   pip install pyspark pandas numpy matplotlib seaborn scikit-learn findspark