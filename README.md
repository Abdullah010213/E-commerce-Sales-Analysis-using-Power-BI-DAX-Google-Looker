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
