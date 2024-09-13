## Project Overview
### We are developing an Excel dashboard titled COFFEE SALES DASHBOARD, designed to offer a comprehensive view of coffee sales data. The dashboard will include the following features:
#### 1. Trend Analysis - Line Chart of Total Sales by Coffee Type
A line chart will display the total sales over time, categorized by the different coffee types: Arabica, Excelsa, Liberica, and Robusta. This visualization will allow users to observe sales trends over time for each type of coffee.
#### 2. Sales by Country - Bar Chart
A bar chart will showcase sales performance across three key regions: the United States, Ireland, and the United Kingdom. This will help users quickly compare sales figures by country.
#### 3. Top 5 Customer Analysis - Bar Chart
A bar chart will highlight the top 5 customers based on their purchase amounts. This feature will allow users to identify the most valuable customers and analyze their buying patterns.
#### 4. Interactive Timeline for Visual Filtering
A timeline chart will be incorporated to provide users the ability to filter and manipulate the dashboard’s visuals for different time periods. This will enable dynamic reporting based on the selected timeframe.
#### 5. Roast Type Filter - Slicer
A slicer will be added for users to filter data by roast type, with options for Dark, Light, and Medium roasts. This will help in analyzing sales based on roast preferences.
####  Product Size and Loyalty Card Slicers
Two additional slicers will be included:
Size Slicer: Since the coffee is available in various sizes, this slicer will allow users to filter sales data based on the size of the coffee purchased.
Loyalty Card Slicer: This slicer will enable users to filter the data based on whether the customer used a loyalty card, offering insights into how the loyalty program impacts sales.

This dashboard will provide a holistic view of coffee sales, allowing for detailed insights through interactive data visualizations and filters.


## Let's Get Started
### 1. Data Gathering
To begin, we will gather and organize the data needed for the COFFEE SALES DASHBOARD from two key sources: the CUSTOMER SHEET and the PRODUCTS SHEET. This step will involve populating specific columns using Excel formulas such as XLOOKUP and INDEX MATCH to extract the relevant information.
#### a. Populating Customer Information
We will use the XLOOKUP function to fill in the following columns with data from the CUSTOMER SHEET:

Customer Name
Email
Country
The XLOOKUP function is ideal here as it allows for a simple and efficient search of a specific value (e.g., Customer ID or Email) within a range, and returns the corresponding data from the specified columns.

#### b. Populating Product Information
For the product-related data, we will use the INDEX MATCH combination to gather data for the following columns from the PRODUCTS SHEET:

Coffee Type
Roast Type
Size
Unit Price
Sales
The INDEX MATCH function is preferred in this scenario due to its flexibility and dynamic capabilities, especially when dealing with large datasets or situations where the lookup column is not positioned to the left of the result column (as required by VLOOKUP). 
Unlike VLOOKUP, which has certain limitations in terms of column position and performance with large datasets, INDEX MATCH allows us to look up values in any column and retrieve data from any other column, making it a more robust choice for complex data extraction.

By combining these two approaches, we will efficiently gather and organize the necessary data for the dashboard, ensuring accuracy and adaptability in the process.

![dataGathering](https://github.com/user-attachments/assets/c54f4a76-971e-4a14-8a89-f9a346db81cf)


### 1. Data Formatting



