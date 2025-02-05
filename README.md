# Unsupervised Learning: Dimension Reduction & Clustering 🔍

## Project Overview
This project applies **unsupervised machine learning techniques** to analyze and cluster data from various datasets. The analysis focuses on **Principal Component Analysis (PCA)** for dimensionality reduction and **clustering methods** such as **K-Means and Hierarchical Clustering** to uncover latent structures in data. The study evaluates clustering performance using silhouette scores and visualizes the data in lower-dimensional representations.

## Problem Statement
High-dimensional datasets often contain redundant or correlated features that can obscure meaningful patterns. This project aims to:
- Reduce dimensionality while preserving critical information
- Identify inherent groupings in the data using clustering methods
- Assess the effectiveness of unsupervised learning techniques for structure discovery

## 🔑 Key Objectives
- Apply **Principal Component Analysis (PCA)** to extract dominant features
- Implement **K-Means and Hierarchical Clustering** for data segmentation
- Standardize data to enhance clustering performance
- Evaluate clustering effectiveness using **silhouette scores**
- Visualize data transformations in lower dimensions

## 📊 Data Analyzed
- **Delta Aircraft Dataset (`delta.csv`)**: Features of aircraft, used for PCA and clustering analysis
- **Iris Dataset (`Iris.csv`)**: Classic dataset for clustering validation
- **NBA Statistics (`nba_stats.csv`)**: Player statistics used in hierarchical clustering

## 📊 Data Analysis Components

### 1. Data Preprocessing
- Load and clean datasets (`delta.csv`, `Iris.csv`, `nba_stats.csv`)
- Handle missing values and normalize numerical features using **StandardScaler**

### 2. Dimensionality Reduction
- Apply **PCA** to identify the most informative features
- Determine the optimal number of components via **explained variance analysis**
- Visualize **principal components** in 2D and 3D spaces

### 3. Clustering Analysis
- Implement **K-Means Clustering** to segment data into clusters
- Perform **Hierarchical Clustering** with dendrogram visualization
- Use **Silhouette Scores** to evaluate clustering performance

## 🛠️ Technical Stack
- **Python**: Primary programming language
- **Libraries**:
  - Pandas, NumPy: Data manipulation and transformation
  - Scikit-learn: PCA, clustering models, silhouette analysis
  - Matplotlib, Seaborn: Data visualization
  - Scipy: Hierarchical clustering
  - Jupyter Notebook: Interactive computing environment

## 📈 Key Findings
- PCA successfully reduced dataset dimensionality while preserving key information
- K-Means and Hierarchical Clustering identified distinct groupings in the data
- Silhouette scores provided insights into clustering effectiveness
- Standardization significantly improved clustering accuracy

## 💡 Skills Demonstrated
- Unsupervised Learning (PCA, Clustering)
- Feature Engineering & Data Preprocessing
- Dimensionality Reduction Techniques
- Model Evaluation Metrics (Silhouette Scores, Explained Variance)
- Python Programming & Data Science Libraries


## 🎯 Methodology
1. **Data Cleaning & Standardization**
   - Handle missing values and normalize numerical features
2. **PCA Implementation**
   - Apply PCA and select optimal components
   - Visualize principal components in reduced dimensions
3. **Clustering Analysis**
   - Compare **K-Means** and **Hierarchical Clustering**
   - Evaluate clusters using **silhouette scores**

## 🌟 Research Contributions
- Demonstrates the power of **unsupervised learning** in structure discovery
- Compares multiple clustering techniques to highlight their effectiveness
- Explores **dimensionality reduction** for improved clustering performance

## 🎓 Learning Outcomes
- Developed expertise in **PCA & Clustering algorithms**
- Applied statistical techniques to **real-world datasets**
- Gained hands-on experience with **Python's ML libraries**

## 🚀 Future Enhancements
- Experiment with **t-SNE or UMAP** for nonlinear dimensionality reduction
- Extend clustering analysis to **other real-world datasets**
- Apply deep learning-based clustering approaches

