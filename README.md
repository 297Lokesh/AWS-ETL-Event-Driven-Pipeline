Project Description 

Developed a serverless, event-driven data processing pipeline on AWS.

Raw JSON data is uploaded into an Amazon S3 bucket.

S3 upload event automatically triggers an AWS Lambda function.

Lambda reads and flattens the nested JSON data.

Flattened data is converted into Parquet format for efficient storage.

Generated Parquet files are stored in a destination S3 folder.

Storage of Parquet files triggers AWS Glue Crawler.

Glue Crawler scans the data and extracts metadata automatically.

Extracted schema is stored in the AWS Glue Data Catalog.

Amazon Athena is used to perform SQL queries directly on processed data in S3.

Enables scalable, cost-effective analytics without managing database infrastructure.
