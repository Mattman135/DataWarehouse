# ETL (Extract, Transform, Load)

## Extract
- Extraction methods: push and pull
- Extract types: full, incremental
- Extract techniques: web scraping, CDC (Change Data Capture), event based streaming, API calls, file parsing, database querying, manual data extraction

## Transform
- Data enrichment
- Data integration
- Derived columns (metacolumn)
- Data cleansing: remove duplicates, data filtering, handling missing data, handling invalid data, handling unwanted spaces, data type casting, outliers detection
- Data normalization / standardization
- Business rules and logic
- Data aggregations

## Load
- Processing types: batching, stream
- Load methods:
    - Full load: truncate and insert, upsert, drop, create, insert
    - Incremental load: upsert, append, merge
- SCD (Slowly Changing Dimensions): SCD 0 (no historization), SCD 1 (overwrite), SCD 2 (historization), SCD _
