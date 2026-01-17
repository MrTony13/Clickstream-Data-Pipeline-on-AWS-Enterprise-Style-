 Amazon Athena Queries

### Setup
- Query engine: Athena v3
- Result location: s3://clickstream-enterprise-anthony/athena-results/

### Sample Queries

```sql
SELECT count(*) FROM clickstream_events;
