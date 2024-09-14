# Online Retail Sales Clustering Project

## Overview
This project involves clustering retail sales data to identify different customer segments based on their purchasing behavior. The analysis includes visualizations using violin plots to interpret the characteristics of each cluster.

## Data
The dataset used in this project is the retail sales dataset from the UCI Machine https://archive.ics.uci.edu/dataset/352/online+retail Learning Repository.

## Clustering Analysis
The clustering analysis focuses on three key metrics:
- **Monetary Value**: The total amount spent by customers.
- **Frequency**: The number of purchases made by customers.
- **Recency**: The time since the last purchase made by customers.

## Clusters
The customers are segmented into four clusters, each with specific characteristics and actionable insights:

### Cluster 0: Re-engage
- **Rationale**: The combination of lower monetary value, frequency, and recency suggests that Cluster 0 consists of less engaged customers who are not contributing significantly to sales. This cluster might represent a segment that requires more attention to boost their engagement and spending.
- **Action**: 
  - Personalized re-engagement campaigns
  - Exclusive discounts
  - Customer surveys

### Cluster 1: Nurture
- **Rationale**: The combination of slightly lower monetary value and frequency, but higher recency, suggests that Cluster 1 consists of recently engaged customers who have potential but are not yet fully contributing to sales. This cluster might benefit from nurturing strategies to increase their spending and purchase frequency.
- **Action**: 
  - Loyalty programs
  - Personalized recommendations
  - Engaging content

### Cluster 2: Retain
- **Rationale**: The combination of higher monetary value and frequency, but lower recency, suggests that Cluster 2 consists of high-value customers who have not made recent purchases. This cluster represents a valuable segment at risk of churning and requires retention strategies to bring them back and maintain their engagement.
- **Action**: 
  - VIP treatment
  - Re-engagement offers
  - Feedback and improvement

### Cluster 3: Maintain
- **Rationale**: The combination of slightly higher monetary value and frequency, but slightly lower recency, suggests that Cluster 3 consists of moderately high-value customers who are somewhat engaged but have not made very recent purchases. This cluster might benefit from strategies to maintain their engagement and spending levels.
- **Action**: 
  - Regular updates
  - Special promotions
  - Enhanced customer experience

## Visualizations
The project includes violin plots to visualize the distribution of monetary value, frequency, and recency across different clusters. The plots are saved in the `images` folder.
