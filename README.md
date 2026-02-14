# PCA on Wholesale Customers Dataset

## Overview

This project applies **Principal Component Analysis (PCA)** to the Wholesale Customers dataset to reduce dimensionality, visualize patterns, and better understand customer purchasing behavior across different product categories.

The dataset contains annual spending data of customers on various product groups such as Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen, along with categorical attributes like Channel and Region.

---

## Objective

* Reduce the number of features while preserving most of the data variance
* Visualize customer distribution in lower dimensions
* Identify patterns and relationships between spending categories
* Prepare transformed data for clustering or machine learning tasks

---

## Dataset Description

The dataset includes **440 customers** and **8 variables**:

**Categorical Variables**

* Channel – Customer type (Hotel/Restaurant/Cafe or Retail)
* Region – Customer region

**Spending Variables**

* Fresh
* Milk
* Grocery
* Frozen
* Detergents_Paper
* Delicatessen

---

## Data Preprocessing

Before applying PCA, the following steps were performed:

* Removed categorical variables (Channel and Region) from PCA input
* Standardized the numerical features to ensure equal scaling
* Prepared the dataset for dimensionality reduction

---

## Principal Component Analysis

PCA was applied to transform the original 6 spending variables into fewer components while retaining maximum variance.

### Explained Variance

* Principal Component 1 (PC1): 45.6% variance
* Principal Component 2 (PC2): 26.9% variance
* Total variance captured by first two components: **72.5%**

This indicates that most of the dataset information is preserved even after reducing dimensions from 6 to 2.

---

## Visualization

The transformed data was visualized using a 2D scatter plot:

* X-axis: Principal Component 1
* Y-axis: Principal Component 2
* Points colored by Channel

This helps observe clustering patterns and customer distribution in reduced dimensions.

---

## Results

* PCA successfully reduced dimensionality from 6 features to 2 principal components
* Over 70% of the original variance was retained
* The visualization revealed patterns in customer purchasing behavior
* The transformed dataset can be used for clustering or machine learning

---

## Applications

* Customer segmentation
* Data visualization
* Noise reduction
* Feature extraction
* Preprocessing for clustering (K-Means, Hierarchical)
* Preprocessing for machine learning models

---

## Conclusion

PCA is an effective dimensionality reduction technique that simplifies high-dimensional data while preserving important information. In this project, PCA reduced six spending variables into two principal components while retaining most of the variance, enabling easier visualization and analysis of customer behavior.

---

