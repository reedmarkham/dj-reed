# dj-reed

This repository supports a data pipeline to ingest data from Spotify API, transform data using dbt, and warehouse data in Snowflake - all orchestrated by Airflow and deployed on AWS using CDK

Sub-repositories:
* `dbt` - the dbt projects and transformations
* `mwaa` - infrastructure to implement Airflow on AWS (MWAA)
* `snowflake` - infrastructure to implement Snowflake as the data warehouse
