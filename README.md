# Mall Customers & Unsupervised Classification

## Overview

- In this project, after cleaning the data, we classify customers based on their columns and characteristics (unsupervised learning) and find a pattern between age, gender, income, and purchasing intention to classify them.

## Objective

- The goal of this project is to find a relationship between customer information, how much they are willing to spend, and classify them using unsupervised learning.

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA) using Pandas & NumPy
- Data visualization with Matplotlib & Seaborn

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA) using Pandas & NumPy
- Data visualization with Matplotlib & Seaborn
- Feature engineering with mall customers features
- Statistical analysis and distribution interpretation
- Using unsupervised learning with a model (K-Means)
- Data preprocessing and scaling with LabelEncoder
- Model evaluation and classification analysis
- Writing clean, structured, and reproducible Python code

## Dataset

- Source: kaggle
- Name: Mall Customers Dataset
- Rows: 200
- Columns: 5
- Link: https://www.kaggle.com/datasets/amisha0528/mall-customers-dataset

### Features

- CustomerID - Customer number
- Genre - Customer gender
- Age - Customer's age
- Annual Income (k$) - Customer income
- Spending Score (1-100) - Customer's willingness to buy

## Feature Engineering

A column was created to classify customers with unsupervised learning:
- Cluster: Based on the relationships between customer characteristics.

In this column, customers are divided into five groups.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Visualizations

The following plots are generated to analyze the data:

- Line Plot (most appropriate number of clusters)
- Count Plot (counting species in each cluster)
- Histogram (distribution by species)
- Scatter Plot (relationships between features)
- Heatmap (features correlations)
- Box Plot (outlier detection)
- Pie Chart (species distribution)
- Pair Plot (pairwise feature relationships)
- Min-Max Chart (size comparison between species)

## Machine Learning

- Type: Unsupervised learning
- Model: Clustering algorithm(K-Means)
- Data Scaling: LabelEncoder
- Model Evaluation: Five clusters with high correlation

## Results

- Five clusters is best because after five the slope of the graph decreases.
- The correlation is high in this number of models.
- Column correlation is low.
- The number of people in cluster C is higher.
- There are more females than males.
- The correlation in income and propensity to buy is high across clusters.
- The minimum and maximum ages are 18 and 70 respectively.
- The lowest and highest incomes are $15,000 and $137,000 respectively.
- This classification is not related to age because the correlation between age and other columns is low, but the correlation between income and purchasing intention columns is high.
- The smallest difference in income and willingness to buy is in cluster C, where the age of customers is between 18 and 70. The number of women and men in this cluster is 48 and 33, respectively.

## Conclusion

This project demonstrates a complete data science workflow:

- Data Mining
- Visualization
- Feature Engineering
- Unsupervised Machine Learning

This project learns about customer characteristics for revenue and purchase and classifies them