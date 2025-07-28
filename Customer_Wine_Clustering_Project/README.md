#  Clustering Analysis on Synthetic, Mall Customer & Wine Quality Datasets

**Author**: Pradeep Anand Mohanasundaram  
**Purpose**: Personal learning project to explore clustering techniques in machine learning  


##  Overview

This project was developed as a personal initiative to master unsupervised machine learning techniques such as **K-Means** and **Hierarchical Clustering**. It applies these algorithms to three datasets:

1. A **synthetic dataset** generated with `make_blobs()`
2. The **Mall Customer dataset**
3. The **Wine Quality dataset**

The objective is to identify natural groupings and patterns in each dataset through effective preprocessing, clustering, and visualization.

---

## Project Structure

```
Clustering-Project/
│
├── Mall_Customers.csv
├── winequality-red.csv
├── Project.ipynb                # Jupyter Notebook with full analysis
├── README.md                    # Project documentation
```

---

## 📦 Datasets Used

### 1. Synthetic Dataset
- Created using `make_blobs(n_samples=300, centers=4, cluster_std=0.8)`
- Features: `Feature_1`, `Feature_2`
- Purpose: Demonstrate basic clustering

### 2. Mall Customers Dataset
- Source: Kaggle
- Features: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1-100)`
- Purpose: Segment customers by income and spending behavior

### 3. Wine Quality Dataset
- Source: UCI Machine Learning Repository
- Features: 11 chemical attributes + `quality`
- Purpose: Identify wine groups with similar chemical characteristics

---

## Methods & Techniques

- **Data Preprocessing**: Cleaning, selection, normalization
- **Clustering**: K-Means (with Elbow & Silhouette), Hierarchical Clustering (Dendrogram)
- **Dimensionality Reduction**: PCA for 2D visualization
- **Visualization**: Seaborn, Matplotlib, Plotly

---

## Key Insights

- **Synthetic Data**: Clusters recovered effectively
- **Mall Data**: Clear customer groups with distinct behaviors
- **Wine Data**: Quality groups correspond to chemical patterns

---

## Learning Outcomes

- Hands-on experience with unsupervised learning
- Ability to evaluate clustering quality
- Proficiency in visualizing high-dimensional data
- Real-world application of PCA, normalization, and clustering metrics

---

