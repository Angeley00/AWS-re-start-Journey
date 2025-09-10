**What is a Database?**
- A structured collection of data.
- Cloud databases are managed services , meaning there is no need to handle hardware, patching, backups.
- AWS offers relational, non-relational, in-memory, graph, and time-series databases.

**Types of Databases**
  
*Relational Databases (SQL)*
- Store data in tables with rows and columns.
- Use SQL for queries.
- Good for structured data, transactions, strong consistency.
- AWS Service → Amazon RDS (Relational Database Service)
- Supports MySQL, PostgreSQL, MariaDB, Oracle, SQL Server, and Aurora.
- Handles backups, patching, scaling.
- Multi-AZ for high availability.

*Non-Relational Databases (NoSQL)*
- Store data in flexible formats (key-value, documents, graphs).
- Good for unstructured/semi-structured data, scalability.
- AWS Service → DynamoDB
- Fully managed, serverless, low-latency key-value/NoSQL DB.
- Automatic scaling.
- Global Tables for multi-region.

*Data Warehousing*
- Store & analyze large volumes of data for BI (business intelligence).
- Optimized for queries, not transactions.
- AWS Service → Amazon Redshift
- Columnar storage.

**Database Use Cases**
- RDS/Aurora → Traditional apps, e-commerce, financial systems.
- DynamoDB → Serverless, IoT apps, gaming, mobile apps.
- Redshift → Business analytics, reporting.

**Best Practices**
- Choose the right DB type for workload.
- Use Multi-AZ for availability, Read Replicas for scaling.
- Encrypt data with KMS.
- Monitor with CloudWatch and Performance Insights.
- Automate backups and use snapshots.
- Integrates with BI tools (QuickSight).

**Reflection**

I realized the importance of selecting the right storage type to balance cost, performance and access speed and how lifecycle policies and encryption further optimize storage management.
