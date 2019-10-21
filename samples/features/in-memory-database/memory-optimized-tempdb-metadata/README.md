# Memory-Optimized TempDB Metadata
[Memory-Optmized TempDB Metadata](https://docs.microsoft.com/sql/relational-databases/databases/tempdb-database#memory-optimized-tempdb-metadata) was introduced in SQL Server 2019 and is a part of the In-Memory Database feature family. This feature was introduced in order to improve the scalability of highly-concurrent OLTP applications by leveraging latch-free non-durable memory-optimized tables for TempDB system tables. Enabling this feature effectively removes metadata contention - a common bottleneck for highly-concurrent TempDB workloads.

In this folder, you can find examples that help illustrate the benefits of Memory-Optmized TempDB Metadata.