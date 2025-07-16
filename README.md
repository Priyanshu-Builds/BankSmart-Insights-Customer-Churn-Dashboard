# BankSmart Insights: Customer Churn Dashboard

This Power BI report, titled **BankSmart Insights**, explores and visualizes customer churn patterns in a retail banking environment. It identifies key factors driving customer exit and supports data-driven retention strategies.

![Banking Domain - Customer Churb Analysis Report_Page_1](https://github.com/user-attachments/assets/a0ef08c0-ed7f-4488-b48e-5e31f4abf20d)

![Banking Domain - Customer Churb Analysis Report_Page_2](https://github.com/user-attachments/assets/04853ea3-2519-4515-aba5-4276cf67adcc)


## 📄 Project Overview

Customer churn negatively impacts bank revenues and customer lifetime value. **BankSmart Insights** is designed to analyze churn behavior and provide actionable intelligence to reduce attrition.

### 🏦 Business Objective

- Detect and visualize churn trends.
- Highlight key risk factors influencing churn.
- Enable targeted customer retention campaigns.

## 📊 Data Sources

The following data assets were analyzed:

- `CustomerInfo`
- `ActiveCustomer`
- `ExitCustomer`
- `CreditCard`
- `Gender`
- `Geography`
- `Bank_Churn`

## 📌 Key Attributes Considered

| Feature | Description |
|--------|-------------|
| `CreditScore` | High credit score = Lower churn risk |
| `Geography` | Region-specific churn patterns |
| `Gender` | Analyzed for demographic relevance |
| `Age` | Older customers are more stable |
| `Tenure` | Years with the bank (loyalty indicator) |
| `Balance` | Higher balance = More retained |
| `NumOfProducts` | More products → lower churn |
| `HasCrCard` | Credit card ownership correlation |
| `IsActiveMember` | Strong churn signal |
| `EstimatedSalary` | Compared with balance |
| `Exited` | 1 = Churned, 0 = Retained |
| `Bank DOJ` | Used for tenure evaluation |

## 🧠 Insights Derived

- Customers under 35 are **twice as likely to churn**.
- **Inactive members** show a **60% churn rate**.
- **High-balance** customers remain more loyal.
- Regions with lower product adoption correlate with high churn.
- Having multiple bank products improves retention likelihood.

## 📈 Visuals Included

- Age vs Churn Rate
- Geographic Churn Heatmap
- Product Count & Churn
- Active vs Inactive Members
- Salary vs Balance Clustering

## 🔧 Tools Used

- Power BI Desktop
- DAX
- Power Query Editor
- Excel (for data preprocessing)

## 📁 Files Included

- `BankSmart_ChurnDashboard.pbix` – Power BI report
- `BankSmart_BusinessRequirementDocument.docx` – Requirements doc
- `dataset.csv` – Sample cleaned dataset
- `visuals/` – Screenshots of report pages

## 📬 Contact

For questions or suggestions, feel free to connect and raise an issue on this GitHub repository.

---

