# data-engineering

Portfolio of data engineering and analytics engineering projects (Databricks, Snowflake, Airflow, PySpark).

## Configuration

Credentials are read from environment variables and are never stored in this repo:

| Variable | Used by |
|---|---|
| `SNOWFLAKE_ACCOUNT`, `SNOWFLAKE_USER`, `SNOWFLAKE_PASSWORD` | RealTime-Trader-KPI-Analytics, Snowflake-car-rental-pipeline-SCD2 |
| `SNOWFLAKE_WAREHOUSE`, `SNOWFLAKE_DATABASE`, `SNOWFLAKE_SCHEMA`, `SNOWFLAKE_ROLE` (optional) | same as above |
| `NEWS_API_KEY` | news-data-analysis-snowflake-pipeline |
