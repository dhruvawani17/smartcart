# SmartCart Customer Segmentation using Machine Learning

## Project Overview

This project analyzes SmartCart customer data and applies Machine Learning clustering techniques to segment customers into distinct groups based on their demographics, spending behavior, and purchasing patterns.

The goal is to help businesses better understand their customers and create targeted marketing strategies.

---

## Objectives

- Clean and preprocess customer data
- Perform feature engineering
- Detect and remove outliers
- Scale and normalize features
- Reduce dimensionality using PCA
- Identify customer segments using clustering algorithms
- Visualize customer groups and spending behavior

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KMeans Clustering
- Agglomerative Clustering
- PCA (Principal Component Analysis)

---

## Dataset Features

The dataset contains customer information such as:

- Income
- Age
- Education
- Marital Status
- Customer Tenure
- Total Spending
- Number of Children
- Product Purchase History
- Campaign Responses

---

## Data Preprocessing

### Missing Value Handling
- Filled missing values in Income using median imputation.

### Feature Engineering
Created new features:

- Age
- Customer_Tenure_Days
- Total_Spending
- Total_Children
- Living_With

### Data Cleaning
- Removed unnecessary columns
- Handled categorical variables
- Removed extreme outliers

---

## Exploratory Data Analysis (EDA)

Performed:

- Distribution Analysis
- Correlation Analysis
- Pair Plots
- Scatter Plots
- Cluster Visualization

---

## Feature Scaling

Used StandardScaler to standardize features before clustering.

```python
from sklearn.preprocessing import StandardScaler
```

---

## Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce dimensions while preserving maximum variance.

```python
from sklearn.decomposition import PCA
```

---

## Clustering Algorithms

### K-Means Clustering

- Used Elbow Method to determine optimal K
- Evaluated clusters using Silhouette Score

```python
from sklearn.cluster import KMeans
```

### Agglomerative Clustering

Implemented hierarchical clustering using Ward linkage.

```python
from sklearn.cluster import AgglomerativeClustering
```

---

## Model Evaluation

Used:

- Elbow Method
- Silhouette Score

to determine optimal cluster formation.

---

## Results

The analysis successfully segmented customers into multiple clusters based on:

- Income levels
- Spending habits
- Family structure
- Customer engagement

These segments can be used for:

- Personalized marketing
- Product recommendations
- Customer retention strategies
- Business decision making

---

## Visualizations

- Pair Plots
- Cluster Scatter Plots
- 3D PCA Cluster Visualization
- Income vs Spending Analysis
- Cluster Distribution Charts

---

## Project Structure

```
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/SmartCart-Customer-Segmentation.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## Future Improvements

- DBSCAN Clustering
- Customer Lifetime Value Prediction
- Recommendation System
- Interactive Dashboard using Streamlit or Power BI

---

## Author

Dhruva Wani

Artificial Intelligence & Data Science Student  
K. J. Somaiya Institute of Technology

---
