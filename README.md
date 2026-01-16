# Retail-Sales-Relational-Database-System
A normalized relational database system for retail sales analysis, built with SQL and Python. Includes ERD design, 3NF schema implementation, data cleaning, a Tkinter GUI, and cloud scalability considerations using AWS.

Overview

This project focuses on the design and implementation of a normalized relational database for retail sales analysis. The system efficiently stores and manages sales transactions alongside store attributes, departmental data, external economic indicators, and management information. It is designed to support accurate reporting, data integrity, and scalable analytics.

Objectives

Design a structured retail database to support sales and performance analysis

Reduce data redundancy through normalization

Ensure data consistency using relational constraints

Enable efficient querying and reporting of retail metrics

Project Workflow

Requirements Analysis
Identified key retail entities including stores, departments, sales transactions, store features (economic and environmental factors), and managers.
Database Design & Normalization
Developed an Entity Relationship Diagram (ERD) and normalized the schema to Third Normal Form (3NF) to eliminate redundancy and prevent update anomalies.
Schema Implementation
Implemented the database using SQL with clearly defined:
Primary and foreign keys
NOT NULL, CHECK, and UNIQUE constraints
Referential integrity across all tables
Data Cleaning & Preparation
Cleaned input datasets by handling missing values using df.dropna() prior to database insertion to prevent integrity and loading errors.
Application Interface
Built a Tkinter-based GUI to allow users to interact with the database without direct SQL input.
Cloud Deployment Considerations
Evaluated cloud scalability using AWS services, including:
Amazon RDS for managed relational databases
Amazon S3 for data storage and backups
Amazon EC2 for application hosting
Technologies Used
SQL (Relational database design and querying)
Python (Data cleaning and GUI development)
Tkinter (Desktop GUI)
AWS (RDS, S3, EC2) – deployment and scalability considerations
Key Outcomes
Fully normalized relational database schema
Improved data integrity and query efficiency
Scalable architecture suitable for cloud deployment
User-friendly interface for database interaction
