# Data Pipelines

 - Data pipeline refers to the automated process that handles various steps like data collection, preprocessing, and feature engineering.
 - It's crucial for ensuring that data is consistently prepared, cleaned, and transformed in a manner that is optimal for training machine learning models.

# Key Components

 - **Data Collection:** data can be collected (in real-time or in batches) from databases, APIs, sensors, or web scraping, depending on the machine learning problem;
 - **Data Ingestion:** frameworks like Apache Kafka, Flume, or cloud services such as AWS Kinesis are often used to ingest data into the pipeline;
 - **Data Preprocessing:** removal of outliers, handling missing values, normalizing data, and creation of new features from raw data are examples of preprocessing that can be done into the pipeline;
 - **Data Storage:** data is often temporarily stored in data lakes or databases, before being transformed to a format ready for model training, such as CSV files, Parquet files, or database tables.

# Challenges in Replicability

 - In production, new data must be processed through similar scripts to maintain consistency with development data;
 - Replicability is crucial to ensure the machine learning algorithm performs as expected in production.

# Phase-Dependent Effort

 - **Proof of Concept Phase:**
    - Focus on getting the prototype to work rather than ensuring full replicability.
    - Keep extensive notes and comments to help replicate preprocessing later if needed.
 - **Production Phase:**
    - Invest in making the data pipeline replicable.
    - Use sophisticated tools that offers the ability for tracking:
        - Metadata, data provenance, and lineage to ensure the integrity and traceability of data processing steps.