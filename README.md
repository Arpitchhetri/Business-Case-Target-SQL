# 🛒 Target Brazil E-Commerce SQL Case Study

This project is a comprehensive SQL-based analysis of Target’s e-commerce operations in Brazil from 2016 to 2018. Using a dataset of over 100,000 orders across 8 interrelated tables, the analysis dives deep into customer behavior, order trends, delivery performance, freight charges, and payment methods.

---

## 📁 Dataset Overview

The dataset includes the following files:

- `customers.csv` – Customer demographics and locations  
- `sellers.csv` – Seller details and states  
- `order_items.csv` – Item-level pricing and freight info  
- `orders.csv` – Order status and delivery timestamps  
- `payments.csv` – Payment types, values, and installments  
- `reviews.csv` – Customer ratings and feedback  
- `products.csv` – Product category and dimensions  
- `geolocation.csv` – Zip-code level geo-coordinates  

---

## 🎯 Key Business Questions

- What are the ordering trends over time? Is there any seasonality?
- What time of day do most customers place orders?
- Which states have the highest/lowest average freight costs and delivery times?
- How accurate is the estimated delivery date compared to the actual?
- What are the most used payment types and installment behaviors?

---

## 🔍 Analysis Performed

- Initial data structure exploration (data types, nulls, basic stats)
- Time-based order trend analysis (yearly, monthly, daily)
- Time-of-day order categorization (Dawn, Morning, Afternoon, Night)
- State-level breakdown of sales, freight, and delivery metrics
- Delivery performance: estimated vs actual delivery dates
- Payment method usage by month and installment count

---

## 📊 Tools Used

- **SQL** (BigQuery / MySQL)
- **Excel / Google Sheets** (for screenshots and validation)
- **Jupyter Notebook** (Markdown documentation)

---

## 📌 Key Insights & Recommendations

- **Order Failures**  
  - A total of **609 orders were unavailable** and **625 orders were canceled**, which accounts for approximately **1.2% of total orders**.  
  - Recommendation: Analyze reasons for order cancellations and unavailability to reduce this percentage.

- **Surge in Order Volume**  
  - There is an **abrupt increase in order volume** over a short time span, indicating a rapid business expansion.  
  - Recommendation: Prepare with an **additional workforce** to handle growing demand. To mitigate long-term risk, consider **hiring contractual employees**.

- **Time-of-Day Purchasing Behavior**  
  - Brazilian customers predominantly place orders in the **afternoon and night**.  
  - Recommendation: **Increase staff during afternoon and night shifts** to handle more requests and reduce workforce during **morning and dawn**.

- **State-Level Contribution**  
  - Only **3 states contribute to the majority of the order volume**, while the rest have significantly lower numbers.  
  - Recommendation: Focus on **regional marketing and infrastructure improvements** in underperforming states to boost business.

- **High Delivery Time in Low-Volume States**  
  - **Average delivery time is higher** in states with **low order volume**, which may be deterring customers.  
  - Recommendation: Conduct a **deeper analysis** to determine the causes and work on **reducing delivery times** to improve customer satisfaction and order frequency.



