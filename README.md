## Customer Churn Analysis and Prediction Using Power BI

## Project Overview

Customer retention is a critical challenge for telecommunications companies, where customer churn can significantly affect revenue, customer lifetime value, and long-term business growth. This project analyzes customer churn behavior using **Microsoft Power BI** to identify the demographic, contractual, payment, service, and behavioral factors associated with customer attrition.

Using a telecommunications dataset containing **7,043 customer records**, the project applies data cleaning, transformation, exploratory analysis, KPI development, data modeling, and interactive visualization techniques to transform raw customer data into actionable business intelligence.

The primary objective was to understand **who is churning, which services and customer characteristics are associated with higher churn, and what retention-focused strategies could be considered based on the observed patterns**.

## Dataset

The dataset contains information on **7,043 telecommunications customers** and includes variables covering:

* Customer demographics
* Customer tenure
* Contract type
* Payment method
* Internet service
* Monthly charges
* Total charges
* Partner and dependent status
* Customer churn status
* Other service-related attributes

##  Dashboard Analysis

The Power BI solution was structured around several analytical dimensions to provide a comprehensive view of customer churn.

### 1. Churn Rate Overview

The overview dashboard provides a high-level assessment of customer retention performance using KPI cards.

### Key KPIs

| Metric            | Result |
| ----------------- | -----: |
| Total Customers   |  7,043 |
| Churned Customers |  1,869 |
| Churn Rate        | 26.54% |

The analysis identified **1,869 churned customers**, representing **26.54%** of the customer base.

This establishes a significant customer-retention challenge and provides a baseline for examining the characteristics of customers associated with churn.

## Customer Demographic Analysis

The project examined customer demographics to determine whether characteristics such as gender, partner status, and dependent status were associated with differences in churn.

### Gender

Churn was relatively balanced between male and female customers:

* Male: **50.48%**
* Female: **49.52%**

The relatively small difference suggests that gender alone does not appear to explain a substantial portion of the observed churn pattern in this dataset.

### Partner Status

Customers without partners represented approximately **51.70%** of observed churn.

Customers with partners demonstrated comparatively lower churn patterns.

### Dependent Status

Customers without dependents represented approximately **48.13%** of churn.

These results suggest that household and family-related characteristics may be associated with customer retention behavior, although they should be interpreted alongside other customer and service attributes rather than treated as independent causal factors.

---

## Contract Type Analysis

Contract duration emerged as an important dimension of customer churn.

Observed churn rates included:

| Contract Type  | Churn Rate |
| -------------- | ---------: |
| Month-to-Month |     31.52% |
| One Year       |     18.56% |
| Two Year       |     23.38% |

Customers on **month-to-month contracts** displayed the highest observed churn rate at **31.52%**.

The analysis indicates a strong association between contract structure and customer retention. Customers with shorter contractual commitments may have greater flexibility to discontinue their services compared with customers operating under longer contracts

## Business Recommendations
The analysis suggests that management should pay particular attention to month-to-month customers, newer customers, fiber-optic users, customers with higher charges, and customers using electronic-check payments. These characteristics should be treated as risk indicators for further investigation rather than proof that they independently cause churn.

