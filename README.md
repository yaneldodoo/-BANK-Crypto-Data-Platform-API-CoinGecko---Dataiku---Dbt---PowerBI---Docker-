# # # Crypto Data Platform (CoinGecko)

I am building a complete end-to-end data platform using the CoinGecko API.

# # Goal

My goal is to replicate a real-world data engineering system used in companies.

# # This project allows me to:

automatically collect cryptocurrency market data
store and historize data over time
transform raw data into analytical datasets
automate the full data pipeline
build dashboards to analyze market trends
Career Objective

# # This project helps me position myself for roles such as:

Junior Data Engineer
Analytics Engineer
Data roles in banking or Big 4 consulting firms

# # # I want to demonstrate that I can design and operate a full data pipeline end-to-end.

##  System Architecture

CoinGecko API
↓
Dataiku (workflow orchestration and scheduling)
↓
Python (data ingestion layer)
↓
DuckDB (raw data storage)
↓
dbt (data transformation layer)
↓
Power BI (dashboard and visualization layer)

##  Tech Stack
# 1. Data Source

I use the CoinGecko API to collect cryptocurrency market data such as prices, volume, and market capitalization.

# 2. Orchestration Layer

I use Dataiku to manage and automate workflows.

It allows me to:

schedule pipelines
automate execution
monitor pipeline runs
# 3. Data Ingestion

I use Python to extract data from the API.

This includes:

API requests
basic data cleaning
loading data into storage
# 4. Storage Layer

I use DuckDB to store raw data and maintain historical records.

# 5. Transformation Layer

I use dbt to transform data using SQL.

I build:

staging models for data cleaning
analytical models (marts)
business KPIs
# 6. Visualization Layer

I use Power BI to build dashboards that help analyze:

market trends
price evolution
top-performing cryptocurrencies
volatility patterns
# 7. Infrastructure (Bonus)

I containerize the entire project using Docker to make it reproducible and production-like.

# # Final Outcome

At the end, I have a complete data platform that works like a real company system:

automated data ingestion
structured data pipeline
SQL-based transformations
business dashboards
What This Demonstrates
