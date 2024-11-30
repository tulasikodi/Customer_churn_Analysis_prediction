# Customer_churn_Analysis_Prediction
## 1. Project Overview

The company operates in the telecommunications industry and has been active for several years. Its business model revolves around subscription-based services, including device protection plans and data services. The company tracks customer behavior using predictive analytics and churn data to improve customer retention.

##### Insights and recommedation are provided on the following key areas:

**Churn Reasons Analysis:**    Identifying the primary factors contributing to customer churn.

**Churn Trends by Age Group:**    Understanding how churn rates differ across different age groups.

**Churn Trends by Tenure:**    Analyzing how the length of customer relationships correlates with churn rates.

**Impact of Device Protection Plans:** Investigating how device protection influences churn rates.



##  Data Model View

The data model is designed to analyze customer churn, leveraging multiple tables that store customer data, service details, and predictive analytics. The model consists of core tables, mapping tables, and a predictions table, and is structured to facilitate churn-related analyses.

![image](https://github.com/user-attachments/assets/7a4f78d3-01aa-4f68-a89b-1858d240990f)

## Executive Summary
### Overview of Findings
The churn analysis  highlights significant patterns in customer behavior, showing that certain customer segments are at a higher risk of churn.
There are critical insights into customer characteristics and factors driving churn, which can guide targeted retention strategies.
The key performance indicators are has shown 27% churn rate  1732 customers are churned with 6418 total customers and 411 new joiners. 

Below is the overview page from the power Bi dashboard and more examples are there thoughout the report . The entire interactive dashboard can  download here

![image](https://github.com/user-attachments/assets/c960f8d0-f62a-443c-b97e-f1961c5fec32)

**Churn Reasons Analysis** Identifying the Primary Factors Contributing to Customer Churn

- **Competitor had better devices** :  289 customers left because **they found better devices with competitors.** This shows that when your competitors offer superior products, it’s a tough battle to keep customers satisfied and engaged. But, it's not just about the product.
- **Competitor's Better Offer:**  274 customers churned because **competitors made a better offer** — whether it was a more attractive deal or a promotional price. In today’s competitive market, customers are constantly looking for the best value, and if they find it elsewhere, they won’t hesitate to switch.
- **Attitude of Support Staff:**  208 customers cited poor experiences with the **attitude of support staff** as their reason for leaving.
  his underlines a crucial insight: no matter how good your product is, the customer experience must be seamless and pleasant. If customers feel neglected or disrespected, they are likely to walk away, even if the product itself is strong.
- **Uncertainty ("Don't Know"):**   124 customers couldn't pinpoint why they left. This points to deeper issues—perhaps a **lack of engagement, unclear communication, or unnoticed dissatisfaction.**
- **Competitor Offering More Data:** 106 customers churned because **competitors offered more data**, highlighting that valuable perks, like better data plans, play a significant role in retaining customers in a market driven by connectivity and digital services.
![image](https://github.com/user-attachments/assets/0a74391e-38b8-463e-bd15-b83a1bb00397)

  





## 4. Problem Statement
#### Businesses often face the challenge of high churn rates, leading to revenue loss and increased customer acquisition costs.

### Key Questions Addressed:
#### What patterns exist among customers who churn?
#### How can we predict customers likely to churn?
#### What strategies can reduce churn and improve retention?

## 5. Executive Summary
The analysis revealed the following key insights:

Churn Rate: 27% of customers churned out of 6,418 total customers.
Demographics:
64.15% of churned customers were male.

Churn rates were highest among customers aged 25–35.

Services Used:
Customers using Fiber Optic Internet had the highest churn rate (41%).

Customers not using online security services were more likely to churn.

Geographical Trends:
States such as Jammu and Assam exhibited higher churn rates (57% and 38%, respectively). A predictive model was developed to identify at-risk customers, achieving an accuracy of 90%.

6. Insights
What We Did:
Data Cleaning:
Removed duplicates and handled missing values.

Standardized column names for consistency.

Exploratory Data Analysis (EDA):
Created visualizations to understand demographic, geographical, and service-based churn trends.

Used bar charts and pie charts to explore churn rates across different features.

Churn Prediction Model:
Applied logistic regression and decision trees to predict churn.

Validated the model using accuracy, precision, and recall.

Dashboard Creation:
Designed an interactive Power BI dashboard summarizing all insights.
