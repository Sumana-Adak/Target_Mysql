# Target_Mysql
# 🛒 Target Brazil E-commerce Analysis

## 📌 Project Overview
This project analyzes the e-commerce operations of Target in Brazil using a dataset of 100,000 orders placed between 2016 and 2018. The goal is to extract business insights and provide actionable recommendations to improve customer experience, logistics, and revenue performance.

---

## 🎯 Objectives
- Analyze order trends over time
- Identify customer distribution across states
- Evaluate delivery performance and delays
- Study payment behavior and installment trends
- Understand revenue and freight patterns

---

## 🗂️ Dataset Description
The dataset consists of 8 CSV files:

- customers
- orders
- order_items
- payments
- reviews
- products
- sellers
- geolocation

These datasets include information about customers, transactions, payments, delivery timelines, and product attributes.

---

## 🛠️ Tools & Technologies Used
- SQL / Bigquery (Data Analysis)
- CSV (Data Handling)

---

## 🔍 Key Analysis Performed

### 1. Exploratory Data Analysis
- Checked data types and structure of tables
- Identified time range of orders (2016–2018)
- Counted number of unique cities and states

---

### 2. Order Trends Analysis
- Year-wise growth in number of orders
- Monthly seasonality trends
- Peak order time (Morning / Afternoon / Night)

---

### 3. Regional Analysis
- Month-on-month orders across states
- Customer distribution by state

---

### 4. Revenue & Cost Analysis
- % increase in order cost (2017 vs 2018)
- Total & average order value by state
- Freight cost analysis by state

---

### 5. Delivery Performance Analysis
- Delivery time calculation:
  - time_to_deliver = order_delivered_customer_date - order_purchase_timestamp
  - diff_estimated_delivery = order_delivered_customer_date - order_estimated_delivery_date
- States with fastest and slowest delivery
- States with highest freight cost

---

### 6. Payment Analysis
- Monthly trend of payment types
- Orders based on installment usage

---

## 📊 Key Insights

- Orders showed a **consistent growth trend**, indicating expansion of e-commerce in Brazil
- Majority of orders were placed during the **afternoon and night**
- Certain states showed **higher delivery delays**, indicating logistics inefficiencies
- Freight costs varied significantly across states, impacting profitability
- Customers preferred **credit card payments with installments**

---

## 💡 Business Recommendations

- Improve logistics in high-delay states to enhance customer satisfaction
- Optimize freight pricing strategies for cost-heavy regions
- Focus marketing campaigns during peak ordering hours
- Encourage prepaid payment methods to reduce dependency on installments

---

## 📁 Project Structure
