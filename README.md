# Delta Lake Tutorial on Azure Databricks

This repository accompanies the *Azure Databricks Delta Lake* tutorial, demonstrating essential features of Delta Lake on the Databricks platform.

## Overview

The tutorial covers:

1. **Dataset Preparation**  
   - Download the *People 10 M* CSV dataset from Kaggle.  
   - Upload it to a Unity Catalog volume in your Databricks workspace.  
   :contentReference[oaicite:2]{index=2}

2. **Creating a Delta Table**  
   - Read the CSV using a defined schema.  
   - Write to create a managed Delta table (e.g., `main.default.people_10m`).  
   :contentReference[oaicite:3]{index=3}

3. **Upsert (MERGE)**  
   - Use DeltaTable APIs or SQL MERGE to update existing records or insert new ones.  
   :contentReference[oaicite:4]{index=4}

4. **Reading & History**  
   - Query the Delta table using DataFrame or SQL.  
   - Retrieve version history using `DESCRIBE HISTORY` or `DeltaTable.history()`.  
   :contentReference[oaicite:5]{index=5}

5. **Time Travel**  
   - Query earlier versions of the table using version number or timestamp.  
   :contentReference[oaicite:6]{index=6}

6. **Optimize & Z-Order**  
   - Run `OPTIMIZE` and optionally `ZORDER BY` to improve query speed.  
   :contentReference[oaicite:7]{index=7}

7. **VACUUM**  
   - Clean up obsolete data files using `VACUUM`.  
   :contentReference[oaicite:8]{index=8}
