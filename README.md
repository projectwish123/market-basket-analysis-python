# Market Basket Analysis with Python

## Project Overview

Analyzed Target customer survey data using Python to understand customer purchasing behavior, satisfaction levels, customer segments, and personalized recommendation patterns.

## Dataset

- 800 customer records
- 24 columns
- Customer demographics, purchasing behavior, satisfaction, browsing activity, recommendations, and review-related information

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- K-Means Clustering
- Jupyter Notebook / Google Colab

## Key Analysis

### 1. Data Cleaning & Preparation
- Checked duplicate records and inconsistent categorical values.
- Standardized categorical data and removed extra spaces.
- Handled missing values in `Product_Search_Method`.
- Renamed duplicate column names and converted the timestamp into datetime format.

### 2. Customer Behaviour Analysis
- Analyzed customer age and gender distribution.
- Examined purchase frequency and popular purchase categories.
- Analyzed browsing frequency and cart abandonment factors.
- Calculated mean and median satisfaction and rating accuracy.

### 3. Customer Segmentation
Created customer segments based on purchase frequency and shopping satisfaction:

- Frequent Buyers
- Occasional Shoppers
- At-Risk Customers

Compared these segments using demographic and behavioral characteristics.

### 4. K-Means Clustering
Applied K-Means clustering using:

- Shopping Satisfaction
- Rating Accuracy
- Personalized Recommendation Frequency Score

Standardized the numerical features and used an Elbow Curve to evaluate the number of clusters. Three clusters were then applied for behavioral grouping.

### 5. Recommendation Analysis
Analyzed the relationship between:

- Recommendation Helpfulness
- Shopping Satisfaction
- Review Reliability
- Review Helpfulness
- Personalized Recommendation Frequency

### 6. Data Visualization
Created visualizations including:

- Bar charts
- Pie charts
- Satisfaction distribution charts
- Heatmaps
- Elbow curve

## Key Findings

- Average shopping satisfaction was **2.935 out of 5**, with a median of **3**.
- Customer purchasing behavior was analyzed across multiple purchase-frequency categories.
- Customer segmentation identified frequent buyers, occasional shoppers, and at-risk customers.
- K-Means clustering identified three behavioral groups based on satisfaction, rating accuracy, and personalized recommendation scores.
- Recommendation helpfulness and customer satisfaction were analyzed to identify opportunities for improving personalized recommendations.

## Business Insights

The analysis can support strategies for:

- Improving personalized product recommendations
- Reducing customer cart abandonment
- Identifying different customer segments
- Improving customer satisfaction
- Monitoring recommendation engagement and effectiveness

## Project File

`Market_Basket_Analysis_with_Python_Target_.ipynb`
