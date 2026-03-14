# SmartCart Customer Segmentation using Clustering Techniques

## Overview

This project implements **customer segmentation using clustering techniques** on an e-commerce dataset.

Clustering is an **unsupervised machine learning technique** used to group customers with similar behavior. In this project, clustering algorithms are applied to analyze customer demographics, purchasing patterns, and engagement data.

The goal is to discover **hidden customer segments** that can help businesses improve marketing strategies and customer retention.

---

## Dataset

The dataset contains **2240 customer records** and **22 attributes** describing customer demographics, purchasing behavior, and website activity.

Some key features include:

- Income
- Recency (days since last purchase)
- Number of web purchases
- Number of catalog purchases
- Number of store purchases
- Website visits per month
- Spending on different product categories

---

## Project Workflow

1. Data preprocessing  
   - Handling missing values  
   - Cleaning the dataset  

2. Feature engineering  
   - Age  
   - Customer tenure  
   - Total spending  
   - Total children  

3. Encoding and scaling  
   - One-Hot Encoding  
   - StandardScaler  

4. Dimensionality reduction  
   - PCA used for visualization  

5. Determining optimal number of clusters  
   - Elbow Method  
   - Silhouette Score  

6. Clustering algorithms  
   - K-Means Clustering  
   - Agglomerative Clustering  

7. Cluster analysis  
   - Understanding cluster characteristics  
   - Assigning business-friendly cluster names  

---

## Final Customer Segments

### Budget Families
- Lower income customers  
- Moderate spending behavior  
- Often families with children  

### Low Engagement Customers
- Lower spending  
- High website visits  
- Lower purchase frequency  

### Premium Customers
- High income customers  
- High spending behavior  
- Frequent buyers  

### Loyal High Spenders
- Highest spending customers  
- Very active buyers  
- High response to marketing campaigns  

---

## Business Value

Customer clustering helps businesses:

- Identify high-value customers  
- Improve targeted marketing campaigns  
- Increase customer retention  
- Personalize promotional offers  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## Author

Adarsh  
B.Tech Artificial Intelligence & Machine Learning Student
