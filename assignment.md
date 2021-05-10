# Abstract
On the basis of reliability, rational models,
huge amount of data non-relational models are much more useful. To store large
chunks of data, NoSQL databases are used. NoSQL databases are scalable and wide ranged
because they are non-relationally distributed.
In relational databases, it was not possible to manage data which involved very large number of
Big Data applications hence the concept of NoSQL database was introduced.
There are a lot of advantages of NoSQL which not only involve its own features but also some
features of relational database management system. The severe benefit of NoSQL database is that
it is an open source system which helps to adapt many numbers of features for newly generated
applications.
This investigation is focused on performance and scalling  of non-relational database to improve performance using best NoSQL database.
# NoSQL Database
NoSQL stands for “Not Only SQL” which means that this database is not only
replacing RDBMS but also harmonizing some key features to it.
NoSQL is a type of non-relational database which does not require any fixed operations unlike
relational databases. It helps in better mounting of data. Platforms such as Big Data and website
applications use NoSQL for storing their data. The naming of this database might be a little
 NoSQL databases are used in
real-time web applications and big data and their use are increasing over time. NoSQL systems are
also sometimes called Not only SQL to emphasize the fact that they may support SQL-like query
languages.
For problems such as tempo, pliability and scalability, developers usually focus on implementing
simple and easy solutions. For better understanding of key solutions, NoSQL is diversified into 4
types stated as: 
- Column 
- Key values 
- Documents 
- Graphs 

 On the basis of type and requirement,
selection of the following can be done accordingly. There is a term named transaction which is
considered to be a very tiny unit and its purpose is to handle many minute-level tasks. In order to
gain accuracy there are some properties which are to be maintained by transaction. These
properties are called **ACID** properties. **ACID** property helps to handle integrity of data and its full
time completion. Whereas, NoSQL depends on a much lighter model known as **BASE** model.
**BASE** model helps to provide flexibility to the NoSQL data so that the data might be structured
properly. 
## Advantages of NoSQL Database
- NoSQL databases can be scaled easily.
- The administrators for database are not required.
- The data which is either structured, semi structured or not at all structured can also be
stored.
- There are some databases which are unique enough to undertake hardware failures.
- The basic principles such as speed, efficiency and flexibility are obtained.
- These are the best solution to the problem of cloud databases because they can handle large
amount of data.
- The database for clouds can be handled best with NoSQL databases.
- In terms of performance and retrieving of huge chunks of Big Data, NoSQL plays a
significant role by providing methods to handle such sort of data.
- When the data of a database is been structured into a table, there may be a possibility of
high complexity faced and this could possibly slow down the system. In case of NoSQL
databases, data can be stored in structured, semi-structured and unstructured format. 
## Following are 5 NOSQL database with thier uses given below:
# 1. Apache HBase
**Apache HBase** is an open-source non-relational database modeled after of Google's BigTable distributed storage system and is supported by the Apache Software Foundation. HBase is a distributed, scalable, high-performance, versioned database. **HBase's** infrastructure is designed to store billions of rows an columns of data in loosely defined tables, such as the webtable.
Just as traditional **RDBMSs** are designed to run on top of a local file system, **HBase** is designed to work on top of the Hadoop Distributed File System **(HDFS)**. As described earlier, **HDFS** is a distributed file system that stores files as replicated blocks across multiple servers. **HDFS** lends a scalable and reliable file system back end to **HBase**
## uses of Apache HBase
- **HBase** offers multiple interfaces with which to work.
- The Java interface to **HBase** can be used in a MapReduce job. 
- **HBase** has a REST interface, which can be used to retrieve data stored in HBase through HTTP service calls.

- **HBase** is a distributed data store that can store billions of rows and columns.

- **HBase** is best suited for big-data storage, which requires fast access to multiple rows at a time for aggregations, such as summing or averaging.
- **HBase** model also allows for flexibility of adding columns to the database at any time.
- The versioning property of **HBase** is also useful to store information that changes over time, but previous versions of the data are also useful. 
- **HBase** does not support the join operation, where data from two or more tables are combined on a common column to create another table.
- **HBase's** relaxed consistency model places additional burdens on the application developer.
# 2. MongoDB 
**MongoDB** is a document-oriented database. **MongoDB** eschews the relational model in favor of a "schema-less" model, which is designed to be more flexible and mimics the way data is modeled in modern object-oriented programming languages. **MongoDB** is also designed to be scalable from the ground up, it can automatically split up data among multiple servers and balance load across servers in a cluster. **MongoDB** also allows for complex queries such as those that involve MapReduce-style aggregations and geo-spatial queries, making **MongoDB** popular as a data store for mapping-related applications. 
## uses of MongoDB
- **MongoDB** can be used to meet specific challenges for certain types of applications:

  - Large, rapidly evolving data set: **MongoDB** supports large amounts of data and has a very flexible schema-less design. For applications that evolve rapidly and require ever-changing schema, **MongoDB** may be a good choice.

  - Location-based data: **MongoDB** is unique in its ability to store and index geo-spatial data in an efficient manner. For this reason, **MongoDB** is used quite extensively for applications that use geo-spatial or map data. (Examples include booking applications, location-based services, etc)

  - Applications with a high write load: **MongoDB** has built-in support for bulk inserts and supports a high-insert rate, while having relaxed transaction safety when compared to RDBMSes.

  - High availability in an unreliable environment: **MongoDB's** architecture allows for near-instant, automatic recovery from the failure of a Node when replication is configured. This is especially useful in unreliable environments
