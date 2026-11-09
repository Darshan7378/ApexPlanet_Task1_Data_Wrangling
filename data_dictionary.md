# Data Dictionary
## ApexPlanet Data Analytics Internship – Task 1

### Dataset Overview
The dataset contains 1,000 sales transaction records
and 12 columns. It provides information about orders,
customers, products, quantities, prices and total sales.

### Column Descriptions

| Column Name | Data Type | Description | Business Relevance |
|---|---|---|---|
| Order_ID | String | Unique order identification number | Tracks individual orders |
| Order_Date | Date | Date when the order was placed | Analyzes sales trends over time |
| Customer_ID | String | Unique customer identification number | Identifies customers |
| Customer_Name | String | Name of the customer | Maintains customer records |
| Age | Float | Age of the customer | Supports customer segmentation |
| Gender | String | Gender of the customer | Helps demographic analysis |
| City | String | Customer's city | Supports regional sales analysis |
| Product | String | Name of the purchased product | Identifies product performance |
| Category | String | Category of the purchased product | Analyzes category-wise sales |
| Quantity | Integer | Number of units purchased | Measures sales volume |
| Unit_Price | Float | Price of one unit of the product | Supports pricing analysis |
| Total_Sales | Float | Total value of the transaction | Measures revenue |

### Dataset Summary
- Total Records: 1,000
- Total Columns: 12
- Dataset Type: Sales Transaction Data
- File Format: Excel (Original), CSV (Cleaned)

### Data Cleaning Summary
- Handled missing values in Age and City.
- Converted Order_Date into datetime format.
- Removed unnecessary spaces from text columns.
- Standardized categorical text formatting.
- Identified repeated Order_ID values.
- Identified 19 outliers in Total_Sales and retained them.
- Verified Total_Sales calculations.
- Removed temporary verification columns.
