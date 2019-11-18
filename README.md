# SSIS_SQL

Transfer (with versioning) data from a product stock CSV file to SQL Server DB

## The steps is:

### 1. Truncate RAW Table
### 2. CSV to RAW Table
### 3. RAW to WRK Table
### 4. Conditional Updates on VRS
* **Sort Tables (RAW and WORK0**
* **Merge Join**
* **New Reg -> Insert**
* **Description Update -> Simple Update (overwrites)**
* **Units Update -> Update (Saves the last date and create a new reg)**
