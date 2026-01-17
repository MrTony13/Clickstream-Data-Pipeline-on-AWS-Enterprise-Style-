Issue
Athena queries failed with HIVE_CURSOR_ERROR due to corrupted GZIP files produced during Firehose ingestion.

### Root Cause
- Malformed or incomplete JSON records
- Athena failing on unreadable compressed files

### Resolution Steps
1. Identified failing file via Athena error message
2. Moved corrupted file to quarantine folder in S3
3. Updated Glue table location
4. Repaired table metadata
5. Re-ingested clean data

### Outcome
Queries executed successfully after isolating corrupted files.
