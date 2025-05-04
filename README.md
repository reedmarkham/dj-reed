# dj-reed

This repository supports a data pipeline implementing a medallion architecture using dbt transformations and warehousing data in Snowflake originally from Spotify API

Sub-repositories:
* `dbt` - the dbt projects and transformations
* `mwaa` - infrastructure to implement Airflow on AWS (MWAA)
* `snowflake` - infrastructure to implement Snowflake as the data warehouse