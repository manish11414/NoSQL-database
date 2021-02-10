# NoSQL Database


NoSQL database is a non-relational data management system, that does not require a fixed schemas. It avoids joins, and is easy to scale. It includes simplicity of design, simpler horizontal scaling to cluster of machines and final control over availability.

#### There are 4 types of NoSQL database available
##### 1. Document based:
  Stores data in JSON, BSON, or XML documents
##### 2. Key-value stores:
 Stores data as a key value pair consisting of an attribute name and a value.
#####  3. Column-oriented database: 
In this database, Data is stored in cells group in columns of data rather than as row of data
#####  4. Graph databases:
Each element is stored as a node and nodes are connected to each other.

### NoSQL databses for increasing performance and scaling

##### 1. MongoDB:
It the most uses NoSQL database. it stores data in JSON, BSON, or XML documents. It provides ad-hoc queries optimization that make a significant difference at scale, when thousands to missions of variables may need to be considered.
##### 2. CouchDB:
It is also a document storage database. It provides the simplest form of replication and an interface Futon which facilitates a browser based GUI to handle our data, permission and configuration. It is also follow the ACID property of the transection.

##### 3. Redis:
It is the part of key-value database of NoSQL. It stores the data in the form of key-value. It's uses its own hashing mechanism that is called Redis Hashing. It allows to load millions of pieces of data into the cache within a short period of time.

##### 4. HBase:
It is a column-oriented database that provides dynamic database schema. It provides the Schema-less so there is no concept of fixed columns schema and internally uses hash tables and offers random access. It is also perform real-time query processing and scalability.

##### 5. Neo4j: 
It is a graph database that support full ACID properties and it facilitates to scale the database by increasing the number of reads/writes, and the volume without affecting the data integrity and speed of query processing.