# PostgreSQL:

## What is PostgreSQL
PostgreSQL, also known as Postgres, is an open-source Relational Database Management System (RDBMS) renowned for its robustness, reliability, and advanced features. It provides a powerful and scalable platform for managing large volumes of structured data.
PostgreSQL supports a wide range of data types, indexing options, and query optimization techniques, making it suitable for various applications. It offers ACID (Atomicity, Consistency, Isolation, Durability) compliance and supports transactions, ensuring data integrity and reliability. With its extensibility and support for various programming languages, PostgreSQL is widely used in enterprise environments and by developers to build high-performance, data-driven applications.

## What is pgAdmin

pgAdmin is a powerful, open-source administration and development platform for PostgreSQL, a robust, open-source database. It provides a graphical user interface (GUI) that simplifies managing PostgreSQL databases, including creating, modifying, and deleting objects. pgAdmin can be used on Linux, Unix, macOS, and Windows. 

## Creating a Database

### 1. Creating a Database with Default Settings
**Query:**
CREATE DATABASE test_db_1;

### 2. Creating a Database with Specific Parameters
**Query:**
CREATE DATABASE my_test_db2 WITH ENCODING='UTF8' OWNER=DBOWNER CONNECTION LIMIT=30;

