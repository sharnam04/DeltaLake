# 🚀 Delta Lake - Hands-on Learning with Databricks

This repository contains my hands-on practice of **Delta Lake** concepts using **Databricks**, following the Delta Lake tutorial series by **Ansh Lamba**.

Rather than only watching the videos, I implemented every concept side-by-side in Databricks notebooks to gain practical experience.

---

## 📌 Technologies Used

- Databricks
- Apache Spark
- PySpark
- Delta Lake
- SQL
- Unity Catalog

---

# Repository Structure

| Notebook | Topics Covered |
|----------|----------------|
| 📒 1_DeltaLake.ipynb | Creating Delta Tables using SQL API and Delta API |
| 📒 2_DeltaLake.ipynb | Delta Transaction Log (`_delta_log`), ACID Transactions, Reading Transaction Logs |
| 📒 3_DeltaLake.ipynb | Schema Enforcement & Schema Evolution (`mergeSchema`) |
| 📒 4_DeltaLake.ipynb | Delta DML Operations (UPDATE, DELETE, MERGE) |
| 📒 5_DeltaLake.ipynb | Column Mapping, Column Rename, Column Drop |
| 📒 6_DeltaLake.ipynb | Delta Utility Commands (DESCRIBE DETAIL, HISTORY, EXTENDED) |
| 📒 7_DeltaLake.ipynb | Change Data Feed (CDF) |
| 📒 8_DeltaLake.ipynb | Delta Uniform (Universal Format / Iceberg Compatibility) |
| 📒 9_DeltaLake.ipynb | Delta Optimization (OPTIMIZE, File Compaction) |

---

# Notebook Details

---

## 📒 Notebook 1 - Creating Delta Tables

Topics Covered

- Create Delta Tables using SQL
- Create Delta Tables using Delta API
- Managed Tables
- Delta Table Storage
- Reading Delta Tables

Key Concepts

- CREATE TABLE
- USING DELTA
- Data Persistence

---

## 📒 Notebook 2 - Delta Transaction Log

Topics Covered

- Writing data into Delta format
- Reading Delta Tables
- Understanding `_delta_log`
- JSON Transaction Files

Key Concepts

- ACID Transactions
- Commit Logs
- Metadata Tracking

---

## 📒 Notebook 3 - Schema Management

Topics Covered

### Schema Enforcement

- Prevent invalid schema writes

### Schema Evolution

- mergeSchema option
- Adding new columns

Key Concepts

- Schema Validation
- Automatic Schema Evolution

---

## 📒 Notebook 4 - Delta DML Operations

Topics Covered

- UPDATE
- DELETE
- MERGE
- INSERT

Key Concepts

- SQL DML on Delta Tables
- Upserts
- Data Modifications

---

## 📒 Notebook 5 - Column Mapping

Topics Covered

- Enable Column Mapping
- Rename Columns
- Drop Columns

Key Concepts

- Metadata-only Operations
- Column Mapping Mode

---

## 📒 Notebook 6 - Delta Utility Commands

Topics Covered

- DESCRIBE
- DESCRIBE DETAIL
- DESCRIBE EXTENDED
- DESCRIBE HISTORY

Key Concepts

- Table Metadata
- Storage Information
- Operation History

---

## 📒 Notebook 7 - Change Data Feed (CDF)

Topics Covered

- Enable CDF
- Read Changed Records
- INSERT Tracking
- UPDATE Tracking
- DELETE Tracking

Key Concepts

- Incremental Processing
- CDC Pipelines

---

## 📒 Notebook 8 - Delta Uniform

Topics Covered

- Universal Format
- Iceberg Compatibility

Key Concepts

- Cross-engine Compatibility
- Open Table Format

---

## 📒 Notebook 9 - Delta Optimization

Topics Covered

- OPTIMIZE Command
- Small File Compaction

Key Concepts

- Performance Optimization
- Efficient File Layout

---

# Delta Lake Concepts Covered

✅ ACID Transactions

✅ Delta Tables

✅ Transaction Log

✅ Schema Enforcement

✅ Schema Evolution

✅ DML Operations

✅ MERGE

✅ Change Data Feed

✅ Column Mapping

✅ Table History

✅ Table Metadata

✅ Delta Uniform

✅ Performance Optimization

---

# Learning Outcome

Through these notebooks, I gained practical understanding of:

- Delta Lake Architecture
- Delta Transaction Log
- Reliable Data Lake Design
- Incremental Data Processing
- Schema Management
- Delta Table Optimization
- Databricks SQL & PySpark Integration

---

# Reference

This repository is based on the Delta Lake learning series by **Ansh Lamba**.

The notebooks have been recreated and practiced independently for educational purposes.

---

# Author

**Sharnam Kansal**

**Data Engineer**

### Skills

- Azure Databricks
- PySpark
- SQL
- Azure Data Factory
- Microsoft Fabric
- Delta Lake
- Power BI

If you found this repository helpful, feel free to ⭐ the repository.
