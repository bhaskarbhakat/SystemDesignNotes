## Types of RDBMS
- MySql
- Postgres
- MariaDB
- Microsoft SQL Server
- Oracle Database
- SQLite
- IBM Db2

# MySql
### Feature of MySql : 
```
# Customizable storage engine
# Partitioning
# Sharding
# Replication
```
 
### Storage Engine:- 

A storage engine in MySQL is responsible for how data is stored, retrieved, and managed within the database. Each storage engine has its own characteristics, capabilities, and use cases.

 1. InnoDB

    Feature: ACID compliance with row-level locking, foreign key support, crash recovery, and transaction management.

    Pros: Reliable, supports transactions, good for high-concurrency environments.

    Cons: Higher memory usage, slower for read-heavy operations compared to MyISAM.

2. MyISAM

    Feature: Table-level locking, full-text indexing, and simple storage format with fast read performance.

    Pros: Fast read performance, low memory usage.

    Cons: No transaction support, table-level locking can cause contention in write-heavy environments.

3. Memory (HEAP)

    Feature: Stores data in RAM, ideal for temporary tables and caching with fast read/write operations.

    Pros: Extremely fast read/write operations.

    Cons: Limited by RAM size, data is volatile and lost on restart.

4. NDB (Cluster)

    Feature: Distributed storage with automatic sharding, high availability, real-time performance, and redundancy.

    Pros: High availability with automatic failover, scalability by adding nodes, and real-time capabilities for demanding applications.

    Cons: Complex setup and management, higher resource usage due to redundancy and distribution.
