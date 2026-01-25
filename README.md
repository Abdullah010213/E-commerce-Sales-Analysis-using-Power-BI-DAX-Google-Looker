# E-commerce-Sales-Analysis-using-Power-BI-DAX-Google-Looker
# Data Dictionary - E-commerce Sales Analysis

| Field Name | Data Type | Description | Purpose |
| :--- | :--- | :--- | :--- |
| **order_id** | String | Unique identifier for each transaction | Primary Key for orders |
| **customer_id** | String | Unique identifier for each customer | Linking customer behavior |
| **product_id** | String | Unique identifier for the product | Analyzing product performance |
| **category** | String | Product group (e.g., Electronics, Home) | Primary dimension for analysis |
| **price** | Decimal | Original unit price of the item | Calculating base revenue |
| **discount** | Decimal | Percentage reduction applied (0.0 to 1.0) | Analyzing promotional impact |
| **quantity** | Integer | Number of units purchased | Sales volume tracking |
| **payment_method**| String | Method used (Credit Card, PayPal, etc.) | Financial channel analysis |
| **order_date** | Date | Date the order was placed | Time Intelligence (YoY, MoM) |
| **region** | String | Geographic location (North, South, etc.) | Regional performance mapping |
| **total_amount** | Decimal | Final price paid (Price * Qty * Discount) | KPI: Discounted Sales |
| **profit_margin** | Decimal | Actual profit earned from the transaction | KPI: Total Profit |
| **customer_age** | Integer | Age of the customer | Customer segmentation |
| **AgeGroup** | String | Categorized age (e.g., 18-24, 55+) | Demographic analysis (Calculated) |

# E-Commerce Sales Performance Analysis (2023 - 2025) 📊

A data-driven project focused on analyzing e-commerce transactions using **Power BI** and **Google Looker** to optimize sales strategy and regional profitability.

---

## 📌 Project Overview
This analysis utilizes an e-commerce dataset containing transaction-level information on customer orders, products, and financial performance. The project demonstrates the full BI lifecycle: data cleaning, star-schema modeling, DAX/LookML development, and executive dashboarding.

## 🛠️ Tech Stack
* **Power BI:** Advanced DAX measures and demographic segmentation.
* **Google Looker:** LookML semantic modeling and category performance exploration.
* **Data Modeling:** Star-schema with central fact tables.

## 📈 Key Performance Indicators (KPIs)
| KPI | Value | Description |
| :--- | :--- | :--- |
| **Total Sales** | **6.2M** | Gross revenue across all categories |
| **Total Profit** | **970.02K** | Net earnings after discounts and costs |
| **Profit Margin** | **17%** | Overall efficiency of sales conversion |
| **Top Category**| **Electronics** | Highest revenue generating product line |

---

## 🔍 Key Insights

### 1. Category Performance
* **Electronics** is the business engine, contributing **56.7%** of total sales (3.5M).
* **Home** and **Sports** show strong stability with high profit margins.
* **Grocery** is currently underperforming, showing a net loss of **-9,187.96**, requiring an immediate pricing strategy review.

### 2. Regional & Demographic Analysis
* **Most Profitable Region:** The **South** region leads with **211.08K** in total profit.
* **Core Customer:** The **45+ Age Group** is the most valuable segment, driving the highest sales volume.
* **Payment Trends:** **Credit Card** transactions are the preferred method, accounting for **35.07%** of total payments.

### 3. ROI Strategy
A targeted **LKR 100,000** marketing campaign focused on **Electronics** in the **South** region for the **45+ age group** is projected to yield an **ROI of 36%**, assuming historical conversion rates.

---

## 📊 Dashboard Highlights

### Power BI Analysis
* **Sales vs. Year:** Peak performance observed in 2024.
* **Demographic Slicing:** Visualizes the spending power of the 45+ age group.
* **Payment Method Mix:** Breakdown of Credit Card vs. UPI/Wallet/COD.

### Google Looker Analysis
* **Category Deep-Dive:** Scatter plots showing the correlation between sales volume and profitability.
* **Daily Profit Trends:** A time-series analysis of profit fluctuations from 2023 to 2025.

---

## 📂 Project Structure
```text
├── Screenshots/             # Dashboard visuals (Power BI & Looker)
├── Data/                   # Dataset documentation/Data Dictionary
├── DAX_Measures.txt         # Key Power BI calculations
└── README.md                # Project documentation
