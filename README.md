# -Analysis-of-Subscription-Based-Businesses-A-Netflix-Case-Study

This repository contains the capstone project for the Master of Business Administration (MBA) in Business Analytics, focusing on the analysis of subscription-based business models through a Netflix case study. The project explores key factors influencing customer retention and churn, utilizing data analysis and machine learning techniques to provide actionable insights.

# 1. Problem Statement
The subscription-based streaming industry faces significant challenges with customer churn due to market saturation, intense competition, and evolving consumer behavior. This study addresses the high attrition rate affecting Netflix by identifying the key factors that contribute to customer churn and exploring how data-driven strategies can improve user loyalty and retention.



# 2. Objectives
The primary goals of this study are:


Evaluate Key Metrics: Investigate business indicators such as Monthly Recurring Revenue (MRR), Customer Acquisition Cost (CAC), Customer Lifetime Value (CLV), and churn rate.


Understand Customer Behaviour: Analyze user engagement patterns to identify factors leading to customer retention or churn.


Predict Churn Rate: Apply machine learning models to forecast customer attrition and provide actionable insights.


Optimize Revenue Strategies: Explore pricing models and customer segmentation to enhance business profitability.

# 3. Dataset
The analysis is based on a Netflix user dataset containing 2,500 records over a five-month period. The dataset includes the following features:



User Demographics: Age, Gender, Country.


Subscription Details: Plan type (Basic, Standard, Premium), Join Date, Payment Method.



Engagement Metrics: Watch time and device usage.


Customer Tenure & Churn Status: Subscription duration and cancellation history.

# 4. Methodology
The project follows a quantitative, data-driven approach involving several stages:

Data Pre-processing: The dataset was cleaned by handling missing values, correcting data types, and removing duplicates. New features like 

Subscription Duration were engineered to support the analysis.



Exploratory Data Analysis (EDA): EDA was performed to uncover patterns in customer behavior, subscription types, and churn rates across different demographics and regions. Visualizations such as bar charts, heatmaps, and geographic plots were used to interpret the data.




Predictive Modeling: Supervised machine learning models were implemented to predict customer churn. The models used include:

Logistic Regression 



Random Forest 


XGBoost (Extreme Gradient Boosting) 

Model performance was evaluated using metrics like Accuracy, Precision, Recall, and F1-Score.


Customer Segmentation: K-Means Clustering was used to group users into distinct segments based on engagement and tenure, allowing for targeted retention strategies.


# 5. Key Findings

High Churn Rate: The analysis revealed a significant churn rate of 66.96%, indicating a major retention issue for the business.


Engagement is Crucial: Low user engagement (watch time) was identified as the strongest predictor of churn. Users with fewer watch time minutes per month were more likely to cancel their subscriptions.




Subscription Plan Matters: Basic plan subscribers had lower engagement and were twice as likely to churn compared to Premium users.




Tenure Affects Loyalty: Users with a tenure of less than 12 months had a higher churn risk, while long-term users (20+ months) were more stable and loyal.



Model Performance: The XGBoost model achieved the highest accuracy (85-90%) in predicting customer churn, making it the most reliable model for identifying at-risk users. The Logistic Regression model achieved an accuracy of about 64%.




# 6. Key Visualizations
The project includes several visualizations to present the findings, such as:


User Distribution by Country: An interactive world map showing the geographic concentration of Netflix users.


Churn Rate by Subscription Type: A bar chart comparing churn rates across Basic, Standard, and Premium plans.


MRR by Subscription Type: A bar chart illustrating the monthly recurring revenue generated from each subscription tier.


Confusion Matrix: A heatmap to evaluate the performance of the Logistic Regression prediction model.

# 7. Recommendations
Based on the analysis, the following strategies are recommended to reduce churn and improve retention:


Enhance Customer Engagement: Use AI-driven algorithms for highly personalized content recommendations and introduce interactive features like rewards or watch parties to increase watch time.


Optimize Pricing and Plans: Introduce an ad-supported tier for price-sensitive users and offer incentives for Basic users to upgrade to higher-tier plans.



Targeted Retention Campaigns: Develop early engagement strategies for new users (<6 months) and launch re-engagement campaigns with special offers for inactive or at-risk users.


# 8. Technologies Used
Language: Python

Libraries:

Pandas 

NumPy 

Matplotlib 

Seaborn 

Scikit-learn (for Logistic Regression, Random Forest, etc.) 

XGBoost
