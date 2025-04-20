# 📊 BSNL_Customer_Churn_Analysis

## 📌 Project Overview  
BSNL launched its Business Broadcast Plans two years ago to support enterprises, influencers. Recently, a drop in user retention raised concerns about customer engagement and satisfaction.

This project focuses on understanding **customer churn patterns** through a comprehensive analysis of user activity and demographics. The primary goal is to uncover insights that can help BSNL reduce churn and enhance customer loyalty using simple Excel-based techniques.

---

## 🗃️ Database Information  

The dataset used in this project is titled **`Data_CustomerChurn`**, and it contains the following columns:

- **CustomerID**: Unique identifier for each customer  
- **CustomerType**: Category of customer – *Entrepreneur*, *Influencer*, or *Startup*  
- **Stage**: Business development stage – *Emerging (0)* or *Established (1)*  
- **Tenure**: Number of months the customer has been using the service  
- **Plan**: Subscription type – *Month-to-Month*, *Half-Yearly*, or *Annual*  
- **PaymentMethod**: UPI, Debit Card, or Credit Card  
- **MonthlyCharges**: Charges billed last month  
- **TotalCharges**: Total charges paid by the customer to date  
- **Churn**: Whether the customer left the service (*Yes*) or remained (*No*)

📁 **[https://github.com/rashi12121/BSNL_Customer_Churn_Analysis/blob/main/BSNL_Data.csv]**

---

## ❓ Questions to Answer

1. Does tenure affect the customer churn rate?
2. Which plan type has the highest and lowest churn rates?
3. Do different customer types (Entrepreneur, Influencer, Startup) show varying churn behaviors?
4. How does churn vary between Emerging and Established business stages?

---

## 📊 EDA & Visualization  

Analysis was performed using **Microsoft Excel**, including:

- Pivot tables for summarizing churn by tenure, customer type, plan type, and business stage  
- Bar charts and conditional formatting to highlight trends  
- Slicers for filtering dashboard elements  
- Interactive dashboard elements for:
  - Active vs Inactive Customers  
  - Tenure-wise Churn Rate  
  - Customer Type Churn Rate  
  - Plan-wise Churn Rate  
  - Stage-wise Churn Rate  

> 🖼️ Dashboard

![Break-even Dashboard](https://github.com/rashi12121/BSNL_Customer_Churn_Analysis/blob/main/BSNL_Dashboard.png)

---

## 🔍 Key Insights

### 📈 Tenure vs Churn Rate
- Churn is highest in the **first 3 months**, with churn rates over **50%**.
- Churn rate significantly drops after **6 months**, and falls below **10%** after the **20th month**.
- Customers staying more than a year are **more likely to remain loyal**.

### 📦 Plan Type Churn
| Plan             | Churn Rate |
|------------------|------------|
| Month-to-Month   | **54.44%** |
| Half-Yearly      | 37.20%     |
| Annual           | **25.29%** |

- **Annual plans** have the lowest churn rate. Month-to-month customers are the most likely to leave.

### 👥 Customer Type Churn
| Customer Type | Churn Rate |
|---------------|------------|
| Influencer    | **77.92%** |
| Entrepreneur  | 34.47%     |
| Startup       | **5.61%**  |

- **Influencers churn the most**, possibly due to their dynamic needs or lack of long-term value.
- **Startups show the highest loyalty** with minimal churn.

### 🏢 Business Stage Churn
| Stage       | Churn Rate |
|-------------|------------|
| Emerging (0) | 31.38%     |
| Established (1) | **48.27%** |

- Surprisingly, **established businesses have a higher churn rate**, indicating a need for better retention strategies even among long-term users.

---

## 🛠️ Tools Used

- **Microsoft Excel** for:
  - Data Cleaning & Transformation  
  - Pivot Table Creation  
  - Charting and Conditional Formatting  
  - Interactive Dashboards

---

## 📎 Resources

- 📁 **Dataset Link**: [Paste dataset link here]  
- 🖼️ **Dashboard Snapshot**: [Paste dashboard image here]

---

Let me know if you want me to help you design the dashboard layout or export it to a PDF or PPT format!