# 3.Apache Cassandra
  **Apache Cassandra** is a fully distributed, structured key-value storage system. **Cassandra** marries the best aspects of both HBase and Amazon's set of storage techniques, referrred to as Dynamo. **Cassandra** uses the data model of HBase and the implementation architecture of Dynamo.
## uses of Apache Cassandra
- **Cassandra** is a unique data storage system with useful features, such as tunable consistency, high availability, and scalability.
- **Cassandra** is best deployed with a large number of servers, which allow users to take full advantage of these features.

- **Cassandra** is also among the most powerful for its write performance, which is in part due to its architecture and tunable consistency model.
- **Cassandra** was primarily developed for applications in the social network space, where writes are frequent and read operations are less predictable.

- it has out-of-the-box support for replicating across multiple data centers. The fault-tolerance mechanism is more dynamic in nature (compared to HBase or Hadoop) and will not mistake long latencies as failures. The schema-free data model is also good for evolving applications, where application changes may occur frequently.
# 4. Redis 
**Redis** Remote Dictionary Server)[is an in-memory data structure store, used as a distributed, in-memory key–value database, cache and message broker, with optional durability. **Redis** supports different kinds of abstract data structures, such as strings, lists, maps, sets, sorted sets, HyperLogLogs, bitmaps, streams, and spatial indexes. The project is developed and maintained by a project core team and as of 2015 is sponsored by Redis Labs. It is open-source software released under a BSD 3-clause license.
## uses of Redis
- It is blazingly fast.

- It’s a NoSql Database.So called Pun for Nerds and by Nerds of Databases.
-  Currently, it is being used by tech-giants like GitHub,Weibo, Pinterest, Snapchat, Craigslist, Digg, StackOverflow, Flickr.
- In order to save your cloud database calls and eventually saving some dollars out there, you can of course opt for caching so the **Redis**.
- It is Developer friendly and by that I mean to say that **Redis** is being supported in most of the languages (Perks of using an Open Source Technology). Languages like JavaScript, Java, Go, C, C++, C#, Python, Objective-C, PHP and almost every famous language out there has support for this.
- Last and probably the very obvious point, it is open source and stable.
# 5.Oracle NoSQL Database
Oracle NoSQL Database **(ONDB)** is a NoSQL-type distributed key-value database from Oracle Corporation. It provides transactional semantics for data manipulation, horizontal scalability, and simple administration and monitoring.
Oracle released Oracle Autonomous NoSQL Database Cloud **(OANDC)** on August 10, 2018. **OANDC** is a managed cloud service for applications that require low latency, flexible data models, and elastic scaling for dynamic workloads.
Developers focus on application development and data store requirements rather than managing back-end servers, storage expansion, cluster deployments, topology, software installation/patches/upgrades, backup, operating systems, and availability. **OANDC** scales to meet dynamic application workloads and throughput requirements.**OANDC** supports tabular model.The application can also perform an iterative non-transactional scan of all the rows in the database.
## uses of oracle NOSQL database
- Build rich, personalized user experiences with fast response times based on content customized to the individual users.

- Develop content and product catalog services that delight customers and deliver them in record time by utilizing Oracle NoSQL’s rich APIs.

- Build modern, consumer scale, and responsive apps for mobile devices.

- Detect fraudulent activity in real-time with fast response time while simultaneously processing transactions.

- Build fast and scalable IoT applications that require processing high-volume data bursts from device sensors and real-time analytics.

- Support millions of concurrent players with real-time status and game state while simultaneously retrieving or updating the game data with single-digit millisecond response times.
# conclusion
- **NOSQL** databases are flexible for faster development.
- They are simple for easier development.
- They are used a powerful query language that extend sql to **JSON**.
- They are oprate at any scale.
- they are available for always-on.
- they are globally development.
- they are better fit for Digital Economy requirment.
