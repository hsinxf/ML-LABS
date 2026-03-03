# Sports Car Performance & Price Analysis

This project explores a dataset of high-performance sports cars, focusing on data cleaning, preprocessing, and dimensionality reduction using Principal Component Analysis (PCA).

## Project Objectives
The goal of this assignment was to transform raw, "messy" data into a format suitable for machine learning and to understand the underlying relationships between car specifications.

## Tasks Performed

### 1. Data Quality Assessment
* Identified missing values in engine and torque specifications.
* Handled data type inconsistencies (converting price and horsepower from strings/objects to numeric floats).
* Cleaned special characters ($, commas, and units).

### 2. Missing Value Strategy
* Applied **Median Imputation** to fill gaps in the dataset. 
* *Why:* The median was chosen to ensure that extreme hypercar prices did not skew the average.

### 3. Outlier Detection
* Used the **Interquartile Range (IQR)** method to identify and handle price outliers.
* Filtered out statistical anomalies to ensure the analysis focused on the core sports car market.



### 4. Normalization
* Applied **Min-Max Scaling** to bring all features into a [0, 1] range.
* Applied **Z-Score Normalization (Standardization)** to prepare the data for PCA, ensuring each feature has a mean of 0 and a standard deviation of 1.

### 5. PCA & Explained Variance
* Performed **Principal Component Analysis (PCA)** to reduce the complexity of the data.
* Analyzed the **Explained Variance Ratio** to determine how much information is captured by the primary components.



## Key Insights
* **Correlation:** Strong positive correlation between Horsepower and Price, and a strong negative correlation between Horsepower and 0-60 MPH times.
* **Dimensionality:** The first two principal components explain the vast majority of the variance, suggesting that most car performance can be summarized by just two "latent" factors (e.g., Raw Power and Value).

## Technologies Used
* Python
* Pandas & NumPy
* Scikit-Learn (Pre-processing & PCA)
* Matplotlib & Seaborn (Visualization)
