# Business Insight from Clustering and Analyzing Customer Behaviours
In this project, I'm a data scientist hired by a leading consumer credit bank. My job is to provide insights and advice on identifying customer segments through clustering. This will help the bank focus on retaining more valuable customers and solve their customer attrition problem.

## Industry Landscape for the Consumer Credit Business
Acquiring new customers is a costly process, and retaining valuable customers is crucial for the success of the consumer credit business. By analyzing customer account activity and demographics through clustering, the bank can better understand which customers are most valuable and develop effective retention strategies.

## Project Goal

Our goal is to identify customer segments by clustering and analyzing their behavior.

## Approach

In my initial attempt, I performed K-means clustering with 14 features, but the elbow method did not provide a clear flattening pattern. However, using the Silhouette score, I was able to identify the ideal number of clusters.

To further refine the analysis, I performed feature engineering through Principal Component Analysis (PCA) to reduce the number of features to two components. With two PCA components, which explain 33% of the variance, the Silhouette score more than tripled to 0.383, indicating that clusters are better defined.

## Customer Segmentation Insights

By analyzing the customer attrition numbers for each cluster, I found that Group 3 had the highest number of attritions at 862. However, further analysis revealed that even though these customers are loyal and long-time users, their credit card usage, transaction amount, and transaction count are low relative to other groups.

The key insight is that the bank should focus on retaining Group 1 customers, who are newer users but have higher credit card usage, transaction amount, and transaction count compared to other groups. This can help the bank increase revenue and optimize their marketing budget.

## Learning Points

Through customer segmentation with k-means clustering, the bank can focus on retaining more valuable customers instead of being misdirected by groups with high numbers of attrition but lower value.
