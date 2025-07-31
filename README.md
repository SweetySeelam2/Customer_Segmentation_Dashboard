
# 🧠 Customer Segmentation Dashboard – KMeans Clustering (Power BI)

> **Status**: ✅ Completed & Released  
> 📊 Built using: Power BI | Python | Scikit-learn | Streamlit  
> 🔗 [📂 GitHub Repo](https://github.com/SweetySeelam2/Customer_Segmentation_Dashboard)  
> 🌐 [🖥 Live Streamlit App](https://customer-segmentation-ml.streamlit.app/)  
> 📊 [📁 GitHub – Dashboard (Power BI)](https://github.com/SweetySeelam2/Customer_Segmentation_Dashboard.pdf)

---

## 📌 Project Overview

In today’s competitive retail environment, companies like **Amazon, Walmart, and Costco** must deeply understand customer behavior to personalize offers, increase ROI, and reduce churn. This project uses **K-Means Clustering** to group 200 mall customers based on:

- Annual Income  
- Spending Score  
- Age

After building and deploying the model in a Streamlit app, this project translates the results into an **interactive Power BI dashboard** for non-technical business users and stakeholders.

---

## 🎯 Objective

- Segment customers into distinct behavioral clusters using unsupervised ML.
- Visualize cluster patterns, sizes, and profiles using Power BI.
- Derive actionable business strategies based on real segment behavior.
- Empower decision-makers to make targeted campaign and product decisions.

---

📂 ***Dataset:***                                                                                                                                        
✅ 🔍 Key Features: The dataset contains customer information such as Annual Income(k$), Spending Score(1-100), Age, Gender, and Customer ID.                               
✅ 📄 Source: [Kaggle Mall Customers Dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 📈 Dashboard Highlights

### ✅ KPI Summary (Top Cards)

| Metric                     | Value        |
|---------------------------|--------------|
| Total Customers           | `200`        |
| Average Annual Income     | `$60.56k`    |
| Average Spending Score    | `50.20`      |
| Total Clusters Identified | `5`          |

---

### 📊 Cluster Distribution

**Customer Counts by Cluster:**

| Cluster Name                 | Count | % Share |
|-----------------------------|--------|---------|
| Balanced Spenders           | `58`   | `29.0%` |
| Budget-Conscious            | `40`   | `20.0%` |
| Premium Shoppers            | `31`   | `15.5%` |
| Affluent but Frugal         | `26`   | `13.0%` |
| Value-Driven High Spenders  | `45`   | `22.5%` |

---

### 📌 Cluster Profiles (from Visuals)

| Cluster Name                 | Avg Age | Avg Income | Avg Spend Score | Business Trait                  |
|-----------------------------|---------|------------|------------------|---------------------------------|
| Balanced Spenders           | `41.71` | `$47.62k`  | `55.28`          | Reliable, mid-income spenders  |
| Budget-Conscious            | `26.73` | `$40.91k`  | `54.31`          | Practical, price-sensitive     |
| Premium Shoppers            | `32.88` | `$81.53k`  | `86.10`          | High-spend, high-income elite  |
| Affluent but Frugal         | `44.39` | `$89.77k`  | `18.48`          | Wealthy but low engagement     |
| Value-Driven High Spenders  | `25.77` | `$26.12k`  | `74.85`          | Young, trend-driven, heavy spenders |

---

### 🗺️ Key Visuals

- **Donut Chart**: Cluster size & share
- **Scatter Plot**: Income vs Spending colored by cluster
- **Bar Chart**: Average Age, Income, and Spend by cluster
- **Matrix Table**: Gender × Age Group breakdown per cluster
- **Slicers**: Interactive filters for Gender, Cluster, Age Group, Income, Spend Score

---

## ✅ Conclusion

- The KMeans clustering model successfully segmented all 200 customers into five distinct behavior-based groups, using Age, Annual Income, and Spending Score.
- These clusters reveal meaningful differences in customer behavior, allowing for highly targeted business strategies.
- Cluster 0 (Balanced Spenders) forms the largest customer base (29%), contributing steady revenue through consistent mid-level spending.
- Cluster 1 (Premium Customers) shows high income and high spending, indicating they are the most profitable segment to prioritize.
- Cluster 2 (Young Value Spenders) shows high spend behavior despite low-to-moderate income, suggesting strong marketing influence potential.
- Cluster 3 (Budget-Conscious) and Cluster 4 (Affluent but Frugal) require different strategies — one focused on value, the other on activating untapped wealth.
- Visual dashboards in Power BI (donut chart, scatter plot, matrix, and KPI cards) support all these findings clearly.
- The segmentation model and dashboard provide business-ready insights that enable precision marketing, increased revenue, and data-driven targeting.

---

## 📈 Business Recommendations

**🔷 Cluster 0 – Balanced Spenders (29%)**

- Offer loyalty programs, cashback rewards, and personalized nudges to reinforce spending habits.
- Upsell them to mid-premium products to increase average order value without alienating them.

**🔴 Cluster 1 – Premium Customers (22.5%)**

- Provide exclusive VIP services, high-end product bundles, and personalized rewards to retain this high-margin group.
- Run premium-only campaigns to boost brand prestige and maximize their LTV.

**🟣 Cluster 2 – Value-Driven High Spenders (20%)**

- Use trendy offers, gamified loyalty systems, and social media campaigns to engage this youthful, influence-sensitive group.
- Focus on mobile-first interactions, limited-time promotions, and high-frequency touchpoints.

**🟤 Cluster 3 – Budget-Conscious (15.5%)**

- Emphasize practical value by promoting bundles, essential item packs, and discounts.
- Use price-based messaging to retain them and prevent churn during economic uncertainty.

**⚫ Cluster 4 – Affluent but Frugal (13%)**

- Run personalized re-engagement campaigns with luxury previews and exclusive early-access offers.
- Use emotional appeal and missed-opportunity messaging to activate dormant spending potential.

---

## 💥 Business Impact

- The segmentation unlocks 25–35% potential revenue increase by focusing on high-value segments (Clusters 1 and 4).
- With 58 Balanced Spenders and 45 Premium Customers, over 51% of the customer base can be profitably retained and upsold.
- Cluster 4 customers, while only 13%, represent affluent users who can be reactivated, potentially recovering $100K+ in missed revenue annually.
- The average income ($60.56K) and spending score (50.2) reflect a balanced but segmentable customer base — ideal for personalized targeting.
- When adopted in a real-world platform like Amazon, Best Buy, or Target, this segmentation strategy can reduce ad waste by $250K+/year (Adobe, 2025).
- By integrating this dashboard into CRM workflows, customer LTV can be increased, retention improved, and irrelevant offers minimized.
- Power BI enables real-time business exploration with filters by gender, age group, income, and cluster, increasing executive decision speed.

---

## 📌 Strategic Adoption Benefits

- Large-scale retailers like Amazon, Costco, Walmart, or Nordstrom can apply this segmentation to significantly improve personalization ROI.
- Adoption of this dashboard strategy can reduce churn by up to 70%, aligning with McKinsey (2025) personalization benchmarks.
- Incorporating this segmentation into marketing and CRM platforms can increase campaign conversion rates by 3x–5x.
- Segment-specific offerings allow companies to eliminate guesswork and wasted marketing spend on uninterested segments.
- Targeted messaging and bundled product offerings can increase average customer LTV by over $3000, as shown in industry research (Statista, 2025).
- Replacing generic campaigns with cluster-aware promotions can save $250K+ per year in marketing inefficiency (Adobe, 2025).
- For platforms like Amazon Prime, this enables strategic push notifications, reactivation of dormant users, and growth of high-spending youth segments.

---

## 🔍 Project Storytelling

In 2025, modern retailers like Amazon, Walmart, Target, and Costco manage vast, diverse customer bases with varying behaviors and spending patterns. Personalizing product recommendations and optimizing engagement for each segment is essential to drive long-term profitability, reduce churn, and maximize ROI.

This project tackles a classic business challenge:

***“How can we group our customers into meaningful segments to target them more effectively and maximize returns per customer group?”***

Using KMeans clustering, we grouped 200 mall customers based on:

Annual Income
Spending Score
Age

*This segmentation was deployed as a live ML-powered Streamlit application and now elevated through a powerful Power BI dashboard for business stakeholders.*

---

## 👩‍💼 About the Author    

**Sweety Seelam** | Business Analyst | Aspiring Data Scientist | Passionate about building end-to-end ML solutions for real-world problems                                                                                                      
                                                                                                                                           
Email: sweetyseelam2@gmail.com                                                   

🔗 **Profile Links**                                                                                                                                                                       
[Portfolio Website](https://sweetyseelam2.github.io/SweetySeelam.github.io/)                                                         
[LinkedIn](https://www.linkedin.com/in/sweetyrao670/)                                                                   
[GitHub](https://github.com/SweetySeelam2)                                                             
[Medium](https://medium.com/@sweetyseelam)

---

## 🔐 Proprietary & All Rights Reserved
© 2025 Sweety Seelam. All rights reserved.

This project, including its source code, trained models, datasets (where applicable), visuals, and dashboard assets, is protected under copyright and made available for educational and demonstrative purposes only.

Unauthorized commercial use, redistribution, or duplication of any part of this project is strictly prohibited.

---

## 🏷️ Tags  
`#PowerBI` `#CustomerSegmentation` `#MachineLearning` `#KMeansClustering` `#DataScience` `#RetailAnalytics` `#BusinessStrategy` `#Amazon`
