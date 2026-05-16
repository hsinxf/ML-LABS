# Credit Card Customer Segmentation

## Project Overview

This project applies K-Means clustering to segment credit card customers based on their financial behavior. The goal is to identify different customer groups that can help businesses improve marketing strategies and customer management.

---

## Dataset

The dataset contains information about credit card customers, including:

- Balance
- Purchases
- Cash Advance
- Credit Limit
- Payments
- Purchase Frequency
- Cash Advance Frequency
- Tenure

Dataset size:

- 8950 rows
- 18 columns

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Steps Performed

### 1. Data Loading

The dataset was loaded using Pandas.

### 2. Data Cleaning

- Removed the `CUST_ID` column.
- Filled missing values using the mean.

### 3. Exploratory Data Analysis

- Displayed dataset information and statistics.
- Created histograms and correlation heatmaps.
- Visualized relationships between important features.

### 4. Feature Scaling

StandardScaler was used to normalize the data before clustering.

### 5. K-Means Clustering

- Used the elbow method to determine the optimal number of clusters.
- Evaluated clusters using silhouette score.
- Selected K = 3.

### 6. Cluster Visualization

PCA was used to reduce dimensions for visualization.

---

## Results

The model grouped customers into 3 main segments:

1. Low-activity customers
2. High-value customers
3. Cash-advance-focused customers

These segments can help businesses improve targeted marketing and customer retention strategies.

---

## How to Run

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
