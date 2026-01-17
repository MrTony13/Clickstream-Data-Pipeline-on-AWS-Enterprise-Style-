# Clickstream-Data-Pipeline-on-AWS-Enterprise-Style-
This project demonstrates a production-style clickstream data ingestion and analytics pipeline using AWS managed services.  The architecture simulates how real-world web or mobile clickstream events are ingested, stored, cataloged, and queried at scale.

# Clickstream Data Pipeline on AWS (Enterprise-Style)

This project demonstrates a production-style clickstream data ingestion and analytics pipeline using AWS managed services.

The architecture simulates how real-world web or mobile clickstream events are ingested, stored, cataloged, and queried at scale.

## Services Used
- Amazon S3 (Data Lake Storage)
- Amazon Kinesis Data Firehose (Streaming ingestion)
- AWS Glue Data Catalog (Schema management)
- Amazon Athena (Serverless analytics)

## Architecture Flow
Client events are streamed into Kinesis Data Firehose, delivered into Amazon S3 as compressed JSON files, cataloged using AWS Glue, and queried using Amazon Athena.

## Key Highlights
- Enterprise-grade S3 data lake layout
- Firehose buffering and compression
- Manual Glue table creation with JSON SerDe
- Athena troubleshooting and error isolation


clickstream-data-pipeline/
│
├── 00-architecture/
│   └── architecture-overview.md
│
├── 01-s3/
│   └── s3-setup.md
│
├── 02-kinesis-firehose/
│   └── firehose-setup.md
│
├── 03-glue-data-catalog/
│   └── glue-table-setup.md
│
├── 04-athena/
│   └── athena-queries.md
│
├── 05-troubleshooting/
│   └── hive-cursor-error-fix.md
│
├── screenshots/
│   ├── s3/
│   ├── firehose/
│   ├── glue/
│   ├── athena/
│
└── README.md
