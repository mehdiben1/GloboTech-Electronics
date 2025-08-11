# GloboTech-Electronics : 2016 - 2022

# Project Background:
**GloboTech Electronics** is a global electronics retailer **operating since 2016**, with a diversified sales strategy that includes both e-commerce and brick-and-mortar stores across multiple regions. The company offers a wide range of consumer electronics from top brands, catering to customers in North America, Europe, Asia, and beyond.

Over the years, GloboTech has accumulated a substantial volume of operational and transactional data, covering everything from sales transactions and product catalogs to customer demographics, store locations, and currency exchange rates. However, this data remains largely unstructured and under-leveraged across departments.

As a data analyst, my role is to transform this raw data into actionable insights that can support data-driven decision-making for key stakeholders, particularly the executive leadership and strategy teams.

# Data Structure:
The companies main database structure as seen below consists of 5 tables: **Sales**, **Customers**, **Products**, **Category** and **Stores** with a total row count of **63 000 records**. A description of each table is as follows:

- **Sales:** Captures transaction-level data for every order placed, including order identifiers, product references, customer identifiers, store location, quantity sold and currency codes.
- **Products:** Contains detailed product-level attributes such as brand, product name, color, cost (USD), and price (USD).
- **Category:** Defines the product hierarchy, mapping each product to a category and subcategory.
- **Stores:** Holds store-level data, including location (country, state), physical size (square meters), and opening date.
- **Customers:** Stores customer-level demographic and geographic details, such as name, gender, date of birth, city, state, country, and continent.

  Each row in the Sales table links a customer to a specific product sold in a given store, with the product’s category information derived from the Category table. The relationships between these tables are defined by keys **ProductKey**, **CustomerKey**, **StoreKey**, and **CategoryKey**, as illustrated in the Entity Relationship Diagram (ERD) above.

<img width="1099" height="475" alt="ERD GoloTech" src="https://github.com/user-attachments/assets/de66cc53-bab3-48ed-96c0-40b073aa901d" />


# Executive Summary
## Overview of Findings:
- **From 2016 to 2022**, GloboTech generated total revenue of **$56.0M**, selling approximately **198K units** and achieving **$33.0M** in profit (**58.9% of revenue**), which indicates strong operational efficiency.
- Large-format stores are the leading revenue drivers, contributing **$25.5M** (**45.5% of total revenue**). The business also benefits from a high repeat purchase rate of **61%**, reflecting strong customer loyalty.
- In geographic performance, the United States led with total revenue of **$24.0M**, followed by the United Kingdom (**$6.0M**) and Germany (**$4.2M**). Profitability is concentrated in key North American regions: Nevada, Kansas, Nebraska and New Mexico together account for approximately **$3.24M**, or **9.8% of total profit**.
  
These results suggest the company is well-positioned to maintain growth by optimizing store performance, leveraging repeat customers, and sustaining its high profitability.

<img width="1011" height="567" alt="image" src="https://github.com/user-attachments/assets/5b34a623-2ba9-4be9-a250-63a57432f6bc" />



# Insights Deep Dive:
## I. Customer Insights:
### 1. Customer age segments:
- Young Adults and Seniors are the top revenue-generating segments, together contributing over **$27.6M**, roughly **44%** of total company revenue.
- Average Order Value (AOV) is relatively consistent across age groups, ranging between **$2,068** and **$2,172**, indicating similar spending patterns per transaction regardless of age.
  
### 2. Customer purchase behavior:
- The Top 10 customers generated **$425K** in revenue, representing approximately **1.4%** of total revenue, suggesting a relatively broad revenue base rather than over-reliance on a few clients.
- **Matthew Flemming** is the single largest customer, contributing **$61.8K** in revenue and **$39.6K** in profit, highlighting strong profitability in high-value clients.
- Purchase frequency distribution shows that the majority of customers (**77.5%**) purchase **1–3 items** per order, with a steep drop-off beyond that, suggesting opportunities to increase basket size via cross-selling or promotions.
  
## II. Product & Brand Profitability
# Recommendations:
