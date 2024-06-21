# Analysis of  Customer Segmentation Using Clustering for Credit Card Data

### Objective
To develop a clustering model for customer segmentation based on the provided credit card usage data from a bank, encompassing the last six months. The goal is to identify distinct customer groups to enable targeted marketing strategies and personalized services.

### Background
In the highly competitive banking sector, understanding customer behavior is crucial for improving customer satisfaction and loyalty. By segmenting customers based on their credit card usage patterns, the bank can tailor its products, services, and marketing efforts to better meet the needs of different customer groups.

### Data Description
The dataset consists of credit card usage information for the past six months. It includes various attributes related to customers' spending behavior, payment patterns, and other relevant metrics. 

### Requirements
1. **Data Preprocessing**: 
    - Handle missing values.
    - Normalize or standardize the data.
    - Encode categorical variables if any.

2. **Feature Engineering**: 
    - Identify and select relevant features for clustering.
    - Perform dimensionality reduction if necessary.

3. **Clustering Algorithm**: 
    - Choose appropriate clustering algorithms (e.g., K-Means, Hierarchical Clustering, DBSCAN).
    - Determine the optimal number of clusters using methods such as the Elbow Method, Silhouette Score, or other suitable techniques.

4. **Model Evaluation**: 
    - Evaluate the clustering results using metrics like silhouette score, Davies-Bouldin index, etc.
    - Interpret the clusters and validate them against business knowledge and objectives.

5. **Actionable Insights**: 
    - Provide a detailed analysis of each customer segment.
    - Recommend specific strategies for each segment to enhance customer engagement and satisfaction.

### Expected Deliverables
1. **Clustering Model**: A well-documented clustering model with code implementation.
2. **Segmentation Report**: A comprehensive report detailing the characteristics of each customer segment.
3. **Actionable Insights**: Recommendations for marketing and service strategies tailored to each customer segment.
4. **Visualization**: Visual representations of the clusters and key findings for easy interpretation by stakeholders.


## Technologies
1. Python
2. Pandas
3. Scikit-Learn
4. scipy
5. matplotlib
6. yellowbrick
7. pickle

---

## Findings

Based on the data analysis results, I can draw several key findings:

### Cluster Interpretation:

Based on the average values obtained, I can draw the following conclusions for each cluster:

**Cluster 0:**
- High balance
- High purchase frequency
- High one-off purchases
- High installment purchases
- High credit limit

Cluster 0 indicates customers who have a high balance and frequently make purchases, including both one-off and installment purchases. They also have a high credit limit.

**Cluster 1:**
- Low balance
- Low purchase frequency
- Low one-off purchases
- Low installment purchases
- Low credit limit

Cluster 1 represents customers with low balances who make infrequent purchases, both one-off and installment, and have a low credit limit.

**Cluster 2:**
- High balance
- Low purchase frequency
- Low one-off purchases
- Normal installment purchases
- High credit limit

Cluster 2 consists of customers with high balances but lower purchase frequencies. They make fewer one-off purchases but maintain normal installment purchase habits. They also possess a high credit limit.

**Cluster 3:**
- Low balance
- Low purchase frequency
- Low one-off purchases
- High installment purchases
- Low credit limit

Cluster 3 includes customers with low balances who make infrequent purchases, especially one-off purchases. However, they have a higher tendency to make installment purchases despite having a low credit limit.

These interpretations provide insights into the different spending behaviors and financial profiles within each cluster, helping to tailor marketing strategies or financial products accordingly.


### Recommendation

The model successfully performed clustering on the numeric dataset. However, due to the challenge of determining cluster characteristics solely from numerical data, it would be beneficial to consider datasets that include clear categorical data. This can lead to better-defined cluster characteristics and more insightful analyses.