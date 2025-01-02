State and Explain the components of a DBMS(Database Management System)
A Database Management System (DBMS) consists of several key components, which work together to manage and manipulate databases:

Database Engine: The core component of a DBMS, responsible for data storage, retrieval, and manipulation. It interacts with the database to perform operations such as reading, writing, and updating data.

Database Schema: This defines the structure of the database, including tables, fields, relationships, views, indexes, and other database objects. The schema acts as a blueprint for the database.

Query Processor: This component interprets and executes database queries. It optimizes the execution of queries and translates SQL commands into an execution plan for the database engine.

DBMS Utilities: These are tools that help manage and maintain the database, such as backup and recovery tools, performance tuning utilities, and tools for managing users and permissions.

Data Dictionary: A repository that stores metadata, or data about the data. It contains information about the structure of the database, data types, constraints, relationships, and access control details.

Transaction Management: Ensures that database transactions are processed reliably and securely, following the ACID properties (Atomicity, Consistency, Isolation, Durability).

User Interface: This allows users to interact with the database, whether through command-line interfaces or graphical interfaces, to execute queries, retrieve data, and modify the database.
What is a relational database? Give 4 examples.
A Relational Database is a type of database that stores data in tables (also called relations) and uses relationships between tables to organize and structure the data. Data in a relational database is stored in rows and columns, with each row representing a record, and each column representing a field of data.

Examples of relational databases:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
State and Explain three classifications of SQL?
Data Definition Language (DDL): This type of SQL deals with defining and modifying the structure of the database. It includes commands like:

CREATE: To create tables, databases, views, and indexes.
ALTER: To modify the structure of existing tables.
DROP: To delete tables or databases.
Data Manipulation Language (DML): This category of SQL is used to manipulate data in the database. It includes commands like:

SELECT: To retrieve data from tables.
INSERT: To insert new records into tables.
UPDATE: To modify existing records.
DELETE: To remove records from tables.
Data Control Language (DCL): DCL is used to control access to the data in the database. It includes commands like:

GRANT: To give permissions to users.
REVOKE: To remove permissions from users.
What is the difference between a Primary Key and a Foreign Key?
Primary Key: A primary key is a unique identifier for a record in a database table. It ensures that each record can be uniquely identified. A primary key cannot have NULL values and must contain unique values for every row in the table.
Example: A table of "Employees" might have an EmployeeID as the primary key.
Foreign Key: A foreign key is a field in one table that is used to reference the primary key in another table. It creates a relationship between two tables. A foreign key can have duplicate values and can contain NULL values.
Example: An "Orders" table might have a CustomerID as a foreign key, referencing the CustomerID in the "Customers" table.

What is an Entity-Relationship Diagram?
An Entity-Relationship (ER) Diagram is a visual representation of the entities within a system and the relationships between them. It is used in database design to depict how data entities are related to each other.

Entities represent objects or things in the system (e.g., Customer, Order, Product).
Attributes represent data that describe the entities (e.g., CustomerName, ProductPrice).
Relationships show how entities are related (e.g., Customer places Order, Order contains Product).

What are the advantages of relational databases?
Data Integrity: Relational databases enforce data integrity constraints like unique keys, foreign keys, and not null constraints, ensuring accurate and consistent data.

Flexibility: Changes in the database schema, such as adding or removing columns, can be done easily without affecting the existing data.


State four types of data type used to store data in tables?
Integer: Used to store whole numbers without decimal points.

Example: AGE INT
Varchar (Variable Character): Used to store variable-length text strings.

Example: Name VARCHAR(255)
Date: Used to store date values (year, month, day).

Example: DateOfBirth DATE
Decimal: Used to store exact numeric values with a fixed number of decimal places.

Example: Price DECIMAL(10,2)
What is the purpose of a database management system (DBMS)?
The primary purpose of a DBMS is to manage and organize data in a way that ensures:

Efficient Data Storage and Retrieval: A DBMS allows for fast access, retrieval, and manipulation of data.

Data Integrity and Consistency: A DBMS enforces constraints and rules that ensure data remains accurate and consistent.

Data Security: A DBMS provides features like access control and user authentication to ensure that only authorized users can interact with sensitive data.
