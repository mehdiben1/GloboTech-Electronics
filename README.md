# GloboTech-Electronics Sales Performance Analysis: 2016 - 2022

<details open>
  <summary>Table of Contents:</summary>
  
- [Project Background](#project-background)
- [Data Structure](#data-structure)
- [Executive Summary](#executive-summary)
- [Insights Deep Dive](#insights-deep-dive)
    - [Customer Insights](#Customer-Insights)
    - [Product & Brand Profitability](#Product-&-Brand-Profitability)
    
- [Recommendations](#Recommendations)

</details>

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
## 1. Customer Insights:
### a. Customer age segments:

- Young Adults and Seniors are the top revenue-generating segments, together contributing over **$27.6M**, roughly **44%** of total company revenue.
- Average Order Value (AOV) is relatively consistent across age groups, ranging between **$2,068** and **$2,172**, indicating similar spending patterns per transaction regardless of age.

  <img width="655" height="250" alt="image" src="https://github.com/user-attachments/assets/e7e2d10f-fb42-49c5-be3f-d1ac1866ccd8" />

  
### b. Customer purchase behavior:
- The Top 10 customers generated **$425K** in revenue, representing approximately **1.4%** of total revenue, suggesting a relatively broad revenue base rather than over-reliance on a few clients.
- **Matthew Flemming** is the single largest customer, contributing **$61.8K** in revenue and **$39.6K** in profit, highlighting strong profitability in high-value clients.
- Purchase frequency distribution shows that the majority of customers (**77.5%**) purchase **1–3 items** per order, with a steep drop-off beyond that, suggesting opportunities to increase basket size via cross-selling or promotions.

  <img width="895" height="401" alt="image" src="https://github.com/user-attachments/assets/ab4d2f63-14a5-46b2-a5f1-0395be24fc56" />

## 2. Product & Brand Profitability: 
- The top three brands, Adventure Works, Wild World Importers, and Contoso—generate over half of GloboTech’s total profit (**56.3M**). This emphasizes the importance of prioritizing investment in these high-performing brands while reevaluating the role of lower-performing ones.
- Among the product lineup, the **WWI Desktop PC 2.33 X23** stands out as the top contributor, with a profit of **$0.34M**. It appears multiple times with slight variations, indicating strong recurring sales. Adventure Works desktops dominate the top ten products, showcasing consistent profitability across similar SKUs and reinforcing the brand’s position as a key profit driver.
- Computers generate **$11.3 million** in profit, nearly double that of the next highest category. This confirms that computers are the core revenue generator. Home appliances and cameras follow, but with a significant drop-off, suggesting they should be considered as secondary focus areas.

<img width="867" height="550" alt="image" src="https://github.com/user-attachments/assets/b457e160-361d-49c6-bd69-0ebe3252ded5" />

  
# Recommendations:

- **Prioritize High-Performing Brands and Products:** Focus resources on Adventure Works, WWI, and Contoso, as these three brands together generate more than half of our total profit. Expand successful product lines, such as the WWI Desktop PC2.33 X23 and Adventure Works desktops, by leveraging their proven demand to strengthen our market share in the Computers category. Additionally, coordinate efforts in marketing, supply chain, and research and development to support these core profit drivers.
- **Rationalize the Product Portfolio:** Conduct a comprehensive profitability analysis to identify low-performing SKUs and brands that weaken margins. Discontinue or reposition underperforming items and reallocate budgets to high-margin products with growth potential. This approach will enhance operational efficiency and free up resources for strategic investments.
- **Enhance Geographic and Customer Segmentation Strategy:** Implement successful strategies from high-profit states like Nevada and Kansas in other regions with untapped potential. Create focused campaigns targeting high-value customer segments, such as Young Adults and Seniors. Additionally, develop tailored retention programs for top spenders to increase repeat purchases and enhance customer lifetime value.
- **Drive Higher Basket Size and Cross-Selling:** Use personalized marketing, targeted promotions, and loyalty incentives to encourage multi-item purchases. Train sales staff and optimize online recommendation engines to upsell complementary high-margin products, increasing revenue per customer transaction.


# Appendix:

- For more details about the dataset and the data cleaning process check out [the Dataset Summary & Issue Log ](https://github.com/mehdiben1/GloboTech-Electronics/tree/main/Scope%20of%20work%20&%20Issues%20log)

  
- Check out the full Power Bi report [here](https://github.com/mehdiben1/GloboTech-Electronics/tree/main/Power%20Bi%20Dashboard)
