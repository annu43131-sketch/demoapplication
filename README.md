Inventory Manager
Overview
Inventory Manager is a full‑stack web application built with Spring Boot, Thymeleaf, MySQL, Bootstrap, and Chart.js.
It allows users to manage products with full CRUD operations (Create, Read, Update, Delete) and provides a visual dashboard with stock analytics.

✨ Features
Add new products with name, quantity, and price.

Edit existing products.

Delete products from inventory.

Dashboard summary cards:

Total Products

Low Stock (quantity < 5)

Out of Stock (quantity = 0)

Interactive bar chart showing stock levels by product.

Responsive UI styled with Bootstrap.

Toast notifications for user actions.

🛠 Tech Stack
Backend: Spring Boot, Spring Data JPA

Frontend: Thymeleaf, Bootstrap 5, Chart.js

Database: MySQL

Language: Java

⚙️ Setup Instructions
Clone the repository:

bash
git clone  https://github.com/annu43131-sketch/inventory-manager.git 
Configure database in application.properties:

properties
spring.datasource.url=jdbc:mysql://localhost:3306/inventorydb
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
Run the application:

bash
mvn spring-boot:run
Open in browser:

Code
http://localhost:8080/products-page
📊 Sample Data
Insert demo products into MySQL for testing:

sql
INSERT INTO product (name, quantity, price) VALUES
('Pen', 15, 5.0),
('Milk', 5, 30.0),
('Eraser', 2, 5.0),
('Pencil', 9, 10.0),
('Chocolate', 4, 100.0),
('Bottle', 0, 10.0);
🎤 Demo Script
When presenting:

“This project is an Inventory Manager. It shows product stock levels with summary cards and a bar chart. I can add, edit, and delete products, and the dashboard updates instantly. It demonstrates full CRUD operations with a connected backend and frontend, plus analytics visualization.”

📌 Author
Built by [Annu yadav and gauri]  
© 2026 Inventory Manager
