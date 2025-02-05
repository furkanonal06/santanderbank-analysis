# Santander Bank Customer Analytics

## Project Overview
This project presents a comprehensive data science analysis aimed at **predicting customer churn** and **segmenting customers** within the Santander Bank dataset. By employing advanced statistical techniques and machine learning models, this analysis provides data-driven insights to support customer retention strategies and targeted business decision-making.

## Dataset
- **Source:** Publicly available dataset
- **Size:** Approximately 10,000 data points
- **Objective:** Identify key factors influencing customer churn and segment customers based on behavioral and financial attributes.

## Methodology

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

## Key Insights & Business Implications
- Customers with **lower credit scores, higher balances, and multiple products** exhibit a higher churn probability.
- Cluster analysis identifies distinct customer segments, enabling personalized marketing strategies.
- Decision Tree models uncover actionable rules that explain churn behaviors.
- XGBoost provides a robust predictive framework with superior accuracy.
- Approximately **21% of customers have left the bank**, signifying a critical need for retention strategies.
- **50% of customers fall within the 32-42 age range**, a key demographic for retention planning.

## Future Enhancements
- Expanding segmentation analysis with hierarchical clustering and DBSCAN for improved accuracy.
- Refining predictive models through hyperparameter tuning and ensemble learning techniques.
- Developing an interactive dashboard for real-time churn prediction and customer analysis.

---

### Author
**Furkan Önal**  
Data Science Professional | Predictive Analytics | Customer Insights

---

### Acknowledgments
- Santander Bank for providing the dataset
- Open-source contributors for developing the tools and frameworks utilized in this project

For inquiries, collaboration, or further discussions, feel free to reach out! 📩

