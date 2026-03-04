# Customer-Segmentation-Using-K-Means

# Project Overview

This project focuses on segmenting customers based on their purchasing behavior using the K-Means clustering algorithm. The objective is to identify distinct customer groups that can help businesses design targeted marketing strategies instead of using a one-size-fits-all approach.

# Problem Statement

Businesses often struggle to understand different customer behaviors.

The goal of this project is to:

Analyze customer data

Identify meaningful segments

Provide business insights for targeted marketing

# Dataset Description

The dataset used is the Mall Customer Segmentation Dataset.

It contains the following columns:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

Spending Score represents customer purchasing behavior.

# Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

# Project Workflow
1. Data Loading & Cleaning

 Loaded dataset using Pandas.

 Checked for missing values.

 No missing values were found.

 Dataset was clean and ready for analysis.

2️. Exploratory Data Analysis (EDA)

Performed:

Distribution analysis of Annual Income

Distribution analysis of Spending Score

Scatter plot analysis between Income and Spending

# Observation:
 Customers with similar income levels show different spending behaviors.
 This indicates the presence of hidden customer segments.

3️. Feature Selection

Selected key features:

Annual Income (k$)

Spending Score (1–100)

These two features directly represent purchasing power and buying behavior.

4️. Feature Scaling

Applied StandardScaler to normalize the data.

Reason:
K-Means is distance-based, so scaling ensures fair clustering.

5️. Finding Optimal Clusters (Elbow Method)

Used WCSS (Within Cluster Sum of Squares).

The Elbow Method indicated optimal clusters at k = 5.

6️. Model Implementation

Applied K-Means clustering with 5 clusters.

Assigned each customer to a segment.

7️. Cluster Visualization

Visualized clusters using scatter plots.

Five distinct customer segments were identified.

# Customer Segments Identified

1️. High Income – High Spending → Premium Customers
2️.High Income – Low Spending → Careful Customers
3️. Low Income – High Spending → Impulsive Buyers
4️. Low Income – Low Spending → Budget Customers
5️. Medium Income – Medium Spending → Regular Customers

# Business Insights

High income does not always mean high spending.

Premium customers significantly impact revenue.

Budget customers respond well to discount strategies.

Impulsive buyers can be targeted with promotions.

Segmentation enables personalized marketing campaigns.


# Conclusion

The project successfully segmented customers into five meaningful groups using K-Means clustering. These segments provide actionable business insights that can help organizations improve marketing strategies and increase revenue.
