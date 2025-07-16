
```markdown
# Online Bookstore Database Management 📚💻

A SQL-based database management system designed for an online bookstore. The project includes 7 interconnected tables, sample data generation using Python, and SQL triggers/queries for managing real-world bookstore operations.

## 📊 Database Tables

- **BookInfo** – Contains details of all books (in stock or not)
- **Inventory** – Tracks in-stock books with quantity, price, and supplier info
- **Supplier** – Stores supplier details
- **Purchase** – Records all purchase transactions
- **Customer** – Stores customer contact information
- **Autdet** – Contains author details (randomly generated using Python)
- **log_pu_details** – Logs purchase and cancellation details

## ⚙️ Features

- Relational database with properly normalized tables
- Sample data generated using a Python script (`ran.py`)
- Includes SQL file with triggers and complex queries (`Queries and trigger`)
- Supports common bookstore operations like purchase logging and inventory management

## 📝 Files Included

```

📦 OnlineBookStore-Database-management
- 📄 book\_store\_online.sql         # SQL dump of the entire database
- 📄 Queries and trigger           # Contains SQL triggers and sample queries
- 📄 ran.py                        # Script to generate sample author data
- 📄 README.md                     # Project documentation


## 🚀 Getting Started

1. **Import the SQL dump** into your MySQL or compatible database system:
   ```sql
   SOURCE book_store_online.sql;


2. **Run `ran.py`** to generate and insert sample author data (if needed).

3. Use the provided **Queries and trigger** file to explore and test database logic.

## 📚 Use Cases

* Learn SQL database design through a real-world example
* Practice writing complex SQL queries and using triggers
* Simulate bookstore operations like purchasing, stock updates, and customer logs


**Built for learning and exploring database systems in a practical bookstore setting.**


