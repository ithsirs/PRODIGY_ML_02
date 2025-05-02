# PRODIGY_ML_02
This repository contains the source code of the task-02Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.  Dataset :- https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

# 🛍️ Customer Segmentation using K-Means Clustering

This project performs unsupervised customer segmentation for a retail dataset using **K-Means Clustering**. The goal is to group customers into clusters based on purchasing behavior to assist in targeted marketing and customer relationship strategies.

## 📁 Dataset

- **Source**: [Kaggle - Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- The dataset contains features such as:
  - Customer ID
  - Gender
  - Age
  - Annual Income
  - Spending Score

## 📊 Data Preprocessing

- Handled categorical features using **Label Encoding**.
- Applied **StandardScaler** to normalize the data before clustering.
- Performed **PCA (Principal Component Analysis)** for dimensionality reduction and visualization (2D).

## 🤖 Clustering Algorithm

- **K-Means Clustering** from scikit-learn is used for segmentation.
- Optimal number of clusters (`k`) is determined using:
  - **Elbow Method**
  - **Silhouette Score**

## 🧪 Evaluation & Visualization

- Visualizations include:
  - Scatter plots of clusters using PCA-reduced components.
  - Cluster centroids.
  - 3D interactive visualizations with Plotly for deeper insight.
- The silhouette score is used to validate the quality of clusters.

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Plotly
- scikit-learn
- PCA
- K-Means
- LabelEncoder, StandardScaler
- kagglehub (for dataset retrieval)


## 💾 Model Export

- Final KMeans model is saved using `joblib` for reuse or deployment.

