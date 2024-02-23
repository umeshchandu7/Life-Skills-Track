# NoSQL Databases

## Introduction

In this technical paper, we will explore NoSQL databases, types of NoSQL databases, their data model in brief and Advantages of each NoSQL databases.

##NoSQL databases

NoSQL databases are non-tabular databases and store data differently than relational tables. NoSQL databases are often used for big data applications where scalability is important. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. 

Features of NoSQL databases
 * Flexible Schema
 * Horizontal Scaling
 * Fast queries due to the data model
 *  Ease of use for developers
 
 based on the use case we  can choose between NoSQL databases

 ## key-value Database

  1.  A key-value databas uses a simple key-value pair method to store data. 
 1. This type of NoSQL database implements a hash table to store unique keys along with the pointers to the corresponding data values.
 1. These databases contain a simple string (the key) that is always unique and an arbitrary large data field (the value).
 1. The values can be of scalar data types such as integers or complex structures such as JSON, lists, BLOB, and so on.
 5. Key-value databases are particularly suitable when our application requires handling a large volume of small and continuous reads and writes.
 6. These databases are designed for efficient and fast access to data storage as key-value pairs.

 ## Document Database
 1. Document databases stores data in JSON, BSON, or XML documents.
 2. This data model which works as a semi-structured data model in which the records and data associated with them are stored in a single document which means this data model is not completely unstructured.
 3. These are very good in retaining existing data at massive volumes because there are absolutely no restrictions in the format and the structure of data storage. 
 4. It has built-in versioning which means as the documents grow in size there might be a chance they can grow in complexity. Versioning decreases conflicts.


## Columnar Database
1. In this data is stored in columns instead of rows.
2. In a columnar database, all the values in a column are physically grouped together.
2. The purpose of a columnar database is to efficiently write and read data to and from hard disk storage in order to speed up the time it takes to return a query.
3. It can store more data in a smaller amount of memory.
4. Columnar databases perform analytical queries faster than other database methodologies.

## Graph Database

1. This type of databases uses graph structure to store data.
2. It uses nodes, edges, and properties instead of tables or documents to represent and store data.
3. The edges represent relationships between the nodes.
4. Node represents entity like student, car etc. when relationship is your priority then go with graph database.
5. Graph databases allow users to query linked data quickly and efficiently, making them much faster than traditional relational databases.

## Time-Series Databases

Time-series databases are a type of database specifically optimized for handling time-stamped or time-series data. It organize data based on Timestamps. Each data point is associated with Timestamp indicating when it is recorded.

## References

* NoSQL Databases: [link](https://www.mongodb.com/nosql-explained)
* key-value Database: [link](https://redis.com/nosql/key-value-databases/)
* Document Database: [link](https://www.geeksforgeeks.org/document-databases-in-nosql/)
* Columnar Database: [link](https://www.techtarget.com/searchdatamanagement/definition/columnar-database)
* Graph Database: [link](https://www.geeksforgeeks.org/what-is-graph-database/)






