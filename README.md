# 🏪 Store Analysis Dashboard (Power BI)

This project is a **Power BI dashboard** designed to analyze store sales, outlet performance, and customer trends based on two months of data.  
The goal of this project is to provide actionable insights for decision-makers by identifying top-selling items, payment trends, outlet performance, discount strategies, and more.  

---

## 📂 Dataset Details

The dataset consisted of multiple Excel sheets:  
- **Complimentary Food Items** – Details of complimentary orders given to customers.  
- **Discount Details** – Information about receipt-level and campaign-based discounts.  
- **Hourly Sales** – Sales data broken down by hour.  
- **Menu Item Sales & Summary** – Detailed and summarized menu-level sales data.  
- **Payment Details** – Breakdown of payment methods (cash vs. card).  
- **Sales Summary (Multiple Outlets)** – Outlet-wise total sales and performance summary.  
- **Top-Selling Items** – Items driving major revenue.  
- **Void Items & Orders** – Cancelled or voided transactions and reasons.  

All these sheets were **modeled and connected** in Power BI to create a robust star schema for reporting.  
📌 [🔗 View Data Model](https://github.com/divyamehulmakwana-bit/Store-Analysis-using-PowerBi/blob/main/Screenshots/Model.png)  

---

## 📊 Dashboard Pages & Features

### 🔹 Page 1 – Sales Overview
A high-level summary of sales performance:  
- 🥇 **Most Popular Item:** Beef Steak  
- 💰 **Total Sales:** \$240K  
- 🧾 **Average Spend per Customer:** \$29.66K  
- 📅 **Busiest Day:** Friday  
- 📈 **Visuals:**  
  - Column Chart: Sales by day of the week (Fri & Thu leading).  
  - Donut Chart: Payment method breakdown (82% card, 18% cash).  
  - Donut Chart: Discount type distribution (66.6% receipt discount).  
  - Line Chart: Sales over time with **forecasting feature** applied.  
  - Ribbon Chart: Top-selling items (Beef Steak on top).  

📌 [🔗 View Page 1](https://github.com/divyamehulmakwana-bit/Store-Analysis-using-PowerBi/blob/main/Screenshots/Page%201.png)  

---

### 🔹 Page 2 – Product Insights
A deeper look into item-level performance:  
- Bar Chart: **Most popular items**.  
- Line Chart: **Card vs. Cash payments over time**.  
- Bar Chart: **Least sold items**.  
- Table: **Discount details**.  
- Table: **Complimentary order details**.  

📌 [🔗 View Page 2](https://github.com/divyamehulmakwana-bit/Store-Analysis-using-PowerBi/blob/main/Screenshots/Page%202.png)  

---

### 🔹 Page 3 – Outlet & Operational Analysis
Outlet-wise and operational performance summary:  
- 📍 **KPIs:** Best performing outlet, best hour, best month, and most common void reason.  
- 📊 **Visuals:**  
  - Clustered Bar Chart: Sales by outlet.  
  - Table: Void order/item details.  
  - Bar Chart: Average sales by hour.  
  - Line Chart: Average monthly sales trend.  

📌 [🔗 View Page 3](https://github.com/divyamehulmakwana-bit/Store-Analysis-using-PowerBi/blob/main/Screenshots/Page%203.png)  

---

## 🔑 Key Insights
- Friday and Thursday were the **busiest sales days**.  
- **Card payments dominated** with 82% of transactions.  
- The **Receipt Discount** was the most widely used promotion.  
- Beef Steak consistently topped the menu as the **most popular item**.  
- Clear trends in hourly and monthly performance, allowing better staffing and inventory planning.  

---

## 🛠️ Tools Used
- **Power BI** – Dashboard development & data modeling.  
- **Excel** – Raw data storage and cleaning.  

---

