# Data Mining Course for DS Master 2024/2025 Repository
### Introduction to the project 
  Following a thorough preliminary analysis of the features and data distribution, we, as ABCDEats data analysts, are focusing on customer segmentation in this project, using customer data collected over three months. The goal is to develop marketing strategies that improve customer retention and foster stronger engagement. This involves categorizing the customer base into segments based on various characteristics and behaviors to uncover actionable insights.
In the earlier stages, we conducted data cleaning and clustering to prepare the dataset for effective segmentation. This included resolving issues like missing values, duplicates, outliers, and inconsistencies. After feature selection, the dataset was split into two groups: one centered on behaviors and the other on preferences. To perform clustering, we applied models such as K-means, Hierarchical Clustering, Self-Organizing Maps (SOMs), and DBSCAN, Mean-shift and Gaussian Mixture Model. Through merging clusters from both perspectives we were able to build a data-driven approach that enhances the company’s understanding of its customers, enabling more personalized services and better-targeted marketing strategies.

### This Repository is divided in 2 main folders.
1. Part 1 - Notebooks used for the first delivery
2. Part 2 - Notebooks used for the second delivery

Part 1 --> Exploratory Data Analysis.
- This analysis starts with an in-depth exploration of the dataset, which includes descriptive analysis, followed by the detection of patterns and anomalies, the identification of relationships between variables and ends with feature engineering.

Part 2 --> Clustering approach and Profiling 
- We divided features into two segments: behavior and preference. We tested the clustering of these perspectives using various models, including k-means, hierarchical clustering, Gaussian mixture, SOMs, DBSCAN, and mean-shift, and selected the best model for each segment based on R² which were SOMs in both perspectives. Finally, we merged the segments using hierarchical clustering, identifying four distinct customer groups that we further analysed to capture meaningful marketing insights.


# Authors
- Oumayma Ben Hhfaiedh
- Ana Pedro Caleiro
- Rute Teixeira
- Érica Parracho
