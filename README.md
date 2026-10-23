## 1. Project Objective

The objective of this project is to analyze product sales, costs, revenue, and profitability across different countries, regions, product categories, and customer segments. Using Power BI, the data will be visualized through interactive dashboards to identify top-performing products, compare regional performance, evaluate delivery timelines, and identify products generating low or negative profit. The analysis will help understand sales performance, cost distribution, 
and business profitability.


## 2. Data Description
The dataset contains product-level sales and delivery information, including product details, customer segments, categories, geographical regions, shipping and delivery dates, pricing, units sold, total costs, revenue, and net profit.


The dataset consists of the following 15 columns:

| Column Name     | Description |
|-----------------|-------------|
| Product Id      | Unique identifier assigned to each product record. |
| Product Name    | Name of the product being sold. |
| Segment         | Customer segment, such as Consumer or Corporate. |
| Category        | Main product category, such as Furniture, Office Supplies, or Technology. |
| Sub-Category    | Specific product group within a category. |
| Region          | Geographical region where the product is sold. |
| Country         | Country associated with the product sale. |
| Shipping Date   | Date when the product was shipped. |
| Delivery Date   | Date when the product was delivered. |
| Unit Price      | Selling price of one unit of a product. |
| Unit Cost       | Cost of one unit of a product. |
| Units Sold      | Total number of units sold. |
| Net Cost        | Total cost associated with the units sold. |
| Revenue         | Total revenue generated from product sales. |
| Net Profit      | Profit earned after subtracting the net cost from revenue. |


## 3. Data Preprocessing

**The following preprocessing steps were identified for preparing the dataset for analysis in Power BI:**

**Removed Unnecessary Rows:** Removed the extra rows containing 0 values that appeared before the column headers.

**Updated Column Headers:** After removing the unnecessary rows containing 0 values, updated the column headers to ensure they correctly align with the corresponding data columns.

**Separated Combined Columns:** Split combined columns, such as SegmentCategory and Region Country, into separate columns to improve data organization and usability.

**Verified Data Types:** Checked the data types of all columns and ensured that date, numeric, and categorical columns were stored in appropriate formats.

**After preprocessing, the dataset was prepared for further analysis and interactive dashboard creation in Power BI.**

![Sales Dashboard](Screenshot%20(133).png)
![DMart Sales Dashboard](DMART%20DASHBOARD.png)
![DMart Sales Dashboard](DMART%20DASHBOARD.png)
