#  Blinkit Sales Analysis (EDA)

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Blinkit sales data to understand **customer buying patterns, product performance, and outlet-level sales trends**.
The goal is to extract **business insights** that help improve **inventory planning, marketing strategy, and outlet performance**.

## Dataset Information

* **Total Records:** 8,523
* **Total Features:** 12
## Business Problems – Blinkit Sales (Short)
*   Identify top-selling product categories 
*   Analyze sales impact across outlet tiers (Tier 1, Tier 2, Tier 3) 
*   Evaluate performance of outlet sizes (Small, Medium, High) 
*   Analyze sales trends of old vs new outlets 
*   Identify best-performing outlet locations 
*   Improve inventory planning using sales insights 
*   Optimize marketing focus on high-performing products and outlets 

### Key Columns

* Item Fat Content
* Item Type
* Outlet Establishment Year
* Outlet Size & Location Type
* Item Visibility & Weight
* Sales
* Rating

##  Tools & Technologies

* **Python**
* **Pandas, NumPy** – Data cleaning & manipulation
* **Matplotlib, Seaborn** – Data visualization


##  Data Cleaning & Preparation

* Handled **missing values** in `Item Weight` using **mean imputation**
* Standardized categorical values (e.g., `low fat` → `Low Fat`)
* Checked and confirmed **no duplicate records**
* Performed descriptive statistical analysis



##  Exploratory Data Analysis

The analysis includes:

* **Sales by Item Fat Content** (Low Fat vs Regular)
* **Top-selling Item Categories**
* **Sales by Outlet Size** (Small / Medium / High)
* **Sales by Outlet Location Tier** (Tier 1 / Tier 2 / Tier 3)
* **Outlet Establishment Year vs Sales Trend**

Visualizations used:

* Pie Charts
* Bar Charts
* Line Plots


## Key Business Insights

* **Low Fat items generate higher total sales** than Regular items
* **Tier 3 outlets** contribute significantly to overall revenue
* **Medium-sized outlets** show better sales performance
* Certain **product categories dominate sales**
* Older outlets show **stable and consistent sales trends**


## Conclusion

This EDA helps Blinkit make **data-driven decisions** by identifying:

* High-performing products
* Profitable outlet types and locations
* Opportunities for better inventory and marketing strategies

## Author

**Utkarsh Singh**
Data Analyst 

