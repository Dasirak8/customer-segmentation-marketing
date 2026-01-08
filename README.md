Overview

This project demonstrates a customer segmentation analysis using transactional e-commerce data. The goal is to identify distinct customer groups based on purchasing behavior and provide actionable insights to support targeted marketing campaigns, retention strategies, and budget optimization.

Business Objective

Segment customers based on recency, frequency, and monetary value (RFM) to:

Improve campaign targeting and personalization

Identify high-value customers for retention and upsell

Detect low-engagement and at-risk customers for reactivation efforts

Dataset

Public e-commerce transactional dataset

Fields include: CustomerID, InvoiceDate, Quantity, UnitPrice, and Country

Methodology

Data Preparation

Removed invalid or incomplete records

Calculated revenue at the transaction level

Aggregated customer-level features

Feature Engineering

Recency: Days since last purchase

Frequency: Number of unique purchases

Monetary: Total customer spend

Statistical Analysis

Descriptive statistics and distribution analysis

Log transformation and scaling to address skewness

Clustering

K-means clustering applied to RFM features

Optimal number of clusters selected using silhouette analysis

Validation

Silhouette scores for cluster separation

Segment size distribution and interpretability

Business relevance of each segment

Customer Segments Identified

High-value loyal customers
Frequent purchases, high spend, and recent activity. Ideal for retention, loyalty programs, and upsell campaigns.

Occasional / price-sensitive customers
Moderate engagement and spend. Suitable for promotional and reactivation campaigns.

At-risk or churned customers
Low engagement and long recency. Require cost-efficient win-back or remarketing strategies.

Key Insights

A small group of high-value customers contributes a disproportionate share of total revenue, which is typical in e-commerce environments.

The majority of customers fall into lower-engagement segments, highlighting opportunities for targeted reactivation.

Clear behavioral separation enables more efficient and data-driven marketing decisions.

Tools & Technologies

Python

pandas, NumPy

scikit-learn

matplotlib, seaborn

Business Impact

This segmentation provides a practical framework for:

Improving marketing ROI through targeted messaging

Prioritizing retention efforts for high-value customers

Allocating budget more efficiently across customer segments

Next Steps

Integrate segmentation into campaign performance tracking

Enrich with behavioral or demographic features

Apply similar methodology to content or SEO performance data

Author

Mikayil Badalov
GitHub: https://github.com/Dasirak8
