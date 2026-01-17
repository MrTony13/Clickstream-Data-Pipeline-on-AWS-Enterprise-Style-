 AWS Glue Data Catalog

### Database
- Name: clickstream_db

### Table
- Name: clickstream_events
- Data format: JSON
- Location: s3://clickstream-enterprise-anthony/raw/

### SerDe
- org.openx.data.jsonserde.JsonSerDe
- ignore.malformed.json = true

### Schema
- event_id (string)
- user_id (string)
- event_type (string)
- page_url (string)
- device (string)
- country (string)
- timestamp (string)
