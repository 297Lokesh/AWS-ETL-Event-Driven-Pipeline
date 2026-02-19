Project Description 

This project implements a serverless, 
event-driven data processing pipeline on AWS to
automate the transformation of raw JSON data into a 
structured format for analytical querying. Incoming 
JSON files are uploaded to an Amazon S3 bucket, which
triggers an AWS Lambda function to process and flatten
the data and convert it into Parquet format. 
The generated Parquet files are stored in a destination 
S3 folder, which then triggers an AWS Glue Crawler to automatically 
extract metadata and update the Glue Data Catalog. Finally, 
Amazon Athena is used to perform SQL-based queries directly on
the processed data stored in S3, enabling efficient and scalable
data analysis without the need for database infrastructure.
