# RFM-Based Customer Analytics for Strategic Marketing

## Overview
This project focuses on segmenting the customer base using the RFM (Recency, Frequency, Monetary) model to understand customer behavior and optimize marketing strategies. By analyzing customers based on their:
- **Recency**: Time since their last purchase,
- **Frequency**: Number of purchases, and
- **Monetary Value**: Total amount spent,

We can classify them into distinct segments to better target each group. The dataset used contains **500,000 rows** of billing details, offering a comprehensive view of customer interactions.

## Objective
The main goal is to leverage **Unsupervised Learning** techniques—specifically **KMeans Clustering**—to segment customers based on their RFM values. Through this segmentation, we aim to personalize marketing efforts for each group to enhance customer engagement, retention, and revenue growth.

## Methodology

1. **Data Preprocessing**
   - Data cleaning and preparation to handle missing or inaccurate values.
   - Creation of **RFM metrics** for each customer, derived from their billing data:
     - **Recency**: Days since the customer’s last purchase.
     - **Frequency**: Total number of purchases.
     - **Monetary Value**: Total amount spent by the customer.

2. **Customer Segmentation using KMeans Clustering**
   - KMeans Clustering was used to group customers into distinct segments based on their RFM scores.
   - Optimal number of clusters determined using the **Elbow Method** and **Silhouette Score**.

3. **Customer Insights**
   - The clustering results revealed three key segments:
     - **High-Value Segment**: Customers with low recency (recent purchasers), high frequency, and high monetary value.
     - **Mid-Value Segment**: Customers with moderate recency and frequency, indicating potential for growth.
     - **Low-Value Segment**: Customers with high recency (haven’t purchased recently) and low frequency, indicating a need for re-engagement.
  
4. **Visualizations with PowerBI**
   - Customer segments were visualized using **PowerBI** dashboards, providing clear insights into the behavior of each group.


![image](https://github.com/darKKnight14110/Customer-Segmentation---Clustering-Methods/assets/142472592/e237242a-e7aa-4d73-a3b3-e8d8faf79f8b)

## Results
Through this analysis, we gained actionable insights into customer behavior. The segmentation allowed us to:
- **High-Value Segment**: Implement loyalty programs and exclusive discounts to retain engagement.
- **Mid-Value Segment**: Identify opportunities for upselling and cross-selling.
- **Low-Value Segment**: Launch win-back campaigns to re-activate inactive customers.

## Impact
By personalizing marketing strategies for each customer segment, businesses can:
- Increase **customer engagement** and **retention**.
- Optimize marketing investments by targeting the right audience with the right offers.
- Drive **revenue growth** through more efficient and effective campaigns.

## Tools Used
- **KMeans Clustering** for segmentation.
- **PowerBI** for data visualization and presentation.
- **Python (Pandas, Scikit-learn, Matplotlib)** for data preprocessing and modeling.

