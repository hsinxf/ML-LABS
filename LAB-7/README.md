# Advertising Click-Through Rate Prediction

## Lab Overview

This lab focuses on predicting whether a user will click on an advertisement based on several consumer features. A Logistic Regression model was implemented using a synthetic advertising dataset to classify user behavior with high precision and accuracy.

---

## Dataset Description

The dataset includes the following features:

- **Daily Time Spent on Site**: Consumer time spent on the website (in minutes)
- **Age**: Customer age (in years)
- **Area Income**: Average income of the consumer's geographical area
- **Daily Internet Usage**: Average daily internet usage (in minutes)
- **Ad Topic Line**: Headline of the advertisement
- **City**: Consumer's city
- **Male**: Binary indicator (0 or 1) for gender
- **Country**: Consumer's country
- **Timestamp**: Time of interaction with the advertisement
- **Clicked on Ad**: Target variable (0 or 1)

---

## Technical Workflow

### 1. Exploratory Data Analysis

Data visualization was performed using Matplotlib and Seaborn to identify patterns and relationships:

- Analyzed the distribution of age using histograms
- Explored the relationship between Age and Area Income using joint plots
- Examined correlations between Daily Time Spent on Site and Daily Internet Usage
- Generated pair plots segmented by the "Clicked on Ad" feature to identify behavioral patterns

### 2. Data Preprocessing and Splitting

- Selected numerical features: Age, Area Income, Daily Time Spent on Site, and Daily Internet Usage
- Split the dataset into training and testing sets using a 67/33 ratio

### 3. Logistic Regression Model

- Implemented Logistic Regression using Scikit-Learn
- Increased the maximum number of iterations to ensure convergence due to unscaled data

---

## Performance Evaluation

The model achieved an overall accuracy of **97%**.

**Classification Metrics:**

- **Precision**: 0.98 (low false positive rate)
- **Recall**: 0.96 (captures most actual clicks)
- **F1-Score**: 0.97 (balanced performance)

---

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Conclusion

The Logistic Regression model demonstrates strong performance in predicting advertisement click behavior. The high accuracy and balanced evaluation metrics indicate that the selected features are effective in capturing user engagement patterns.
