# E-Commerce ETL Pipeline & Data Warehouse

## About Project

This project demonstrates the implementation of an end-to-end ETL (Extract, Transform, Load) pipeline using PostgreSQL. Raw e-commerce transaction data is extracted, transformed, and loaded into a Data Warehouse and Data Mart to support business reporting and analysis.

The project follows a structured data warehousing approach by separating the data into **Staging**, **Data Warehouse**, and **Data Mart** schemas.

## Portfolio Objective

This project was developed to demonstrate my ability to:

- Build an ETL pipeline using SQL and PostgreSQL.
- Design a Data Warehouse for analytical purposes.
- Transform raw transactional data into structured datasets.
- Apply Data Warehouse concepts in a real-world business scenario.

## Business Problem

Operational transaction data is designed for daily business operations rather than analytical reporting. As the volume of data grows, generating business reports directly from raw transaction tables becomes inefficient and difficult to maintain.

This project addresses the problem by building a Data Warehouse that stores cleaned and structured data, making it easier to perform business analysis and generate reports.

## Dataset

The dataset consists of e-commerce transaction records containing information such as:

- Customer
- Product
- Store
- Payment Method
- Transaction Date
- Quantity
- Price
- Total Sales

## Database Architecture

The database consists of three schemas:

### 1. Staging (`stg`)
Stores raw data before transformation.

### 2. Data Warehouse (`dwh`)
Stores cleaned and integrated dimension and fact tables.

### 3. Data Mart (`dm`)
Stores business-ready tables optimized for reporting and analysis.

## ETL Workflow

The ETL pipeline consists of three main stages:

### 1. Extract
Raw transaction data is imported into the staging area.

### 2. Transform
The data is cleaned, standardized, and transformed into dimension and fact tables.

### 3. Load
Processed data is loaded into the Data Warehouse and Data Mart using PostgreSQL Stored Procedures.

## Tools
- PostgreSQL
- SQL
- DBeaver

## Skills Demonstrated

- SQL Programming
- ETL Pipeline Development
- Data Cleaning
- Data Transformation
- Data Warehouse Design
- Data Mart Design
- Stored Procedures
- Database Management

## Key Insights

By transforming raw transaction data into a structured Data Warehouse and Data Mart, the data becomes:

- Easier to analyze for business reporting.
- More consistent and standardized.
- Better suited for analytical queries compared to raw operational data.

