# Coffee Orders Analysis
## Project Overview
This project analyzes customer orders for a coffee business. The dataset contains detailed information about orders, customers, and products, allowing insights into sales trends, customer behavior, and product popularity.
### Project Goals
- To analyze order data to identify top-selling products and high-value customers.
- To examine customer demographics and location distribution.
- To assess sales trends and product popularity over time.
### Key Analysis Steps
 ## 1. Data Processing with Excel Formulas
This project makes extensive use of Excel functions to automate data retrieval, integrate information across sheets, and add conditional logic for data categorization.
### Data Lookup and Integration
- **`XLOOKUP`**: Used to pull in customer and product details by referencing `Customer ID` and `Product ID`. This allowed seamless data linking across sheets.
### Dynamic Data Retrieval
- **`INDEX` and `MATCH`**: Combined to dynamically fetch product details. `MATCH` finds the row number, and `INDEX` retrieves data from that specific row.
### Conditional Logic
- **`IF`**: Applied to add custom categories and conditions, such as marking high-value orders or categorizing orders by size.
By using these functions, the project efficiently organized and processed data, enhancing the accuracy and speed of analysis.

## 2. Pivot Tables
  Created pivot tables to analyze the top 5 customers by countries and total sales.
## 3. Interactive Filters
  Users can filter data by product type,size and time period.

