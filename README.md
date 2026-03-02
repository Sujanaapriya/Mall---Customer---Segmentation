# Mall---Customer---Segmentation
## Project Overview

This project performs customer segmentation using K-Means clustering, a well-known unsupervised learning algorithm in machine learning and data analysis. The goal is to identify distinct groups of customers based on their demographic and spending behavior, helping businesses make data-driven decisions for targeted marketing, personalized services, and improved customer engagement

## Dataset 
The dataset used in this project is sourced from Kaggle and contains 200 customer record

## Tools Libraries
 Python — core programming language
 Pandas & NumPy — data manipulation
 Scikit-Learn — K-Means algorithm, preprocessing
 Matplotlib & Seaborn — visualizations

 ## Workflow
1. Data Loading & Inspection

2. Exploratory Data Analysis (EDA)

3. Feature Scaling

4. Determining Optimal Clusters

5. Model Training — K-Means

6. Cluster Visualization & Analysis

7. Interpretation & Insights

Why K= 5
From 1 → 5 clusters, each new cluster noticeably improves how well data points are grouped.
Beyond 5 clusters, the improvement is minimal — additional clusters don’t add meaningful group separation.

5 clusters correspond to meaningful customer segments like:
Low income, low spenders
Low income, high spenders
Moderate income/spenders
High income, low spenders
High income, high spenders


Silhouette Score: 0.55  
The score supports that the chosen number of clusters forms meaningful customer segments, balancing separation and interpretability. This quantitative evaluation complements the insights obtained from the Elbow Method and the visual cluster plots.
