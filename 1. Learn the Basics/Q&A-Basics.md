# 🧠 Questions & Answers — Unit: SQL, NoSQL, and RDBMS

This document compiles **key questions and answers** to study the main concepts of **Relational (SQL/RDBMS)** and **Non-Relational (NoSQL)** databases.  
It’s designed as an easy-to-study reference guide.

---

## 🗄️ Section 1: SQL Databases (Relational)

### ❓ What is an SQL database?
An **SQL database** stores information in **structured tables** consisting of rows and columns.  
It follows a **relational model** and requires a **predefined schema** that defines data types and relationships.

---

### ❓ What does it mean that SQL databases are relational?
It means data is **connected through relationships** using **primary keys and foreign keys**, allowing complex queries using **JOIN** operations.

---

### ❓ What language do SQL databases use?
They use **SQL (Structured Query Language)**, a **declarative language** used to query, insert, update, and delete data, as well as to define database structures.

---

### ❓ What are ACID properties and why are they important?
**ACID** properties ensure **data reliability and integrity** during transactions:

- **Atomicity:** Each transaction is all or nothing.  
- **Consistency:** The database remains in a valid state before and after a transaction.  
- **Isolation:** Transactions don’t interfere with each other.  
- **Durability:** Once committed, data persists even after failures.

---

### ❓ What are some popular SQL databases?
- **MySQL**  
- **PostgreSQL**  
- **Oracle Database**  
- **Microsoft SQL Server**

---

### ❓ What are the main advantages of SQL databases?
- Strong **data integrity** and **consistency**.  
- Support for **complex relationships** through joins.  
- **Standardized and widely used language (SQL).**  
- **Mature technology** with strong community and tools.  
- **Robust security** and role-based access control.

---

### ❓ How do SQL databases scale?
They primarily scale **vertically**, by adding more resources to a single server (CPU, RAM, storage).

---

### ❓ When is it best to use an SQL database?
Use SQL when:
- You need **consistent, structured data**.  
- The system requires **ACID transactions**.  
- Relationships between entities are **complex**.  
- **Security and access control** are important.

---

## ⚡ Section 2: NoSQL Databases (Non-Relational)

### ❓ What is a NoSQL database?
A **NoSQL database** (Not Only SQL) stores data in **flexible, non-tabular structures**, such as documents, key-value pairs, graphs, or columns.  
It does not require a fixed schema.

---

### ❓ What are the main types of NoSQL data models?
- **Document databases** (e.g., MongoDB, CouchDB)  
- **Key-Value stores** (e.g., Redis, DynamoDB)  
- **Column-Family stores** (e.g., Cassandra, HBase)  
- **Graph databases** (e.g., Neo4j)

---

### ❓ What are BASE properties, and how do they differ from ACID?
**BASE** properties focus on **availability and scalability**, sacrificing strict consistency:

- **Basically Available:** System guarantees availability.  
- **Soft State:** The system state can change over time.  
- **Eventually Consistent:** Data becomes consistent eventually.

Unlike **ACID**, which ensures immediate consistency, **BASE** allows temporary inconsistencies to improve performance and scalability.

---

### ❓ What are the advantages of NoSQL databases?
- Handle **large volumes of unstructured or semi-structured data.**  
- Support **horizontal scalability** (adding more servers).  
- Offer **flexible schemas** that evolve easily.  
- Provide **high performance** for massive read/write operations.

---

### ❓ What are some examples of NoSQL databases?
- **MongoDB** — Document model  
- **Redis** — Key-value model  
- **Cassandra** — Column-family model  
- **Neo4j** — Graph model

---

### ❓ When should you use a NoSQL database?
Use NoSQL when:
- You need **massive scalability and availability**.  
- You’re working with **unstructured or rapidly changing data**.  
- You want **schema flexibility**.  
- You need **fast response times** for large-scale applications.

---

## ⚖️ Section 3: SQL vs NoSQL Comparison

| Feature | SQL | NoSQL |
|----------|-----|--------|
| **Data Model** | Tables (rows & columns) | Documents, key-value, graphs, columns |
| **Schema** | Fixed | Flexible or schema-less |
| **Consistency** | Strong (ACID) | Eventual (BASE) |
| **Scalability** | Vertical | Horizontal |
| **Query Language** | SQL | Varies by database |
| **Relationships** | Complex (joins) | Limited or embedded |
| **Examples** | MySQL, PostgreSQL | MongoDB, Redis, Cassandra |
| **Best For** | Financial, ERP, CRM | Big Data, IoT, Social Media |

---

### ❓ How do you choose between SQL and NoSQL?

**Choose SQL when:**
- You need **data integrity and accuracy**.  
- Your system depends on **transactions and relationships**.  
- You need **consistent, structured data**.

**Choose NoSQL when:**
- You need **scalable, high-performance systems**.  
- Your data is **unstructured or rapidly evolving**.  
- You need **flexibility** and **fast development**.

**Hybrid Approach:**  
Many modern applications combine **SQL and NoSQL** to take advantage of both models.

---

## 🧩 Section 4: RDBMS (Relational Database Management System)

### ❓ What is an RDBMS?
An **RDBMS** is a software system used to create, manage, and manipulate relational databases.  
It provides **tools for ensuring data integrity, security, and efficient access**.

---

### ❓ What are the main benefits of RDBMS?

#### 🔒 Data Integrity & Consistency
- Supports **ACID transactions**.  
- Enforces **constraints** (Primary Key, Foreign Key, Unique, Check).  
- Prevents **invalid or inconsistent data**.

#### 🗂 Structured Data & Relationships
- Organizes data in **tables with defined schemas**.  
- Supports **complex joins** for data relationships.

#### 💻 SQL Standardization
- Uses **SQL**, a widely adopted and standardized language.  
- Ensures **portability** across different RDBMS systems.

#### 🌐 Mature Technology
- Decades of development and optimization.  
- Strong ecosystem, community, and tooling.

#### 🛡 Security
- **Role-based access control**.  
- **Auditing and logging** for compliance.

#### 📈 Vertical Scalability
- Can scale by **increasing server resources** (CPU, RAM, storage).

---

### ❓ What are the limitations of RDBMS?

- **Limited horizontal scalability.**  
- **Schema rigidity** — hard to change large database structures.  
- **ORM complexity** due to object-relational mismatch.  
- **Performance issues** with heavy joins or large transactions.  
- **High costs** for commercial licenses or powerful hardware.

---

### ❓ When should you use an RDBMS?
Use RDBMS when:
- **Data integrity and consistency** are crucial.  
- The application requires **ACID transactions** (finance, e-commerce).  
- There are **complex relationships** among data.  
- **Security and access control** are priorities.  
- You need a **mature and reliable database system.**

---

### ❓ When should you consider alternatives?
Consider alternatives when:
- You need **massive horizontal scaling**.  
- You handle **unstructured or fast-changing data**.  
- You require **real-time analytics or specialized queries**.  
- You need **high-performance distributed systems** (e.g., IoT, streaming data).

---

## 🧾 Final Summary

- **SQL / RDBMS:**  
  Best for structured data, integrity, transactions, and strong consistency.  

- **NoSQL:**  
  Best for scalability, flexibility, and large volumes of unstructured data.  

> 💡 **Quick Recap:**  
> - SQL = Structure + Integrity + Transactions  
> - NoSQL = Scalability + Flexibility + Performance  
> - RDBMS = Reliable management of relational data  

---
