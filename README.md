# Coffee-Orders
Objective : 
1. To analyze which country sells more coffee with respect to others.
2. To provide a representation of total sales over time.
3. To know the top 5 customers and rregular buyers of this product.

Here, in this dashboard I have used 3 KPIs (line chart to analyze sales over time and bar charts to analyze sales with respect to country and top 5 customers) and 4 slicers to analyze the above objectives. 

The dataset contains three different worksheets:- orders, customers and products. 
The Orders table contains 1000 records and 5 columns namely: Order ID, Order Date,Customer ID,Product ID and Quantity.

The customers table contains 1000 records and 9 columns namely: Customer ID, Customer Name, Email, Phone Number, Address Line 1, City, Country, Postcode and Loyalty Card.

The products table contains 48 records and 7 columns nmaely: Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g and Profit.

This first dataset is a raw dataset which needs to be cleaned, remove the duplicates, remove null values, using Vlookup function source the values from different worksheet.

The second dataset is cleaned by removing duplicate values using the icon in data tab > remove duplicates > if there are duplicates a message will appear and if no duplicates it will say no duplicates found.
Removed null values using if function and replacing it by 0, and with the help of Vlookup function and combination of index-match function sourced the data from different worksheets that is products and customers table present in the same workbook.
