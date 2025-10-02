# 📘 Relational Databases

## 🔹 What are Relational Databases?
A **relational database** is a way of structuring and managing data. Think of it as a collection of spreadsheets (**tables**) that are connected to each other in meaningful ways. This structure provides a robust and organized way to store and retrieve information.

---

## 📂 Core Concepts

### 🗂 Data Organization
- Data is stored in **tables**.
- Each table consists of:
  - **Rows (records):** Individual entries of data.
  - **Columns (fields):** Attributes that describe each record.

### 🔗 Relationships
- Tables can be **linked** through common fields (**keys**).
- This allows efficient connection and retrieval of related data.

### 🔑 Keys
- **Primary Key:**  
  A unique identifier for each record in a table.  
- **Foreign Key:**  
  A column (or set of columns) in one table that refers to the primary key in another table, creating relationships between tables.

### 💻 SQL (Structured Query Language)
- The **standard language** used to manage and query relational databases.
- Provides commands for:
  - Creating, updating, and deleting data.
  - Retrieving information efficiently.

---

## 🛡 ACID Properties
Relational databases ensure data integrity through the following properties:

- **Atomicity:** Each transaction is treated as a single, indivisible unit of work.  
- **Consistency:** Transactions maintain the integrity constraints of the database.  
- **Isolation:** Concurrent transactions do not interfere with each other.  
- **Durability:** Once a transaction is committed, it remains permanent.  

---

## ⚙️ Popular Relational Database Systems
- **MySQL**  
- **PostgreSQL**  
- **Oracle**  
- **SQL Server**

---

## ✅ Benefits
- Ensures **data integrity and consistency**.  
- Provides **efficient data retrieval**.  
- Offers **scalability** for handling large datasets.  
- Uses a **standardized query language (SQL)**.  
