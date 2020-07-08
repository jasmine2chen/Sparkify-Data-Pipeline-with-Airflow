# Sparkify Data Pipeline with Airflow

## Background
Sparkify, a music streaming company, has decided to introduce more automation and monitoring to their data warehouse ETL pipelines. The data team come to the conclusion that the best tool to achieve this is Apache Airflow.

I will be creating high grade data pipelines that are dynamic and built from reusable tasks, can be monitored, and allow easy backfills. As data quality plays a big part when analyses are executed on top the data warehouse, I will run tests against the datasets after the ETL steps have been executed to catch any discrepancies in the datasets.

## Datasets
The source data resides in S3 and needs to be processed in Sparkify's data warehouse in Amazon Redshift. The source datasets consist of CSV logs that tell about user activity in the application and JSON metadata about the songs the users listen to.

S3 links  
- Log data: s3://udacity-dend/log_data 
- Song data: s3://udacity-dend/song_data
