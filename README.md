# smartshop-inventory-system

This is the peer-graded assignment for "Database Integration and Management," the sixth course in a 12-course series in the Microsoft Full-Stack Developer Professional Certificate program.

### 👋 Introduction:

Imagine you are a database engineer tasked with developing the SmartShop Inventory System for a fictional retail company, SmartShop. This system must manage inventory data across multiple stores, providing real-time insights into stock levels, sales trends, and supplier information. 

The company requires:

* A database to store and retrieve inventory data efficiently.

* Complex queries to analyze trends and relationships between products, sales, and suppliers.

* Optimized database operations to ensure high performance and scalability.

Your goal is to leverage Microsoft Copilot to create, debug, and optimize SQL queries, ensuring the system meets performance and accuracy requirements. This project will span three activities and culminate in a comprehensive inventory management database.

### 🧠 Activity 1: Writing Basic SQL Queries With Microsoft Copilot

<img width="1560" height="1080" alt="Activity 1" src="https://github.com/user-attachments/assets/f78ec4b2-49f2-42d3-92c5-83a55ac7b086" /><br>

(5 pts) Did you include a brief summary of how Copilot assisted in each step of the development process?

Yes. It was fairly simple for basic queries, column names were spelled correctly. Pascal case and snake case were correctly used in the generated queries.

### 🧩 Activity 2: Creating Complex SQL Queries With Microsoft Copilot

<img width="1560" height="1080" alt="Activity 2" src="https://github.com/user-attachments/assets/724483f6-f86a-4fd0-a02d-8d1d108617ae" /><br>

(5 pts) Did you include a brief summary of how Copilot assisted in each step of the development process?

Yes. For complex queries, things were much more challenging. Thankfully Copilot was here to assist me in generating these queries. Especially where there were clauses like JOINs, GROUP BYs and ORDER BYs.

### 🛠️ Activity 3: Debugging And Optimizing SQL Queries With Microsoft Copilot

<img width="1560" height="1080" alt="Activity 3" src="https://github.com/user-attachments/assets/791f55e4-0c06-4fa3-ac14-aa1698a880f9" /><br>

(5 pts) Did you debug errors in SQL queries with Copilot’s assistance?

Yes. There were no bugs or errors, so there was nothing to debug.

(5 pts) Did you optimize query performance using Copilot’s suggestions, including indexing and query restructuring?

Yes. Query performance was improved with the CREATE INDEX statement. Instead of repeating the same subquery multiple times where the product ID in the sales table is equal to product ID in the products table, it can be restructured with a LEFT JOIN and GROUP BY clause.
