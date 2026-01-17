## Architecture Overview

This project implements a serverless clickstream data pipeline following AWS data lake best practices.

### Data Flow
1. Clickstream events are ingested using Kinesis Data Firehose
2. Firehose delivers compressed JSON data to Amazon S3
3. AWS Glue Data Catalog stores table metadata
4. Amazon Athena queries the data directly from S3

### Design Decisions
- Serverless services were used to reduce operational overhead
- S3 serves as the durable data lake
- Athena enables SQL-based analytics without managing infrastructure
