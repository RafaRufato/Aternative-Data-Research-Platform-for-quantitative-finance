# System Architecture

## Version
v0.1

## Purpose

This document describes the initial architecture of the Alternative Data Research Platform.

## Architecture Diagram

Diagram coming soon.

## Components

### 1. Data Source

- Alternative data providers: Carbon Arc
- Public behavioral data: Google Trends
(MVP: 1 Selected Dataset)

### 2. Data Ingestion

The ingestion layer retrieves data from the selected alternative data source and brings it into the platform for storage and processing.

For the MVP, ingestion will support one data source and one access method.

###(For students) 
#### How do we access the data?
API, CSV, database, etc.
#### How do we retrieve it?
Python script, API request, file loader, SQL query.
####What do we do immediately after retrieval?
Save the original/raw version.

### 3. Raw Data Storage
Raw data should be preserved as close as possible to how the provider delivered it.

### 4. Data Validation

### 5. Data Transformation

### 6. Structured Storage

### 7. Research Layer
What can this data tell an investor?

this layer could calculate; 

Month-over-month transaction growth
3-month moving average
Year-over-year growth
Historical percentile
Acceleration/deceleration
Deviation from historical trend

we need to answer the alternative data move before analyst revenue revisions?

## Assumptions

## Open Questions
