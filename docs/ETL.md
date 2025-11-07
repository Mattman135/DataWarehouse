# ETL (Extract, Transform, Load)

## Extract

### Extraction methods:
- Push
- Pull

### Extract types:
- Full
- Incremental

### Extract techniques: 
- Web Scraping
- CDC (Change Data Capture)
- Event based streaming
- API calls
- File parsing
- Database querying
- Manual data extraction

## Transform
- Data enrichment
- Data integration
- Derived columns (meta-columns)
  
### Data cleansing
- Remove duplicates
- Data filtering
- Handling missing data
- Handling invalid data
- Handling unwanted spaces
- Data type casting
- Outliers detection

- Data normalization / standardization
- Business rules and logic
- Data aggregations

## Load
### Processing types
- Batching
- Stream
  
### Load methods
#### Full load
- Truncate and insert
- Upsert
- Drop
- Create
- Insert
  
#### Incremental load
- Upsert
- Append
- Merge

### SCD (Slowly Changing Dimensions)
- SCD 0 (no historization)
- SCD 1 (overwrite)
- SCD 2 (historization)
- SCD _
