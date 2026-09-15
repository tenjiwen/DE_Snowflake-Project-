# DE_Snowflake-Project-
Kasi Mart snowflake Project

Project Overview
The Kasi Mart Snowflake Project is a data engineering initiative focused on designing, creating, and validating a relational data warehouse for Kasi Mart using Snowflake cloud platform. The project covers setting up database structures, defining schema relations, and verifying data loading workflows across core business operational entities.

Key Features & Data Pipeline:
Database Architecture: Structured schema designed in Snowflake to manage core retail entities such as customers, orders, and products.
SQL Query Scripts: Includes end-to-end scripts in SQL QUERIES.docx for table creation, schema setup, and data ingestion.
Data Load Verification: Confirmed bulk ingestion process using visual validation proofs for:
> Customer master data (confirm_customers_load.jpg)
> Product catalog data (confirm_products_load.jpg)
> Order transactional data (confirm_orders_load.jpg & orders_loaded.jpg)

Repository Structure:
File/Entity	                 Description
-----------                  ------------
SQL QUERIES.docx	           Contains the SQL DDL/DML queries used to build tables, set up stages, and load data into Snowflake.
Snowflake Kasi-Mart DB .jpg	 Diagram/visual overview of the Kasi Mart database schema and architecture.
confirm_customers_load.jpg	 Verification screenshot confirming data ingestion into the CUSTOMERS table.
confirm_orders_load.jpg	     Verification screenshot confirming data ingestion into the ORDERS table.
confirm_products_load.jpg	   Verification screenshot confirming data ingestion into the PRODUCTS table.
orders_loaded.jpg	           Detailed query output showing loaded records within the ORDERS dataset.
README.md	                   Project overview and documentation file.
