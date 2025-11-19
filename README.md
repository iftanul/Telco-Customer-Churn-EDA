# Telco Customer Churn Analysis 📡📉  
*(This project is created as part of my Data Analysis learning portfolio.)*

---

## 🧠 Project Background  
Customer churn is a major issue for telecommunication companies, where customers may leave due to pricing, service experience, contract flexibility, or external competition.  
Understanding *why* customers churn helps companies design better retention strategies, improve service quality, and optimize customer lifetime value.

This project focuses on exploring the **Telco Customer Churn dataset** using Exploratory Data Analysis (EDA).  
The goal is to understand customer characteristics and service patterns that differentiate churned customers from those who stay.

---

## ❓ Problem Statement  
Telecom companies often struggle to identify which customers are most likely to leave.  
Without this understanding, they risk:

- Inefficient retention efforts  
- Wasted marketing budget  
- Losing customers to competitors  
- Poor service improvement prioritization  

This EDA aims to uncover patterns in customer profiles, billing behavior, and service usage that contribute to churn.

---

## 🎯 Goals  
- To understand customer profiles and service usage patterns  
- To analyze the characteristics of churn vs non-churn customers  
- To identify important features related to churn  
- To prepare insights that can support future predictive modeling  

---

## 🎯 Objective  
To perform an Exploratory Data Analysis on the customer churn dataset and reveal key factors that influence customer churn behavior.

---

## 📊 Dataset  
The dataset used in this project contains **7,043 customer records** with detailed information about:

- Customer demographics  
- Contract type  
- Service subscriptions  
- Billing information  
- Churn status  

Source: *Telco Customer Churn Dataset*

---

## 📄 Data Dictionary (Key Columns)
| Column | Description |
|-------|-------------|
| Gender | Customer gender |
| Senior Citizen | 1 = Yes, 0 = No |
| Partner | Whether the customer has a partner |
| Dependents | Whether the customer has dependents |
| Tenure Months | Number of months the customer has stayed |
| Phone Service | Phone service subscription |
| Internet Service | DSL / Fiber Optic / None |
| Tech Support | Technical support subscription |
| Contract | Month-to-month, One year, Two year |
| Paperless Billing | Whether billing is paperless |
| Payment Method | How the customer pays |
| Monthly Charges | Monthly bill amount |
| Total Charges | Total amount billed |
| Churn Label | Yes / No |
| Churn Value | 1 = churn, 0 = not churn |

---

## 🧹 Data Pre-Processing  
The following steps were performed in the notebook:

### ✔ Data Understanding  
- Reviewed column types  
- Identified unique identifiers  
- Analyzed variable categories  

### ✔ Data Cleaning  
- Checked for duplicates → *No duplicate rows found*  
- Checked and handled missing values  
- Fixed inconsistent data types (e.g., Total Charges)  

### ✔ Feature Reduction  
Some features were removed due to redundancy or low analytical value such as:  
- `CustomerID`  
- `Longitude`, `Latitude`, `Lat Long`  

### ✔ Preprocessing  
- Detection of missing values  
- Detection of outliers  
- Basic preparation before visualization  

---

## 📈 Analysis & Findings  
The notebook includes visual exploration of:

### **1. Churn by Contract Type**  
Month-to-month customers contribute the highest churn rate.

### **2. Churn by Payment Method**  
Electronic Check users show noticeably higher churn.

### **3. Churn by Internet Service**  
Fiber Optic customers churn more compared to DSL users.

### **4. Tenure Distribution**  
Churn is highest in customers who have short tenure.

### **5. Monthly Charges**  
Churning customers tend to have higher monthly charges.

All insights come *directly* from the notebook visualizations without additional interpretation.

---

## 🔑 Key Takeaways  
- Contract structure strongly influences customer retention  
- Payment method is an important indicator of churn risk  
- Internet service type correlates with churn behavior  
- Tenure is a critical factor—newer customers churn more  
- Billing amount also plays a role in customer churn  

These insights form a foundation for further modeling or business recommendations.

---

## 🙏 Thank You!  
This project demonstrates the EDA workflow for understanding churn behavior using real-world telecom data.  
The insights gained can support deeper modeling or business strategy development.

