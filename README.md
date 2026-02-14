🛍️ Customer Segmentation using K-Means

📌 Overview

This project applies the K-Means clustering algorithm to segment mall customers based on their purchasing behavior using selected numerical features.

🎯 Objective

To group customers based on:
Annual Income (k$)
Spending Score (1–100)

🛠️ Tools & Libraries Used

Python
Pandas
Seaborn
Matplotlib
Scikit-learn
Kneed

🔄 Workflow

Loaded the dataset (Mall_Customers.csv)
Performed basic data exploration (info(), shape, isnull())
Visualized data using scatterplot
Selected features:
Annual Income (k$)
Spending Score (1–100)
Applied StandardScaler for feature scaling
Implemented K-Means clustering
Used the Elbow Method to analyze WCSS
Used Kneed library to automatically determine the optimal number of clusters
Visualized clustered customers using scatterplot

📊 Result

Customers were grouped into clusters based on similarities in income and spending behavior.
The optimal number of clusters was determined using the Elbow Method and Kneed.

🚀 Conclusion

K-Means clustering successfully segmented customers based on purchasing patterns, providing a structured approach for customer grouping.
