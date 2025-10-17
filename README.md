<h1> Data-Driven Marketing Optimization for Supermarket Customers </h1>

## 1. Project Overview
This project focuses on analyzing supermarket customer data to gain actionable business insights. The goal is to understand customer purchasing behavior, segment customers based on demographics and spending patterns, and optimize marketing strategies through data-driven decision-making
#### Business Objectives:
- Identify and understand distinct customer segments based on demographics, behavior, and spending.
- Evaluate the effectiveness of marketing campaigns across different customer segments
- Calculate and analyze **Customer Lifetime Value (CLV)** to identify and retain high-value customers.
- Explore relationships between customer satisfaction, complaints, and purchasing behavior
- Provide data-backed recommendations for marketing optimization and customer retention

#### Key Objectives:
- Objective 1: Segment customers using demographic and behavioral features (Age, Income, Education, Purchase Frequency).
- Objective 2: Calculate CLV and identify high-value customer segments.
- Objective 3: Analyze marketing campaign responses and customer satisfaction levels.
- Objective 4: Discover correlations between demographics and purchasing preferences.
- Objective 5: Develop actionable strategies for retention, upselling, and personalized marketing.

## 2. Data Sources
- [Supermarket Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) - Contains information about supermarket customers, including demographics, income, product spending, web/store visits, and marketing responses from Jul 2012 until Jun 2014.

## 3. Technologies Used
- Programming Language: Python (Pandas, NumPy, SciPy, scikit-learn)
- Visualization: Matplotlib, Seaborn, Plotly
- Statistical Analysis: Spearman correlation, Chi-square test, Correlation Ratio (η), Kolmogorov-Smirnov test
- Clustering & Modeling: K-Means Clustering, Silhouette Score
- Interactive Dashboard: Looker Studio
- Version Control: GitHub
- Development Environment: Jupyter Notebook, Visual Studio Code

## 4. Project Structure

```
├── README.md                      <- Project documentation (you are here)
│
├── data
│   ├── Supermarket Customers.csv  <- Original Kaggle dataset
│
├── notebooks
│   ├── main.ipynb
│
└── reports
    ├── dashboard.txt               <- Link to looker studio for interactive dashboard
    ├── slides.txt                  <- Link to canva for business presentation

```

## 5. Summary of Finding
### 5.1 Business Insight
- Customer Segmentation (K=3)
  - Segment 0: Price-sensitive adults with low income and low total spending.
  - Segment 1: Moderate-income seniors — consistent but average spenders with low campaign response.
  - Segment 2: High-income, mature or senior customers — high CLV, frequent campaign responders, and premium product buyers.
- Marketing Campaign Effectiveness
  - Segment 2 customers had the highest campaign acceptance rates
  - Campaign 1 and Campaign 5 specifically attracts segment 2
  - Campaign 3, Campaign 4, and Campaign 6 attracts all segment equally
  - All Campaigns have similar total participant except Campaigns 2, the most ineffective overall, with the very low total paricipant compared to the rest.
- Customer Lifetime Value (CLV)
  - CLV was strongly correlated with income, total spending, and number of campaigns accepted.
  - High-CLV customers showed higher purchase frequency across multiple channels (web, catalog, and store).
- Customer Satisfaction & Complaint
  - Customers who filed complaints tended to have lower total spend and fewer accepted campaigns.
  - There’s no statistic correlation between complaints and product spending, indicating complaints are more-likely about service quality.
- Purchasing Behavior Trends
  - Wines and meat are the top contributing categories to total spend (77% shares combined)
  - Strong correlation between product spending and purchase channels (web/catalog/store), indicating omnichannel customers contribute most to revenue.
### 5.2 Actionable Recommendation
- Target High-income (Segment 2) with personalized promotions, like VIP programs — they show the highest CLV and campaign engagement.
- Strengthen Brand loyalty among medium-income (Segment 1) by introducing loyalty program and affordable bundles - this group frequently visits the website but shows lower participation in marketing campaigns. 
- Re-engage low-income customers (Segment 0) with limited time discount and online-cheap deals o encourage repeat purchases and improve retention, given their relatively high online activity levels.
- Introduce feedback loops for customers who submitted complaints to prevent churn.
- Focus marketing spend on channels with strong product-channel correlations (web campaigns for wine/meat buyers).
## 6. Contact
- Name     : Ferdio Giffary
- Email    : ferdiogiffary@gmail.com
- Linkedin : linkedin.com/in/ferdiogiffary/
