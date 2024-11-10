**How to approach a database:**
	Requirements
		ERD
	Implementation
		The code
	Evaluation
		Testing and assessing against business requirements

- RDB - relational database, a collective set of multiple data sets organised by tables, records and columns 
    
- SQL -  Structured Query Language, the language used to query relational databases
    
- Tuple- row in an RDB
    
- Column - represents specific attribute or field of that record
    
- DBMS - database management system, designed to interact with end-users, applications and the database itself to capture and analyse data
    
- ACID - atomicity, consistency, isolation and durability
    
- Tables: The primary building blocks, tables store data in a structured format. Each table holds data for a specific object, like "Customers" or "Orders."
    
- Columns - Each table is made up of columns, (aka fields). These define the type of data that can be stored, such as integers, text, or dates.
    
- Rows or Records - Each row in a table is a record. It is a single instance that contains data for each field in the table.
    
- Primary Key (PK) - This is a unique identifier for a record in a table. No two records can have the same primary key, ensuring data integrity and enabling quick data retrieval.
    
- Foreign Key (FK) - Used to establish relationships between tables, a foreign key in one table refers to the primary key of another table. This helps maintain referential integrity.
    
- Composite key (PK/FK)- a type of key that consists of two or more attributes or columns to uniquely identify a record in a table. It is used in an intersection table to break up a many-to-many relationship
    
- Index - This is a data structure that improves the speed of data retrieval operations. Indexes can be created on one or multiple columns.
    
- Schema - The blueprint of the database, the schema defines the structure, including tables, fields, and the relationships between them.
    
- Constraints- Rules applied to columns to maintain data integrity, such as "NOT NULL," "UNIQUE," or "CHECK" constraints.
    
- Data Dictionary - Also known as the system catalogue, this holds metadata like table definitions, field data types, and other properties of the database.
    
- Views - These are virtual tables that provide a layer of security and abstraction, presenting data in a specific way without changing the underlying data.
    
- Triggers and Stored Procedures - These are sets of SQL statements that are stored and can be executed on the database server to enforce business rules or automate tasks.
    
- Entity - a thing or an object that is distinguishable from all other objects
    
- ERD - entity relationship diagram, shows the cardinality between entities
    
- Cardinalities - one to one, one to many, many to many, zero 
    
- Candidate key - a minimal super key (a key that doesn’t obtain a subset of attributes that is itself a super key)
    
- Attributes - specific data elements that define properties of an entity 
    
- Data types - define the nature of the data that can be stored and manipulated, they are important from ensuring data integrity in a database 
    
- Normalisation - a systematic approach to designing database in a way that reduces data redundancy and improves data integrity
    
- Denormalisation - database optimisation technique in which redundant data is added to speed up complex queries 
    
- Database constraints - a set of rules that are used to maintain the quality, integrity and accuracy of the data in a database 
    
- Primary Key Constraint - This ensures that a column (or a combination of two or more columns) has a unique value and none of its values are null. It uniquely identifies each record in a table.
    
- Foreign Key Constraint - This is used to prevent actions that would destroy the links between tables. It maintains the referential integrity of data.
    
- Unique Constraint - This ensures that all values in a column are different. Unlike primary keys, they do not imply a sort order.
    
- Check Constraint - This allows specifying a condition on each row in a table. It provides a way to limit the kind of data that can be stored in a table by ensuring that expressions for a column return a Boolean value.
    
- Not Null Constraint - This enforces a column to not accept null values, ensuring that a value is always present.
    

- DQL - data query language, used for querying the database to retrieve information, mostly using SELECT
    
- DML - data manipulation language, used for inserting, updating, deleting and managing data within database objects, predominantly uses to INSERT, UPDATE and DELETE
    
- DDL - Data definition language, used for defining and modifying the database structure and schema, predominantly using CREATE, ALTER and DROP
    
- Data control language-used for controlling access to the data in the database, predominantly uses GRANT and REVOKE
    
- PoLP - principle of the least privilege, ensures that user and applications have only the minimum levels of access needed to perform their tasks 
    
- RBAC - role based access control, defining roles within the organisation and assign permissions to these roles rather than to individual users
    
- Data sanitation - input/insert validation
    
- Sanitisation- cleanses input data, removing potentially harmful characters or patterns that could be used in an injection attack
    
- Symmetric encryption - uses a single key for both encryption and decryption 
    
- Asymmetric encryption - employs a pair of keys, a public key for encryption and a private key for decryption 
    
- Homomorphic encryption - allows computations on encrypted data providing results without ever decrypting the data 
    
- Pgcrypto - enables PostgreSQL with cryptographic functionality, facilitating encryption/ decryption and secure storage of data directly within the database
    
- PGP_SYM - ideal for encrypting text data with a passphrase, making it user-friendly 
    
- AES- suitable for encrypting large volumes of data efficiently 
    
- Hashing- a one-way process used for verifying the integrity of data. The same input always produces the same output 
    
- Encryption- a two-way process that allows data to be made unreadable via encryption and then return to its original readable form via decryption with a specific key 
    
- Crypt - function used to hash password
    
- BF- blowfish, the algorithm used by bcrypt which is highly secure due to its adaptive cost factor 
    
- MD5 - an older hashing algorithm that is faster but significantly less secure than blowfish
    
- DES - (data encryption standard), is considered obsolete for most purposes due to its short key length which makes it vulnerable to brute force attacks
    
- XDES - (extended DES) which offers better security through a configurable number of encryption rounds
    
- Salt - a random sequence of characters added to the input of a hash function along with the password. The same password with different salts will produce different hashes  
    
- Redundancy - poor design often leads to unnecessary duplication of data across the database 
    
- Update anomalies - changes to data in one part of the database can inadvertently lead to inconsistencies elsewhere in the database
    
- Crucial optimisation - aimed at reducing the time and resources required to execute SQL queries 
    
- Full backup - copies all data from the database 
    
- Incremental backup - only backs up the data that has been changed since the last backup
    
- Differential backup - captures the changes made since the last full backup, each differential backup grows in size as it accumulates all changes since the last full backup
    
- C:\Users\.... - local machine level 
    
- username@hostname - server level, a green prompter and a $ sign
    
- username=# -database level, a white prompter with =# sign
    
- LEFT JOIN - combines rows from two or more tables based on a related column between them. It includes all rows from the left table including any matching rows from the right table 
    
- RIGHT JOIN - combines rows from two or more tables based on a related column between them. It includes all rows from the right table 
    
- FULL JOIN - combines rows from two or more tables based on a related column between them. It includes all rows from both tables, when there is a match in both columns, it combines the matched rows into a single row. If there is no match, the result will still show every row from both tables but with NULL in the columns from the table that lacks a corresponding match 
    
- Filtering - a process used to identify and isolate specific sets of data based on predefined criteria. Filtering allows users to narrow down a large dataset by applying conditions, to present only the data that meets those particular conditions 
    

Condition - a criterion or set of criteria that specify which data should be selected or manipulated within a database. Conditions are used in various database operations, such as queries, filters, and joins, to select to exclude records based on certain criteria**