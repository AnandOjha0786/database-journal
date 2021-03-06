===================
Interview Questions
===================

This section provides some of the most frequently asked ``database`` interview questions.

Database Management System (DBMS)
=================================

A database management system (DBMS) is software for creating and managing databases. The DBMS provides its users and programmers with a definite way to create, retrieve, update and manage data in a database.

**What is a Relational Database?**

A relational database is a type of database that uses a structure to identify data, access data and relate it to another data in the database. It contains rows as records and columns as fields to store data in a table structure. Popular relational databases include MySQL, PostgresSQL, MariaDB, etc.


**What is a NoSQL database?**

NoSQL database unlike relational database have no schema or in better words, flexible schema. Data is typically represented in JSON document format and is not adhered to table format. Popular NoSQL databases include MongoDB, DynamoDB, Apache Cassandra, etc.


**What is a graph database?**

A graph database is a database that uses graph structures for schema representation. It uses nodes, edges, and properties to represent and data store. Popular graph databases include Neo4j, GraphQL, OrientDB, etc.


**What is a time series database?**

Time series database is a purpose built database that is optimized for handling time series data which is essentially data indexed with one of its column being a time stamp. It shows change in data values over time.


**What is a search database?**

A search-engine database is a type of database that is dedicated to the search of data content. Search-engine databases use indexes to categorize the similar characteristics among data and facilitate search capability such as full-text search, complex search expressions, search results rankings.


**What is a ledger database?**

Ledgers database are special-purpose databases that are typically used to record chain of activities or series of  financial transactions of an application. Blockchain frameworks, such as Hyperledger Fabric and Ethereum, can also be used as a ledger. 


**What is the difference between hadoop and SQL DBMS?**

Hadoop is schema on read whereas SQL is schema on write. In SQL, data is stored in logical form whereas in hadoop data is in text blob. Hadoop can scale horizontally across many nodes whereas an SQL based database is vertically scalable.


**What is an in-memory database?**

An in-memory database is a nonrelational database which stores the data in-memory (RAM) instead of persisting it on disk. The data is stored in-memory because it provides fast response times to the applications querying the data.  


Basics
======

**What is a database?**

Database is a set of data that is stored in a specific format to allow its easy accessibility. Database is a central collection of data that can be accessed through different client softwares. For example, MySQL client allows for accessing and manipulating data from MySQL database.


**What is a database model?**

Database model define how the data is stored, accessed and manipulated. For example, if the data is stored in table format with defined columns, it is referred to as the relational database model.


**What is CRUD in databases?**

CRUD is an acronym for the four basic types of database operations: Create, Read, Update, Delete. Any database application allows for one or more of these basic operations to be performed on the databse.


**What is indexing in a database?**

Index is a data structure and it can be visualized similar to an index in a book. The reader of the book simply looks up the index if he is not sure of which page contains the information he is interested in. On similar lines, database indexing is a way to efficiently perform queries on a database by minimizing the number of disk accesses in the process.


**What is Data Warehousing?**

A data warehouse is storage of data that is collected from various individual data sources which support analytical and structured querying to take some strategic decision. Efficiently using data warehouse to drive critical decisions is called data warehousing. A data warehouse is designed for analytical queries rather than for transactional queries.


**What is the difference between Redis and Memchached?**

Both Memcached and Redis serve as in-memory, key-value data stores. But Memcached in a way provides sub-set of features that Redis provides. Memcached is easy to start with and provides simple key-value cache functionality. On the other hand Redis provides queuing, pub/sub solution as well as sessions. It also provides data persistence and replication. You can store smaller sizes of data 1MB/key in Memcached whereas Redis allows you to store 512MB/key values. Memcached offers multi-threading whereas Redis is single-threaded.

Relational DBMS
===============

**What is SQL and what are the characteristics of SQL?**

* SQL is Structured Query Language, which is a used for storing, manipulating and retrieving data stored in a relational database.
* SQL is an ANSI and ISO standard computer language for creating and manipulating databases.
* SQL is very simple and easy to learn.
* A wide variery of databases are compatible with SQL as the query language
* SQL is used to define the data in the database and manipulate it when needed.


**What are the different table relationships in a relational database?**

The 3 Types of Relationships in Database Design:

* One-to-One: A row in one TableA can have only one matching row in TableB, and vice versa

* One-to-Many: TableA can have many matching rows in TableB, but a row in TableB can have only one matching row in TableA

* Many-to-Many: A row in TableA can have many matching rows in TableB, and vice versa


**What is a primary key?**

A primary key is a special column in a relational database in which all the records are unique and is a non-NULL value. Most database engines offer automatic primary key generation if not provided explicitly, for example auto-increment primary key.

**What is a unique key constrain?**

A Unique key constraint is a restriction defined for that column in the database where each row should be identifiable uniquely (non-repeating values).


**What is a foreign key in a database?**

A foreign key is a key in one table which can be mapped to the primary key of another table. Foreign key helps create relationship between two tables. Foreign key is used when we perform JOIN operation to combine data between two or more tables.


NoSQL DBMS
==========

**What are the characteristics of NoSQL databse?**

* NoSQL database offers schema free reads and writes

* NoSQL databases are easily scalable

* They use distributed computing

* They’re able to process unstructured (text blobs) and semi-structured data

