
## Overview
This project enables seamless visualization of **DynamoDB data** in **Amazon QuickSight** using **AWS Athena** and **Lambda**. It integrates various AWS services to build an efficient data analytics pipeline.

## Features
- **DynamoDB Table Setup** with partition & sort keys
- **AWS Athena Integration** using Lambda DynamoDB Connector
- **S3 Spill Location** for Athena query results
- **IAM Role Configuration** for QuickSight access
- **Data Import & Visualization** in QuickSight (SPICE & Direct Query)
- **Custom Dashboards** with Donut Charts, Bar Charts, and Interactive Tables
- **Live Data Updates** by syncing DynamoDB changes with QuickSight
- **Cost Efficiency**: Entire setup runs at a minimal cost (**$1.30**)

## Technologies Used
- **Amazon DynamoDB**
- **AWS Lambda**
- **AWS Athena**
- **Amazon QuickSight**
- **AWS Glue**
- **Amazon S3**
