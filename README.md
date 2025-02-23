# HCMST Data Analysis

## Overview
This project analyzes data from the HCMST (How Couples Meet and Stay Together) survey. It applies data preprocessing, Principal Component Analysis (PCA), and K-Means clustering to understand relationship patterns based on various demographic and behavioral factors.

## Features
- Data preprocessing (handling missing values, encoding categorical variables, standardization)
- Principal Component Analysis (PCA) for dimensionality reduction
- K-Means clustering to identify relationship patterns
- Visualization of clusters, relationship quality, and demographic factors

## Dependencies
To run this notebook, you need the following Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Use
1. Load the dataset (`HCMST_ver_3.04.dta`).
2. Run the notebook step by step to preprocess data and perform clustering.
3. Check the visualizations to understand patterns in the data.

## Key Visualizations
- **Explained Variance Plot**: Determines the optimal number of PCA components.
- **Silhouette Score Plot**: Helps select the best number of clusters.
- **Cluster Scatter Plot**: Visualizes data after PCA clustering.
- **Boxplots and Bar Charts**: Show relationship duration, quality, and other demographic insights.

## Conclusion
This analysis helps understand factors influencing relationships and their clustering based on demographic data. Future improvements could involve trying different clustering algorithms or feature selection techniques.

