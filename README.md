# OSMI Mental Health in Tech survey 2016 – An Unsupervised Learning and Feature Engineering Project 
This unsupervised learning project focuses on exploratory data analysis, feature engineering, dimensionality reduction, and clustering. 
The OSMI Mental Health in tech suvey 2016 dataset was obtained from the Kaggle repository to find groupings within the data. 

## Overview of the project
Mental health in the workplace has become an important topic in recent years. Proper understanding of the employees' well-being 
is highly beneficial for the employers as it impoves the prodictivity. However, analysing data comes with challenges, such as missing values 
or incorrectly entered values. This project investigates whether there are any meaningful clusters within this dataset that may help HR create 
a mental health plan. 

This project consists of the following sections: 
1. Obtaining the data from kaggle.com.
2. Data Exploration
3. Data Preprocessing and Feature Engineering
4. Feature Selection
5. Principal Component Analysis
6. Multidimensional Scaling
7. KMeans Clustering
8. Cluster Visualisation
9. Descriptive Statistics
10. Conclusions
11. Limitations
12. Future Work

## Dataset 
The dataset consists of the answers of 1433 respondents across 63 questions. The dataset is male and USA-dominated. 

## Key results: 
Cluster 0: representing self-employed people (286), slightly older (mean age 36,9), with higher presence of ADHD and slightly higher fear of consequences of disclosure.
Cluster 1: representing traditionally employed people (1142), slightly younger (mean age 33,4), with higher presence of OCD, and with present fear of discussing mental health issues with coworkers and supervisors.

## Technical requirements: 
- Python
- Numpy
- Pandas
- Matplotlib and Seaborn
- Scikit-learn (PCA, MDS, K-Means, TF-IDF, VarianceThreshold)
