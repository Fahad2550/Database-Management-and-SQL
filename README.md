# Relational Database Management and SQL Queries Project

This project centers around the creation and management of a relational database for ABC Car Service Co., a fictional car service company. The primary objective was to design a robust and scalable database schema that could efficiently support the diverse operations of a car service center, encompassing everything from employee management to customer interactions and inventory tracking.

## Project Overview

ABC Car Service Co. operates multiple service centers, each with its own set of employees, customers, and inventory. The database was meticulously designed to reflect this complex structure, ensuring that all data could be effectively managed and queried. The project involved creating a comprehensive schema, developing and executing SQL queries, and implementing user roles and permissions to safeguard data integrity and security.

## Key Components

### 1. Database Schema Design
The heart of this project lies in the carefully crafted database schema. This schema includes several interrelated entities:
- **Centers**: Representing the different service centers operated by ABC Car Service Co.
- **Shop Managers, Receptionists, and Mechanics**: Tracking the employees working at each center, along with their roles and responsibilities.
- **Cars and Customers**: Managing customer information and their vehicles, including make, model, year, and maintenance history.
- **Inventory**: Keeping track of car parts, their quantities, and their association with specific service centers.
- **Maintenance History and Billing**: Recording the services provided to each car, the associated costs, and the billing information.

Each entity was designed with appropriate relationships and constraints, ensuring referential integrity across the database. This design allows for efficient data management, enabling complex queries and analyses.

### 2. SQL Queries
A series of SQL queries were developed to interact with the database, providing insights and facilitating the operations of the service centers. These queries include:
- **Retrieving Employee Information**: Identifying shop managers and their contact details across different centers.
- **Customer and Vehicle Management**: Querying car owners based on specific vehicle attributes, such as make or maintenance history.
- **Operational Insights**: Calculating maintenance costs for specific vehicles, listing frequently used car parts, and generating billing information.
- **Data Manipulation**: Updating employee roles, assigning mechanics to specific maintenance tasks, and managing inventory levels.

These queries demonstrate the practical application of SQL in managing a dynamic and complex database, showcasing your ability to extract valuable information and maintain operational efficiency.

### 3. User Roles and Permissions
To ensure the security and integrity of the data, the project also involved defining user roles and assigning permissions based on job responsibilities. The roles created include:
- **Mechanics**: Granted access to view maintenance records and inventory data relevant to their tasks.
- **Receptionists**: Allowed to manage customer and car records, as well as update maintenance information.
- **Shop Managers**: Given full access to all data, including the ability to modify records and oversee operations.

By implementing these roles and permissions, the project demonstrates a comprehensive understanding of database security practices, ensuring that users only have access to the data necessary for their roles.

## Technologies Used

- **SQL**: Used extensively for creating tables, inserting data, writing queries, and managing the overall database structure.
- **Relational Database Management**: The project emphasizes best practices in relational database design, ensuring data consistency, integrity, and scalability.

## Conclusion

This project exemplifies a thorough understanding of relational database management and SQL, from initial schema design to complex query execution. It not only highlights technical proficiency but also showcases the ability to design a database system that supports real-world business operations. Through this project, I have demonstrated the skills necessary to manage and manipulate large datasets, extract meaningful insights, and maintain the security and integrity of the data.
