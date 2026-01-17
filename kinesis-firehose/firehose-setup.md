Kinesis Data Firehose Configuration

### Delivery Stream
- Source: Direct PUT
- Destination: Amazon S3

### S3 Destination Settings
- Bucket: clickstream-enterprise-anthony
- Prefix: raw/
- Error prefix: failed_result/

### Buffering
- Buffer size: 1 MB
- Buffer interval: 60 seconds

### Data Format
- JSON input
- GZIP compression

### IAM
- Auto-generated IAM role with S3 write permissions
