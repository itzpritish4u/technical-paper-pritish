# NoSQL Database Investigation to Improve Performance
As scaling and performance problems continue happening with our project, it's high time some alternative solutions are contemplated concerning databases. Because of the flexibility, scalability, and enhancement in performance, NoSQL databases have been getting much attention since they work with huge data sets and large-scale distributed systems. Further on, I probe into five different NoSQL databases, mentioning use cases and advantages that can be gained concerning performance.

## MongoDB
MongoDB is a NoSQL, document-oriented database. Data is stored in flexible, JSON-like documents. It allows, therefore, for the management of unstructured data. Among its well-known use cases are applications which must support high levels of availability and scaling. It has a schema-less structure; as such, it is subject to changes while the application requirements keep changing. MongoDB does support horizontal scaling, hence can be suitable for large-scale applications with heavy loads.

## Cassandra
Cassandra is a NoSQL wide-column store database. Cassandra has been designed for high availability and to handle huge volumes of data across distributed servers. With its peer-to-peer architecture, Cassandra is highly fault-tolerant and hence very apt in IoT systems with requirements of low latency and high availability, as well as in time-series data applications.

## Redis
Redis is an in-memory key-value store known for its performance at very high speeds with low-latency operations. Because the data resides in memory, Redis is ideal for real-time applications such as caching and session management. It also features several kinds of data structures, including strings, lists, sets, and hashes, thereby making it versatile for all kinds of use cases.

## Couchbase
Couchbase is a document-oriented NoSQL database that marries the flexibility and expressiveness of JSON data storage with the power of a SQL-like query language called N1QL. It provides robust indexing, high performance, and real-time analytics. Couchbase provides the synchronization feature, therefore it's used in mobile and web applications because of its capability of high availability in distributed environments. 

## DynamoDB
DynamoDB is the fully managed AWS key-value and document-oriented NoSQL database that automatically scales the throughput capacity and storage to meet the demand of an application, which allows highly scalable web applications. It also seamlessly integrates with other AWS services, making it ideal for cloud-native solutions.

## References
[MongoDB - NoSQL Explained](https://www.mongodb.com/resources/basics/databases/nosql-explained)

[Cassandra - Apache](https://cassandra.apache.org/_/index.html)

[Redis Documentation](https://redis.io/docs/latest/operate/rc/)

[Couchbase Official](https://www.couchbase.com/)

[DynamoDB - AWS](https://aws.amazon.com/dynamodb/)