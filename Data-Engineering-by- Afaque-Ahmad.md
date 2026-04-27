# Knowledge Sharing (KS) - Data Engineering - Afaque Ahmad

## Overview

* [LinkedIn post](https://www.linkedin.com/posts/afaque7117_dataengineering-interviews-activity-7452559352999174144-bq_e/)
* Author: Afaque Ahmad
  ([Afaque Ahmad on LinkeDIn](https://www.linkedin.com/in/afaque7117))
* Date: Apr. 2026

## Details

Topics I've seen frequently asked in "Senior" Data Engineering interviews for anyone w/ >= 5 years of experience. 

### Architecture and Design Patterns
* Lambda vs Kappa Architecture — when each breaks
* Medallion Architecture (Bronze / Silver / Gold)
* Data Mesh vs Centralized Platform — org + tech trade-offs
* Lakehouse Table Formats (Delta vs Iceberg vs Hudi)
* Storage Layer Decisions (Parquet vs ORC, file sizing, small-file problem)

### Distributed Systems and Performance
* Spark Internals (Catalyst, Tungsten, AQE, shuffle mechanics)
* Join Strategies at scale (Broadcast / Sort-Merge, Skew handling)
* Partitioning, Bucketing, Z-Ordering & Liquid Clustering
* Query Optimization, Execution Plans (predicate pushdown, partition pruning)
* Data Skew & Hot-Partition Mitigation

### Streaming and Real-Time
* Exactly-Once vs At-Least-Once Semantics — guarantees
* Kafka at Scale (partitioning strategy, retention, log compaction)
* Watermarking, Windowing & Late-Arriving Data
* Stateful Stream Processing (RocksDB, checkpointing, state TTL)
* Backpressure & Flow Control

### Data Modeling at Scale
* SCD Type 2 + Bitemporal Modeling
* Kimball (Star) vs Data Vault vs One Big Table
* Schema Evolution + Backward / Forward Compatibility (Avro, Protobuf)
* CDC Patterns (Debezium, log-based vs trigger-based, ordering guarantees)
* Idempotency & Deduplication (merge keys, transactional writes)

### Reliability, Governance and Cost
* Data Contracts & Schema Registry (producer-consumer trust boundary)
* Data Quality Frameworks (Great Expectations, Soda, dbt tests)
* Data Lineage & Observability
* Backfills, Replay & Reprocessing (atomic publish, idempotent pipelines)
* Cost Optimization (cluster sizing, autoscaling, caching, trade-offs)

The "senior" bar is - being tested on "opinions". 

Pick the 5 from this list you can't defend w/ a real production story.
That's your gap.
