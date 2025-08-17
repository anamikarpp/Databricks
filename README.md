# Delta Lake Tutorial on Azure Databricks

This repository accompanies the *Azure Databricks Delta Lake* tutorial, demonstrating essential features of Delta Lake on the Databricks platform.

## Overview

The tutorial covers:

1. **Dataset Preparation**  
   - Download the *People 10 M* CSV dataset from Kaggle.  
   - Upload it to a Unity Catalog volume in your Databricks workspace.  

2. **Creating a Delta Table**  
   - Read the CSV using a defined schema.  
   - Write to create a managed Delta table (e.g., `main.default.people_10m`).  

3. **Upsert (MERGE)**  
   - Use DeltaTable APIs or SQL MERGE to update existing records or insert new ones.  

4. **Reading & History**  
   - Query the Delta table using DataFrame or SQL.  
   - Retrieve version history using `DESCRIBE HISTORY` or `DeltaTable.history()`.  

5. **Time Travel**  
   - Query earlier versions of the table using version number or timestamp.  

6. **Optimize & Z-Order**  
   - Run `OPTIMIZE` and optionally `ZORDER BY` to improve query speed.  

7. **VACUUM**  
   - Clean up obsolete data files using `VACUUM`.  
