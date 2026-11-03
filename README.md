# Databricks-edit
Build a small retail order pipeline in Databricks. A CSV file containing orders is ingested into a Bronze Delta table, cleaned and validated into Silver, and aggregated into a Gold sales summary for reporting.
Business requirement: The sales manager wants daily sales by product category and region, while the data engineering team must retain raw data and reject invalid records.

