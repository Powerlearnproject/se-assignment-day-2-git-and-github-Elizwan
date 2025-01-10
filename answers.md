# Answers

## State and Explain the components of a DBMS(Database Management System)

A DBMS has the following components:

1. **Hardware**: The physical devices used to store and process the database, including servers, storage devices, and network hardware.
2. **Software**: The DBMS software itself, which manages the database and provides an interface for users and applications to interact with it.
3. **Data**: The raw data stored in the database, organized in tables, rows, columns, and fields.
4. **Users**: People who interact with the database, categorized into:
   - **Database Administrators (DBAs)**: Manage and maintain the database.
   - **Application Developers**: Create applications that access the database.
   - **End-Users**: Query and interact with the database.
5. **Procedures**: Guidelines or instructions on how to use and manage the DBMS.
6. **Query Processor**: Interprets and executes database queries from users.
7. **Database Engine**: Handles data storage, retrieval, and updating tasks.
8. **Metadata**: Data about the database structure, including schema and indexes.

## What is a relational database? Give 4 examples.

A relational database is a type of database that stores data in tables (relations) with predefined schemas, enabling relationships between tables using keys. It uses SQL (Structured Query Language) for querying and managing data.

**Examples of relational databases:**

1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

## State and Explain three classifications of SQL

1. **Data Definition Language (DDL)**:
   Used to define and manage the structure of a database. Examples:

   - `CREATE`: Create new tables or databases.
   - `ALTER`: Modify existing database structures.
   - `DROP`: Delete tables or databases.

2. **Data Manipulation Language (DML)**:
   Used for managing and manipulating data within tables. Examples:

   - `INSERT`: Add new data to tables.
   - `UPDATE`: Modify existing data.
   - `DELETE`: Remove data.

3. **Data Query Language (DQL)**:
   Focused on querying and retrieving data from a database. Example:
   - `SELECT`: Retrieve specific data based on conditions.

## What is the difference between a Primary Key and a Foreign Key?

- **Primary Key**:
  A unique identifier for a record in a table. Each table can have only one primary key, and it must contain unique and non-null values.

  - Example: `EmployeeID` in an `Employees` table.

- **Foreign Key**:
  A field in a table that links to the primary key of another table, establishing a relationship between the two tables.
  - Example: `DepartmentID` in an `Employees` table linking to the `DepartmentID` in a `Departments` table.

## What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of entities, their attributes, and the relationships between them in a database. It uses symbols such as rectangles (entities), ovals (attributes), and diamonds (relationships) to illustrate how data is structured and connected.

## What are the advantages of relational databases?

1. **Data Integrity**: Enforces rules like primary and foreign keys to ensure accurate and consistent data.
2. **Flexibility**: Supports complex queries and relationships between data.
3. **Scalability**: Can handle large amounts of data and users.
4. **Security**: Allows role-based access controls and data encryption.
5. **Standardized Query Language**: SQL provides a consistent way to manage and query data.

## State four types of data types used to store data in tables

1. **Integer (INT)**: Used to store whole numbers.
2. **Varchar (VARCHAR)**: Used to store variable-length text.
3. **Date (DATE)**: Used to store date values (e.g., YYYY-MM-DD).
4. **Boolean (BOOL)**: Used to store true/false values.

## What is the purpose of a database management system (DBMS)?

The purpose of a DBMS is to:

1. **Store, Organize, and Retrieve Data**: Efficiently manage large volumes of data in a structured format.
2. **Ensure Data Integrity**: Maintain accuracy and consistency of data.
3. **Provide Security**: Protect data from unauthorized access.
4. **Support Multi-User Access**: Allow multiple users to interact with the database simultaneously.
5. **Facilitate Querying**: Enable users to retrieve and manipulate data using SQL.
6. **Automate Backups and Recovery**: Ensure data is not lost due to hardware or software failures.

---
