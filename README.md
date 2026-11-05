# Retail Data Management using AWS Glue ETL Pipeline

## Project Overview

This course-end project demonstrates the implementation of a serverless Extract, Transform, and Load (ETL) pipeline using Amazon Web Services (AWS) Glue.

The project focuses on integrating product and transaction datasets, automating schema discovery, performing data transformations, and storing enriched output in Amazon S3.

## Project Objectives

- Build an ETL pipeline using AWS Glue.
- Store raw datasets in Amazon S3.
- Automate schema discovery using AWS Glue Crawlers.
- Manage metadata using AWS Glue Data Catalog.
- Configure IAM roles and permissions.
- Join product and transaction datasets.
- Store transformed output in Amazon S3.

## AWS Services Used

- Amazon S3
- AWS Glue
- AWS Glue Data Catalog
- AWS Glue Crawlers
- AWS Glue Classifiers
- AWS Glue Studio Visual ETL
- AWS IAM

## Implementation

1. Amazon S3 bucket creation and dataset upload.
2. Creation of product and transaction folders.
3. AWS Glue database configuration.
4. CSV classifier configuration.
5. IAM role creation and permissions.
6. AWS Glue Crawler configuration.
7. Data Catalog table generation.
8. Visual ETL pipeline development.
9. Inner join using ProductID.
10. S3 output configuration.
11. ETL job execution and output verification.

## Results

- Input and output S3 buckets created.
- Product and transaction datasets uploaded.
- Glue database and classifiers configured.
- Both crawlers executed successfully.
- Data Catalog tables generated.
- Visual ETL inner join pipeline implemented.
- Transformed output verified in Amazon S3.

## Challenges Addressed

- Invalid AWS security token.
- Insufficient source nodes in Join transformation.
- Join key configuration issues.

## Deliverable

`AWS_Glue_ETL_Report.docx`

The report contains implementation steps, explanations, screenshots, results and learning outcomes.

## Author

Raghavendra Varma

GitHub: https://github.com/Raghavendra-Varma-01

---

*Completed as part of ETL course-end project training.*
