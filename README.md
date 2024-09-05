# E-Commerce-Management-System-Using-MYSQL-Power-BI-

## Table of Contents

- **Project Overview**
- **Dataset Used**
- **Database Design**
- **Complex Queries**
- **Advanced Reporting**
- **Key Insights Summary**
- **Learnings**
- **Conclusion**

## Project Overview

The objective of this project is to design and implement a comprehensive E-Commerce Management System using MySQL. The system effectively manages customers, products, orders, reviews, and suppliers. It also includes complex queries and advanced reporting features to generate actionable business insights.

## Dataset Used

The dataset for the final dashboard was sourced from an Excel worksheet named "E-Commerce Dataset." It contains information on:
- **Top 10 Selling Products**: Includes `Product ID`, `Product Name`, `Total Sold`, `Category Name`.
- **Latest 10 Reviews**: Includes `Review ID`, `Product Name`, `Customer Name`, `Rating`, `Comment`, `Review Date`.
- **Sales Trend**: Includes `Sales Month`, `Total Sales`, `Number of Orders`, `Average Order Value`.

## Database Design

The following tables were created in MySQL to manage the various aspects of the e-commerce system:
- **Customers**: `customerid`, `name`, `email`, `phone`, `address`, `registrationdate`
- **Products**: `productid`, `name`, `categoryid`, `price`, `stockquantity`, `description`
- **Categories**: `categoryid`, `categoryname`
- **Orders**: `orderid`, `customerid`, `orderdate`, `orderstatus`, `totalamount`
- **OrderItems**: `orderitemid`, `orderid`, `productid`, `quantity`, `unitprice`
- **Reviews**: `reviewid`, `productid`, `customerid`, `rating`, `comment`, `reviewdate`
- **Suppliers**: `supplierid`, `name`, `contactinfo`, `address`
- **ProductSuppliers**: `productid`, `supplierid`, `supplyprice`, `supplydate`

## Complex Queries

Throughout the project, several complex SQL queries were developed and executed to extract valuable insights from the database:

1. **Retrieve a Customer's Complete Order History and Reviews**: This query combines data from the `Orders`, `OrderItems`, and `Reviews` tables to provide a comprehensive view of a customer's purchase history and their feedback on purchased products.

2. **Find Top-Selling Products and Their Categories**: This query identifies the best-performing products by sales volume and associates them with their respective categories. For example, the query revealed that "Dumbells" in the "Electronics" category was a top seller.

3. **Generate a Report of Total Sales and Average Order Value for the Last Quarter**: This query aggregates sales data over the last quarter to provide insights into the business's financial performance, focusing on total sales and average order value.

4. **Identify Products with Low Stock Levels and Their Suppliers**: This query identifies products that are running low on stock and links them to their suppliers, enabling proactive inventory management and reordering.

## Advanced Reporting

The project also involved the creation of advanced reports that provide deeper insights into the business operations:

1. **Monthly Sales Report**: This report provides a breakdown of total revenue, number of orders, and average order value on a monthly basis. It helps in understanding trends and making data-driven decisions for future strategies.

2. **Dashboard Generation**: A comprehensive dashboard was created using the dataset to visualize top-selling products, customer reviews, and sales trends. This dashboard serves as a central tool for monitoring key performance indicators and making strategic decisions.

3. **Supplier Performance Report**: This report evaluates the performance of suppliers based on delivery times, supply costs, and reliability. It helps in optimizing the supply chain and negotiating better terms with suppliers.

## Key Insights Summary

- **Top-Selling Product**: Example: "Dumbells" in the "Electronics" category.
- **Sales Trends**: Consistent growth with a peak during the last quarter.
- **Low Stock Products**: Critical stock levels identified for replenishment.
- **Supplier Performance**: Insights provided for optimizing supply chain efficiency.

## Learnings

- Gained expertise in **Database Design** by creating a comprehensive relational schema.
- Mastered **Complex SQL Queries** for advanced data retrieval and analysis.
- Enhanced skills in **Data Visualization** using Power BI.
- Developed proficiency in **Reporting** to support business decision-making.

## Conclusion

This project offered valuable experience in managing and analyzing e-commerce data. The end-to-end development, from database design to advanced reporting, equipped me with the skills necessary to work on real-world e-commerce platforms.


