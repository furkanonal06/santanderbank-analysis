# Santander Bank Customer Analytics

## 1. Background and Overview

Customer churn is a critical concern for financial institutions as retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes Santander Bank's customer data to identify key churn drivers and segment customers based on behavioral and financial attributes. By leveraging machine learning and statistical methods, this study provides actionable insights for improving customer retention and engagement strategies.

## 2. Data Structure Overview

- **Source:** Publicly available dataset
- **Size:** Approximately 10,000 data points
- **Key Features:**
  - **Demographic Information:** Age, gender, geography
  - **Financial Metrics:** Credit score, balance, number of products, estimated salary
  - **Behavioral Indicators:** Tenure, activity status, credit card ownership
  - **Target Variable:** Churn status (Exited: 1, Retained: 0)
    
## 3. Methodology

1. **Data Preprocessing**  
   - Data cleaning and handling missing values
   - Feature engineering to enhance predictive power
   - Encoding categorical variables
   - Standardization and scaling for model efficiency

2. **Exploratory Data Analysis (EDA)**  
   - Descriptive statistics to summarize customer characteristics
   - Bivariate and multivariate analysis to identify relationships between variables
   - Advanced statistical techniques: Cramér’s V, Chi-square test, and Logistic Regression

3. **Customer Churn Prediction**  
   - Decision Tree analysis to identify key decision rules leading to churn
   - XGBoost model for high-accuracy churn prediction

4. **Customer Segmentation**  
   - K-Means clustering to group customers based on shared characteristics
   - Gaussian Mixture Models for probabilistic segmentation analysis

## 4. Executive Summary

This project applies **data preprocessing, exploratory data analysis, churn prediction modeling, and customer segmentation** to provide a holistic understanding of customer churn patterns.

### Key Findings:

- Credit card ownership has **little or no affect on chrun**.
- Customers who own **multiple banking products** tend to stay less.
- Age plays a critical role—**customers between 41-70 have the highest rate of churn**, indicates a need to target age specific interventions.
- **Inactive members** have a significantly higher churn probability as expected.
- As expected, customers with **low credit scores and high account balances** are more likely to churn.
- **Geographic Influence:** Customers from **Germany exhibit a significantly higher churn rate** compared to other regions, highlighting a need for targeted intervention.

### Models Applied:

- **Decision Tree:** Identified decision rules leading to churn.
- **XGBoost:** Achieved high-accuracy churn prediction.
- **K-Means Clustering:** Segmented customers into groups for tailored marketing strategies.

## 5. Insights Deep Dive

### Churn Analysis:

- **Churn Rate:** Approximately **21% of customers have left the bank**, signifying a critical need for retention strategies..
- **Age Factor:** **50% of customers fall within the 32-42 age range**, making them a key demographic for retention efforts.
- **Credit Score Impact:** Customers with a **credit score below 600** are twice as likely to churn compared to those with scores above 700.
- **Product Holding:** Customers with **1 or 2 products** are more likely to churn than those with diversified portfolios.
- **Geographic Influence:** Higher churn rates observed in certain regions, particularly among German customers.

### Customer Segmentation:

Based on K-Means clustering, **seven distinct customer segments** were identified:

1. **Young Loyal Customers in Spain** – Moderate churn risk but low profitability; potential for upselling.
2. **Low Engagement, Low Churn Risk** – Satisfied with minimal banking products; could be encouraged to engage more.
3. **German High-Churn Risk** – High-value customers with significant churn likelihood; targeted retention needed.
4. **High Activity, Low Risk Males** – Loyal male customers with consistent engagement; potential for advocacy.
5. **Moderate-Risk Balanced Customers** – Financially stable customers with occasional churn risk; steady relationship management required.
6. **Older High-Value, High-Risk Customers** – High net-worth individuals with multiple products but high churn risk; loyalty programs crucial.
7. **Older High-Churn Risk Professionals** – Professionals nearing exit; immediate engagement needed to retain them.

## 6. Recommendations

### Churn Reduction Strategies:

1. #### Personalized Retention Plans

   - Develop customized financial solutions based on customer profiles (e.g., low-interest loans for high-balance customers at risk of churn).
   - Offer targeted credit-building programs for customers with low credit scores.

2. #### Proactive Customer Engagement

   - Implement an AI-driven early warning system to detect disengagement signs and trigger personalized interventions.
   - Use predictive analytics to proactively contact at-risk customers with relevant offers before they consider leaving.

3. #### Loyalty & Incentive Programs

   - Introduce tiered loyalty rewards (e.g., bonus interest rates, fee waivers) for long-term customers or those using multiple products.
   - Launch exclusive perks for high-value customers in high-churn regions like Germany to reinforce brand loyalty.

4. #### Risk-Based Customer Support

   - Assign dedicated relationship managers to high-risk customer segments (e.g., Older High-Value, High-Risk Customers) to address their concerns directly.
   - Offer priority customer service to high-net-worth clients with a history of multiple product ownership.

5. #### Geography-Specific Churn Strategies

   - Investigate Germany’s higher churn rates by conducting localized surveys or focus groups to understand specific pain points.
   - Introduce localized financial products (e.g., region-specific investment options, customized mortgage plans) tailored to customer preferences.

6. #### Data-Driven Cross-Selling & Upselling

   - Target Young Loyal Customers in Spain with low-risk investment opportunities or higher-tier banking services to increase engagement.
   - Offer premium banking packages to high-balance, moderate-risk customers to deepen their relationship with the bank.

7. #### Product Portfolio Optimization

   - Analyze which products contribute to higher customer stickiness and restructure the portfolio to encourage long-term commitment.
   - Provide family or bundled financial plans to increase multi-account relationships within the same household.

### Next Steps:

- **Enhance customer segmentation** with hierarchical clustering for deeper insights.
- **Optimize churn prediction models** by fine-tuning hyperparameters.
- **Develop a dashboard** to visualize churn trends and real-time customer analytics.

## Tools & Technologies
- **Data Processing & Analysis:** pandas, numpy
- **Data Visualization:** seaborn, matplotlib
- **Statistical Analysis:** scipy, statsmodels
- **Machine Learning:** scikit-learn, xgboost, imbalanced-learn (SMOTE for handling class imbalance)

## Implementation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/santanderbank-analysis.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute the Jupyter Notebook:
   ```bash
   jupyter notebook preprocessing.ipynb
   ```
---

### Author

**Furkan Önal**\  
Data Science Professional | Predictive Analytics | Customer Insights

---

### Acknowledgments

- Santander Bank for providing the dataset
- Open-source contributors for developing the tools and frameworks utilized in this project

For inquiries, collaboration, or further discussions, feel free to reach out. 📩
