# Database to File Formats and Data Pipeline Automation

This project demonstrates how to copy data from a PostgreSQL database to CSV, Parquet, and Avro file formats, configure schedule triggers to automate the data pipeline process.

## Prerequisites
- Python 3.x
- PostgreSQL database
- Required Python libraries:
  - pandas
  - sqlalchemy
  - fastavro
  - pyarrow
  - apscheduler
  - watchdog

## Installation
Clone the repository:
   ```bash
   git clone https://github.com/your-username/database-to-file-pipeline.git
   cd database-to-file-pipeline 

db_connection_str = 'postgresql://username:password@host:port/database_name'
src_engine = create_engine('postgresql://username:password@host:port/source_database')
dest_engine = create_engine('postgresql://username:password@host:port/destination_database')
