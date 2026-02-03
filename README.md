## 📝 Project Description

### Context
This project was developed as part of the **TCS iON Industry Project (AIP 135)**. The primary objective was to solve the challenge of "one-size-fits-all" marketing by leveraging data-driven insights to understand customer behavior in a retail environment.

### The Problem
Traditional marketing often fails to engage customers effectively because it treats all shoppers the same. This leads to lower conversion rates and poor customer retention.

### The Solution
I developed an intelligent system that performs two main functions:
1. **Customer Segmentation:** Using the **K-Means Clustering** algorithm, I categorized customers into distinct groups (such as 'VIP/High-Value,' 'At-Risk,' and 'New Customers') based on their purchasing patterns.
2. **Personalized Recommendations:** I built a **Hybrid Recommendation Engine** that combines user-similarity (Cosine Similarity) with cluster-based popularity to suggest products that a customer is most likely to buy next.

### Key Highlights:
* **Advanced Preprocessing:** Applied `RobustScaler` and log transformations to handle outliers, ensuring "VIP" customers didn't skew the model results.
* **Business Intelligence:** Created a comprehensive **Power BI Dashboard** to visualize the clusters, allowing stakeholders to see the monetary value of each segment at a glance.
* **TCS Standards:** Followed industry-standard documentation, including a Test Design Document (TDD) to validate model accuracy and business logic.
