# Migration Services

## Overview
**Migration Services** is an open-source [vector](https://zilliz.com/glossary/vector-embeddings) and [unstructured data](https://zilliz.com/learn/introduction-to-unstructured-data) migration tool developed **by** [Zilliz](https://zilliz.com/) based on **Apache Seatunnel**.

## Why we decided to introduce this tool
1. **Meeting the Growing Data Migration Needs:** Migration Services evolves from our Milvus Migration Service, which has successfully helped over 100 organizations migrate data between [Milvus](https://github.com/milvus-io/milvus) clusters. User demands have grown to include migrations from different [vector databases](https://zilliz.com/learn/what-is-vector-database), traditional search engines like [Elasticsearch](https://zilliz.com/comparison/milvus-vs-elastic) and Solr, [relational databases](https://zilliz.com/blog/relational-databases-vs-vector-databases), data warehouses, document databases, and even S3 and data lakes to Milvus.

2. **Supporting Real-time Data Streaming and Offline Import:** As vector database capabilities expand, users require both real-time data streaming and offline batch import options.

3. **Simplifying Unstructured Data Transformation:** Unlike traditional ETL, transforming unstructured data requires AI and model capabilities. Migration Services, in conjunction with the [Zilliz Cloud Pipelines](https://zilliz.com/zilliz-cloud-pipelines), enables vector embedding, tagging, and complex transformations, significantly reducing data cleaning costs and operational complexity.

4. **Ensuring End-to-End Data Quality:** Data integration and synchronization processes are prone to data loss and inconsistencies. Migration Services addresses these critical data quality concerns with robust monitoring and alerting mechanisms.


## Core Capabilities of Migration Services
Built on top of Apache Seatunnel, Migration Services offers:
1. Rich, extensible connectors
2. Unified stream and batch processing for real-time synchronization and offline batch imports
3. Distributed snapshot support for data consistency
4. High performance, low latency, and scalability
5. Real-time monitoring and visual management

![migration.png](docs/zilliz/migration.png)

Additionally, Migration Services introduces vector-specific capabilities such as multiple data source support, schema matching, and basic data validation. 


## Roadmap
Future roadmaps include incremental synchronization, full plus incremental modes, and more advanced data transformation capabilities.

![roadmap.png](docs/zilliz/roadmap.png)

For more details about Migration services, read our blog: 

- [**Introducing Migration Services: Efficiently Move Unstructured Data Across Platforms.**](https://zilliz.com/blog/zilliz-introduces-migration-services)
