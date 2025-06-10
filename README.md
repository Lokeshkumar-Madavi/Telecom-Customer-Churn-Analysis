# Telecom Customer Churn Analysis

## Objective
The primary objective of this project is to analyze customer churn in the telecom industry and identify the key factors that influence customer retention or departure. By understanding these trends, the goal is to offer actionable insights for improving customer loyalty and reducing churn.

---

## Data Structure
The dataset consists of various customer attributes, covering demographic information, account details, and service usage. Below are the key columns:

- **customerID**: Unique identifier for each customer  
- **gender**: Customer gender (Male/Female)  
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1 = Yes, 0 = No)  
- **Partner**: Whether the customer has a partner  
- **Dependents**: Whether the customer has dependents  
- **tenure**: Number of months the customer has stayed with the company  
- **PhoneService**: Whether the customer has a phone service  
- **MultipleLines**: Whether the customer has multiple lines  
- **InternetService**: Type of internet service (DSL, Fiber optic, No)  
- **OnlineSecurity**: Whether the customer has online security  
- **OnlineBackup**: Whether the customer has online backup  
- **DeviceProtection**: Whether the customer has device protection  
- **TechSupport**: Whether the customer has tech support  
- **StreamingTV**: Whether the customer uses streaming TV service  
- **StreamingMovies**: Whether the customer uses streaming movie service  
- **Contract**: Type of contract (Month-to-month, One year, Two year)  
- **PaperlessBilling**: Indicates if billing is paperless  
- **PaymentMethod**: Payment method used by the customer  
- **MonthlyCharges**: Monthly billing amount  
- **TotalCharges**: Total charges to date  
- **Churn**: Whether the customer has churned (Yes/No)  

---

## Tools Used
- Microsoft Excel (initial data review)
- Python (for data processing and analysis)
- Libraries:
  - `NumPy` – numerical operations
  - `Pandas` – data manipulation
  - `Matplotlib` & `Seaborn` – data visualization

---

## Executive Summary

 In-Depth Customer Churn Analysis
This analysis provides a comprehensive review of customer churn behavior, using demographic data, service preferences, and contract details. A series of well-designed charts helped uncover key trends and high-risk segments.

### 1. Churn Rate Overview
26.54% of the customer base has churned.

This translates to roughly 1 in 4 customers discontinuing service, indicating a considerable churn challenge that requires strategic focus.

### 2. Senior Citizens and Churn
Among senior citizens, churn rates were significantly higher compared to non-senior customers.

While only a small proportion of total customers fall in this category, the churn rate among them exceeds 40%, suggesting this group experiences unmet needs or dissatisfaction.

### 3. Tenure and Loyalty
Customers with 1–2 months of tenure account for a disproportionately high share of churned users—over 50% of those who churned left within the first 2 months.

In contrast, customers with a tenure of more than 12 months showed significantly higher retention rates (churn rates under 15%), emphasizing the need for improved onboarding and engagement in the early months.

### 4. Contract Type Effect
Customers on month-to-month contracts had the highest churn rate at 43%.

Those on one-year contracts showed a churn rate of 11%, and two-year contracts had the lowest at just 3.5%.

This reveals that longer-term contracts are a strong churn deterrent and can be a lever for retention.

### 5. Influence of Additional Services
Customers not subscribed to OnlineSecurity, TechSupport, or DeviceProtection showed churn rates as high as 45–55%.

In contrast, those with these services enabled churned at much lower rates—often under 20%.

Suggests a strong correlation between bundled value-added services and customer satisfaction.

- 5.1 Internet & Streaming Services

  * Customers using Fiber optic internet had a higher churn rate (~30%) compared to those using DSL or No Internet, possibly due to service expectations or pricing.

   * Similarly, customers subscribed to both StreamingTV and StreamingMovies showed churn rates over 35%, suggesting that upselling entertainment may not always lead to loyalty.

- 5.2 Phone and Backup Services
   * Churn among customers with PhoneService was significantly lower at around 20%.

   * Similarly, OnlineBackup users showed a churn rate of less than 18%.

   * These features appear to offer stability and may play a retention-enhancing role.

---

## Recommendations

1. **Improve early engagement**: Focus on customers in their first 2–3 months to reduce early churn through onboarding calls, welcome offers, or check-ins.
2. **Promote long-term contracts**: Offer incentives for 1-year or 2-year contracts to reduce churn risk.
3. **Bundle essential services**: Upsell value-added features like OnlineSecurity, TechSupport, and OnlineBackup.
4. **Target senior citizens**: Provide customized service plans and dedicated support for older customers.
5. **Monitor fiber optic users**: Investigate churn reasons (e.g., pricing, service issues) among fiber optic users and heavy streamers.

---

