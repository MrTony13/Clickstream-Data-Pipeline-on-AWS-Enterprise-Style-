# Clickstream-Data-Pipeline-on-AWS-Enterprise-Style-
This project demonstrates a production-style clickstream data ingestion and analytics pipeline using AWS managed services.  The architecture simulates how real-world web or mobile clickstream events are ingested, stored, cataloged, and queried at scale.



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
