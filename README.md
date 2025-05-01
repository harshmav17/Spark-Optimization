# Spark-Optimization

# 🚀 Spark Optimization Techniques

This repository contains a collection of Databricks notebooks demonstrating various **Apache Spark optimization techniques**. These examples are essential for improving performance, reducing costs, and ensuring scalability when working with large-scale data pipelines using Spark and Delta Lake.

---

## 📂 Notebook Index

| Notebook | Description |
|----------|-------------|
| **AQE** | Demonstrates Adaptive Query Execution, which dynamically optimizes query plans at runtime. |
| **Broadcast Variable** | Explains how broadcast variables can reduce data shuffling during joins. |
| **CACHING AND PERSISTENCE** | Discusses strategies for caching and persisting DataFrames to optimize repeated computations. |
| **DELTA LAKE OPTIMIZATION** | Shows how Delta Lake optimizations (Z-Ordering, Optimize command, etc.) improve query speed and storage. |
| **Dynamic Partition Pruning** | Covers partition pruning techniques that enable efficient querying on large partitioned tables. |
| **Optimize Joins** | Reviews best practices for join types and their performance impact in Spark. |
| **SALTING JOINS (BONUS)** | A bonus notebook on using salting techniques to handle data skew in joins. |
| **SALTING** | Details the salting pattern to prevent partition skew during aggregations or joins. |
| **Scanning Optimization** | Explores techniques to reduce file scanning overhead and improve query latency. |
| **SPARK SQL Hints** | Demonstrates how to use SQL hints to guide the Spark optimizer for better performance. |

---

## 🛠️ Technologies Used

- Apache Spark (PySpark)
- Databricks Community Edition
- Delta Lake

---
