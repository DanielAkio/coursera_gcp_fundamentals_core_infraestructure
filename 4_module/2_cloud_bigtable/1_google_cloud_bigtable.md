# cloud Bigtable is managed NoSQL

- Fully managed NoSQL, wide-column database service for terabyte applications

- Accessed using HBase API
- Native compatibility with big data, Hadoop ecosystems

# why choose Cloud Bigtable?

- Managed, scalable storage
- Data encryption in-flight and at rest
- Control access with IAM
- Bigtable drives major applications such as Google Analytics and Gmail

# Bigtable Access Patterns

- Application API
    - Data can be read from and written to Cloud Bigtable through a data service layer like Managed VMs, the HBase REST Server. Typically this will be to serve data to applications, dashboards, and data services

- Streaming
    - Data can be streamed in (written event by event) through a variety of popular stream processing frameworks like Cloud Dataflow Streaming, Spark Streaming, and Storm

- Batch Processing
    - Data can be read from and written to Cloud Bigtable through batch processes like Hadoop MapReduce, Dataflow, or Spark. Often, summarized or newly calculated data is written back to Cloud Bigtable or to a downstream database
