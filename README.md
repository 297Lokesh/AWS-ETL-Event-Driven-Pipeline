Project Description 

1.Developed a serverless, event-driven data processing pipeline on AWS.
2.Raw JSON data is uploaded into an Amazon S3 bucket.
3.S3 upload event automatically triggers an AWS Lambda function.
4.Lambda reads and flattens the nested JSON data.
5.Flattened data is converted into Parquet format for efficient storage.
6.Generated Parquet files are stored in a destination S3 folder.
7.Storage of Parquet files triggers AWS Glue Crawler.
8.Glue Crawler scans the data and extracts metadata automatically.
9.Extracted schema is stored in the AWS Glue Data Catalog.
10.Amazon Athena is used to perform SQL queries directly on processed data in S3.
11.Enables scalable, cost-effective analytics without managing database infrastructure.
