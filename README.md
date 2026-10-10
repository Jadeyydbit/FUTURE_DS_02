##Customer Retention & Churn Analysis

#Project Overview

Customer churn is an important challenge for subscription-based businesses. Understanding why customers leave, which customer segments are more likely to churn, and how customer retention varies can help businesses make better decisions.

This project analyzes a telecommunications customer churn dataset using Power Query and Microsoft Power BI. The objective is to identify churn patterns, investigate potential churn drivers, explore customer tenure and billing behavior, and develop actionable recommendations to improve customer retention.

#Project Objectives

Clean and prepare customer subscription data for analysis.

Calculate key customer retention and churn KPIs.

Analyze churn across contract types, payment methods, internet services, and online security subscriptions.

Examine customer tenure and monthly billing patterns.

Identify customer segments that may require additional retention attention.

Present findings through an interactive, multi-page Power BI dashboard.

#Tools & Technologies

Microsoft Excel — initial data inspection and cleaning.

Power Query — data transformation and preparation.

Microsoft Power BI — data modeling, DAX measures, visualizations, and interactive dashboard development.

DAX — KPI calculations and tenure-group classification.

#Dataset

The project uses a telecommunications customer churn dataset containing customer demographics, subscription services, contract details, payment methods, tenure, monthly charges, total charges, and churn status.

#Key fields include:

customerID — unique customer identifier.

tenure — number of months the customer has stayed.

Contract — customer contract type.

PaymentMethod — customer payment method.

InternetService — type of internet service.

OnlineSecurity — online security subscription status.

MonthlyCharges — recurring monthly charges.

TotalCharges — total charges recorded for the customer.

Churn — whether the customer has left the service.

#Data Cleaning & Preparation

The dataset was inspected and prepared before visualization.

The preparation process included:

Checking for missing values and duplicate customer records.

Converting the SeniorCitizen field from numeric codes to readable Yes/No categories.

Reviewing numeric data types for tenure and charge fields.

Preserving meaningful categories such as No phone service and No internet service.

Creating tenure groups to compare customers across different stages of their customer lifetime.

Preparing the cleaned dataset for use in Power BI.

Dashboard Pages

#1. Executive Retention Overview

Provides a high-level summary of customer retention and churn.

#KPIs included:

Total Customers

Churned Customers

Churn Rate

Retained Customers

Retention Rate

Average Tenure

#Visualizations:

Customer Count by Contract Type & Churn Status

Customer Count by Tenure Group & Churn Status

Churn Rate by Tenure Group

Customer Count by Internet Service & Churn Status

#2. Churn Drivers

Explores how churn rates vary across subscription and billing characteristics.

#Visualizations:

Churn Rate by Contract Type

Churn Rate by Payment Method

Churn Rate by Internet Service

Churn Rate by Online Security

#3. Customer Lifetime & Retention

Examines customer tenure and billing behavior to identify patterns relevant to retention.

#Visualizations:

Customer Count by Tenure Group

Average Monthly Charges by Tenure Group

Average Monthly Charges: Churned vs Retained

Churn Rate by Paperless Billing

Key Findings

The dashboard highlights the following patterns in the analyzed dataset:

Overall churn rate: 26.54%.

Overall retention rate: 73.46%.

Contract type: Month-to-month customers have a churn rate of 42.7%, compared with 11.3% for one-year contracts and 2.8% for two-year contracts.

Payment method: Customers using electronic checks have the highest observed churn rate at 45.3%.

Internet service: Fiber-optic customers have a churn rate of 41.9%, compared with 19.0% for DSL customers.

Online security: Customers without online security have a churn rate of 41.8%, compared with 14.6% among customers with online security.

Customer billing: Average monthly charges are higher among churned customers than retained customers in this dataset.

These findings indicate associations between customer characteristics and churn. They do not, by themselves, prove that any particular characteristic causes a customer to leave.

#Business Recommendations

Based on the observed patterns, the following actions could be investigated:

Strengthen month-to-month retention: Test loyalty benefits, renewal incentives, and suitable longer-term plans for customers at risk of leaving.

Improve early customer engagement: Introduce onboarding support and proactive check-ins for new customers during their first year.

Investigate electronic-check churn: Review payment-related customer feedback, failed payments, and billing experiences before changing payment policies.

Review fiber-optic customer experience: Investigate service quality, pricing, installation experience, and customer support for fiber-optic subscribers.

Evaluate service bundles: Test whether relevant add-on services, including online security, improve customer satisfaction and retention.

Monitor higher-billing customers: Examine whether higher monthly charges are associated with dissatisfaction or perceived value, and test targeted offers where appropriate.

Recommendations should be validated through customer feedback, further analysis, and controlled retention experiments where possible.

#Repository Structure

Customer-Retention-Churn-Analysis/
│
├── README.md
├── telco_customer_churn_cleaned.csv
├── Customer_Retention_Churn_Dashboard.pbix
│
└── screenshots/
    ├── executive-retention-overview.png
    ├── churn-drivers.png
    └── customer-lifetime-retention.png

#How to View the Project

Clone or download this repository.

Open Customer_Retention_Churn_Dashboard.pbix using Microsoft Power BI Desktop.

If prompted, update the data source path to the location of telco_customer_churn_cleaned.csv.

Refresh the data if required.

Navigate through the three report pages to explore the dashboard.

Dashboard screenshots are available in the screenshots/ folder for a quick preview.

Project Deliverables

Cleaned customer churn dataset.

Interactive Power BI dashboard with three report pages.

KPI calculations and customer tenure segmentation.

Churn analysis and business recommendations.

#Author

Jaden Fernandes

Data Analytics Project | Future Interns — Data Science & Analytics, Task 2
