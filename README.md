# Customer Personality Analysis & Segmentation
<p align="center">
  <img src="Top-Customer-Segmentation-Examples-every-Marketer-Needs-to-Know.png" width="800">
</p>
## 📌 Project Overview
Customer Personality Analysis helps businesses understand their customers based on demographics, spending habits, purchasing behavior, and responses to marketing campaigns. This project applies Exploratory Data Analysis (EDA), Feature Engineering, PCA, and K-Means Clustering to segment customers into meaningful groups and generate actionable business insights.
### Objectives
- Analyze customer demographics and purchasing patterns.
- Identify customer segments using clustering techniques.
- Study spending behavior across different customer groups.
- Understand customer responses to promotional campaigns.
- Provide business recommendations for targeted marketing.
---
## 📂 Dataset
The dataset contains customer information such as:
- Demographics (Age, Education, Marital Status)
- Annual Income
- Product Spending Categories
- Number of Children
- Purchase Channels
- Promotion Acceptance History
- Customer Enrollment Date
### Dataset Summary
| Metric | Value |
|----------|---------|
| Total Records | 2240 |
| Processed Records | 2216 |
| Features | 29+ |
| Missing Values | Handled |
| Clusters Generated | 4 |
---
## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- Yellowbrick
---
## 🔍 Exploratory Data Analysis
### Customer Age Distribution
- Majority of customers belong to the middle-age category.
- Most customers are between 35–55 years old.
### Income Analysis
- Most customer incomes range between 20,000 and 80,000.
- Higher-income customers generally spend more on products.
### Education Analysis
| Education Level | Percentage |
|----------------|------------|
| Undergraduate | 11.39% |
| Graduate | 50.41% |
| Postgraduate | 38.20% |
### Correlation Analysis
Strong positive relationships were observed between:
- Income ↔ Total Spending
- Income ↔ Wine Purchases
- Income ↔ Meat Purchases
- Income ↔ Catalog Purchases
- Income ↔ Store Purchases
---
## ⚙️ Data Preprocessing
The following preprocessing steps were performed:
- Missing value treatment
- Date conversion and customer tenure creation
- Feature engineering
- Label encoding of categorical variables
- Feature scaling using StandardScaler
- Dimensionality reduction using PCA
---
## 📉 Principal Component Analysis (PCA)
PCA was applied to reduce dimensionality while preserving maximum variance in the dataset.
Benefits:
- Reduced feature complexity
- Improved clustering performance
- Better visualization of customer groups
---
## 🎯 Customer Segmentation
### Clustering Technique
**Algorithm Used:** K-Means Clustering
**Optimal Number of Clusters:** 4
The Elbow Method was used to determine the optimal value of K.
---
# 📊 Cluster Profiles
## 🔵 Cluster 0 – High Value Customers
### Characteristics
- Mostly customers with no children.
- Highest spending among all clusters.
- Strongest response to promotional campaigns.
- Premium customer segment.
### Spending Behavior
- Spending Range: 900 – 2600
### Promotion Acceptance
| Promotions Accepted | Customers |
|---------------------|------------|
| 0 | 281 |
| 1 | 123 |
| 2 | 55 |
| 3 | 37 |
| 4 | 9 |
### Insights
- Most responsive customer group.
- High purchasing power.
- Ideal target for loyalty and premium membership programs.
---
## 🔴 Cluster 1 – Low Engagement Customers
### Characteristics
- Mostly customers with no children or one child.
- Very low spending behavior.
- Least responsive to promotions.
### Spending Behavior
- Spending Range: 0 – 500
### Promotion Acceptance
| Promotions Accepted | Customers |
|---------------------|------------|
| 0 | 546 |
| 1 | 52 |
| 2 | 1 |
| 3 | 0 |
| 4 | 0 |
### Insights
- Large proportion of inactive customers.
- Require discount-based campaigns.
- Potential retention-risk segment.
---
## 🟤 Cluster 2 – Family-Oriented Customers
### Characteristics
- Mostly customers with two children.
- Lower spending levels.
- Low promotional engagement.
### Spending Behavior
- Spending Range: 0 – 500
### Promotion Acceptance
| Promotions Accepted | Customers |
|---------------------|------------|
| 0 | 526 |
| 1 | 47 |
| 2 | 4 |
| 3 | 0 |
| 4 | 2 |
### Insights
- Family responsibilities may influence spending behavior.
- Suitable for bundle offers and family-focused marketing campaigns.
---
## 🟠 Cluster 3 – Potential Growth Customers
### Characteristics
- Mostly customers with one child.
- Moderate to high spending.
- Better campaign response than Clusters 1 and 2.
### Spending Behavior
- Spending Range: 350 – 2000
### Promotion Acceptance
| Promotions Accepted | Customers |
|---------------------|------------|
| 0 | 401 |
| 1 | 100 |
| 2 | 21 |
| 3 | 7 |
| 4 | 0 |
### Insights
- Strong potential to become high-value customers.
- Responsive to personalized marketing strategies.
---
# 📈 Promotion Acceptance Analysis
### Insights
- 281 customers of Cluster 0, 546 customers of Cluster 1, 526 customers of Cluster 2, and 401 customers of Cluster 3 have not accepted any promotions.
- 123 customers of Cluster 0, 52 customers of Cluster 1, 47 customers of Cluster 2, and 100 customers of Cluster 3 have accepted exactly one promotion.
- 55 customers of Cluster 0, 1 customer of Cluster 1, 4 customers of Cluster 2, and 21 customers of Cluster 3 have accepted two promotions.
- 37 customers of Cluster 0 and 7 customers of Cluster 3 have accepted three promotions.
- 9 customers of Cluster 0 and 2 customers of Cluster 2 have accepted four promotions.
### Key Observation
Cluster 0 is significantly more responsive to marketing campaigns compared to other customer groups.
---
# 👨‍👩‍👧 Children vs Spending Analysis
### Insights
- Customers of Cluster 0 mostly have no children and exhibit the highest spending levels, ranging from approximately 900 to 2600.
- Customers of Cluster 1 predominantly have no children or one child, with spending concentrated between 0 and 500.
- Customers of Cluster 2 mainly have two children and display relatively low spending behavior between 0 and 500.
- Customers of Cluster 3 mostly have one child and demonstrate moderate to high spending ranging from approximately 350 to 2000.
### Key Observation
Customers without children generally spend more than customers with multiple children.
---
# 💡 Business Recommendations
## Cluster 0
- Loyalty Programs
- VIP Memberships
- Exclusive Product Launches
- Personalized Premium Offers
## Cluster 1
- Discount Campaigns
- Cashback Offers
- Reactivation Strategies
## Cluster 2
- Family-Oriented Promotions
- Bundle Deals
- Seasonal Discounts
## Cluster 3
- Cross-Selling Campaigns
- Upselling Strategies
- Personalized Recommendations
---
# 📌 Key Findings
- Customer spending strongly correlates with income.
- Customers without children tend to spend more.
- Most customers have never accepted a promotional campaign.
- Cluster 0 represents the most valuable customer segment.
- Cluster 3 represents the highest growth potential.
- Clusters 1 and 2 require targeted marketing interventions to improve engagement.
---
# 🚀 Conclusion
This project successfully segmented customers into four distinct groups based on demographic and behavioral characteristics. The analysis revealed significant differences in spending habits, family structure, and promotion acceptance behavior across clusters.
The insights generated from this project can help businesses:
- Improve customer targeting
- Increase marketing ROI
- Enhance customer retention
- Design personalized campaigns
- Identify high-value customers
By leveraging customer segmentation, organizations can make data-driven marketing decisions and maximize business growth.
---
## 👨‍💻 Author
### Pritish Barupal
- B.Tech, Metallurgical & Materials Engineering
- National Institute of Technology, Raipur
- Data Analytics |  Business Intelligence
### Connect
Mail: pritishbarupal@gmail.com
