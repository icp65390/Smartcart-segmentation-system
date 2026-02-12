# Smartcart-segmentation-system
Auther:- 
Ishwor Chandra Paudyal (ICP)

# Results

<Br>
The SmartCart customer dataset was analyzed using K-Means Clustering to identify distinct customer segments based on purchasing behavior, income, engagement, and demographics.

The Elbow Method (WCSS) indicated an optimal value of K = 4, meaning the dataset naturally forms four customer clusters.

Silhouette Score analysis confirmed that this segmentation provides meaningful separation between groups.

Customers were grouped using behavioral variables such as:

Income

Total Spending

Web, Store, and Catalog Purchases

Recency (last purchase time)

Number of Children

Campaign Response

Customer Tenure

# Cluster Summary (Behavioral Averages)

| Cluster       | Customer Type     | Avg. Income       | Spending Level | Purchase Behavior                 | Web Activity                     | Family Structure   | Campaign Response | Business Insight                            |
| ------------- | ----------------- | ----------------- | -------------- | --------------------------------- | -------------------------------- | ------------------ | ----------------- | ------------------------------------------- |
| **Cluster 0** | Budget Families   | Low–Medium (~39K) | Low            | Mostly in-store purchases         | Moderate–High visits             | More children      | Low               | Price-sensitive customers needing discounts |
| **Cluster 1** | Premium Loyalists | High (~72K)       | Very High      | Catalog + Store heavy buyers      | Lower visits but high conversion | Smaller families   | Moderate          | High-value repeat customers                 |
| **Cluster 2** | Hesitant Browsers | Lowest (~36K)     | Very Low       | Minimal purchases across channels | Highest web visits               | Larger families    | Low               | Conversion-focused marketing needed         |
| **Cluster 3** | Affluent Engaged  | High (~70K)       | Very High      | Strong omnichannel buyers         | Moderate visits                  | Often living alone | Highest           | Most responsive and profitable segment      |

# Discussion

The clustering reveals clear behavioral and economic segmentation among SmartCart customers:

# 1️⃣ Value-Based Segmentation Exists

Income strongly correlates with total spending:

High-income clusters (1 & 3) contribute the majority of revenue.

Low-income clusters (0 & 2) are more deal-driven and cautious buyers.

This confirms that customer value is not evenly distributed, and targeted strategies are required.

# 2️⃣ Browsing Does Not Equal Buying

Cluster 2 shows:

High web visits

Very low purchases

This indicates hesitant or price-sensitive customers who need:

Discounts

Retargeting campaigns

Simplified purchase funnels

# 3️⃣ Omnichannel Customers Are the Most Profitable

Clusters 1 and 3 purchase across:

Web

Store

Catalog

These customers demonstrate true brand engagement, making them ideal for:

Loyalty programs

Membership models

Personalized recommendations

# 4️⃣ Household Structure Influences Spending

Customers with more children (Clusters 0 & 2):

Spend less per transaction

Prefer deals and store purchases

Customers living alone (Cluster 3):

Spend significantly more

Respond better to marketing campaigns

# 5️⃣ Marketing Campaign Response Is Cluster-Dependent

Cluster 3 has the highest response rate, meaning:

Blanket marketing is inefficient.

Targeted marketing will dramatically improve ROI.

# ✅ Conclusion

This project demonstrates how unsupervised machine learning (K-Means clustering) can transform raw retail data into actionable business intelligence.

# Key takeaways:

✔ SmartCart customers naturally divide into 4 meaningful segments
<Br>
✔ High-income omnichannel shoppers drive the majority of revenue
<Br>
✔ A large group of users browse frequently but require incentives to convert
<Br>
✔ Personalized marketing strategies will outperform mass campaigns
<Br>
✔ Data-driven segmentation enables:

Better customer retention

Smarter promotion targeting

Increased lifetime value (LTV)

# Business Impact

By implementing cluster-based personalization, SmartCart can:

Increase conversion rates for hesitant buyers

Focus retention efforts on high-value customers

Optimize marketing spend using behavioral targeting

Improve recommendation systems using segment identity

# ML Techniques Used

Data Preprocessing (Encoding, Scaling)

Exploratory Data Analysis (EDA)

Feature Engineering

K-Means Clustering

Elbow Method (WCSS Optimization)

Silhouette Score Validation

Cluster Characterization & Interpretation

# Thanks