# Databases

## Types
- self-managed
- SQL (relational)
- NoSQL (not only SQL)

## Structured Data
- can be queried by row and column for example

## Unstructured Data
- use some key identify, such as name, to find someone

## SQL
- contains tables interconnected by keys
- a change in one table may have to reflect in another table
- tend to collect data into grouping and structures
- relationships with the stores

## NoSQL
- different data relationships
- used for simple but specific needs for data
- blobs data together and looks for an attribute based on a key

## Relational Database Server (RDS)
- Managed SQL Service
- Good for transactional processing
- Built before the cloud era
- Hard to grow in size and performance
- Has 4 flavors (MySQL, MariaDB, PostgreSQL, Oracle)

## Aurora (Really RDS Aurora)
- managed service for databases
- cloud native
- amazons cloud optimized version of MySQL and PostgreSQL
- grows easier
- higher capacity

## Aurora Serverless v2
- capacity can go up and down much easier than other RDS services
- don't pay for compute when you are not using it

## Amazon Redshift
- Data Warehouse not a transactional data store
- just structured data
- for reporting
- has serverless version

## NoSQL Stores

## DynamoDB
- King of key-value at AWS
- search for key and get attributes for that key

## DocumentDB
- want to store data and retrieve documents
- has a hierarchy
- mongoDB for aws

## Keyspaces (Cassandra Compatibility)
- unstructured data ran across entire planet

## Neptune
- database that will detect relationships between data like fraud detection or social network relationships
- graph database

## ElastiCache
- used to cache expensive queries
- lowers latency

## OpenSearch
- the service you use when search is the most important thing

## Amazon Quantum Ledger Database
- everytime a change is made, it creates a record
- immutable records

## Timestream
- captures data from various sources at high scale and maintains the timestamp