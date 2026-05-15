# Smartcart Customer Segmentation

This project applies unsupervised machine learning to perform customer personality analysis for a retail company. By segmenting customers into distinct groups based on their purchasing habits, demographics, and response to marketing campaigns, the business can better tailor its strategies for different customer profiles.

## Project Overview :
The goal of this analysis is to identify different customer segments (clusters) to help the "Smartcart" marketing team optimize their resource allocation and product offerings.

### Key Objectives:
- Data Cleaning: Handling missing values and feature engineering (calculating age, total spend, etc.).

- Exploratory Data Analysis (EDA): Visualizing distributions and correlations between customer attributes.

- Clustering: Using the K-Means algorithm to group similar customers.

- Profiling: Interpreting the clusters (e.g., "Big Spenders," "Frugal Families," etc.).

### Dataset Description
The project uses smartcart_customers.csv, which contains information on:

- Demographics: Year of birth, Education, Marital Status, and Income.

- Products: Amount spent on Wines, Fruits, Meat, Fish, Sweets, and Gold.

- Promotions: Number of deals purchased and responses to various campaigns.

- Place: Number of purchases made through Web, Catalog, and Stores.

### Tech Stack
- Language: Python

- Environment: Jupyter Notebook / VS Code

- Libraries: * pandas & numpy (Data Manipulation)

- matplotlib & seaborn (Data Visualization)

- scikit-learn (Machine Learning & Scaling)

## Results & Clusters
- The analysis identifies 4 distinct customer clusters based on features like:

- Income vs. Spending: High-income customers who prefer meat and wine vs. lower-income families.

- Family Size: Impact of having kids/teens at home on purchasing behavior.

- Living Status: Differentiation between partners and individuals living alone.