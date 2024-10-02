# youtube-data-analysis-using-aws

OVERVIEW:
This project focuses on securely managing, optimizing, and analyzing structured and semi-structured YouTube video data, categorized by video types and trending metrics.

PROJECT GOALS:
Data Ingestion — Develop a system to ingest data from various sources.  
ETL System — Convert raw data into the required format through transformation processes.  
Data Lake — Establish a centralized repository to store data from multiple sources.  
Scalability — Ensure the system can scale as data volume grows.  
Cloud — Leverage AWS for processing large datasets that can't be handled locally.  
Reporting — Create a dashboard to provide insights and answer key questions raised earlier.

SERVICES USED:
Amazon S3: A scalable object storage service offering high availability, security, and performance for data management.  
AWS IAM: Identity and Access Management service enabling secure control over access to AWS resources and services.  
QuickSight: A scalable, serverless BI service powered by machine learning, designed for cloud-based analytics and reporting.  
AWS Glue: A serverless data integration tool that simplifies data discovery, preparation, and combination for analytics, machine learning, and application development.  
AWS Lambda: A serverless computing service allowing code execution without the need for server management.  
AWS Athena: An interactive query service for analyzing data directly in S3, with no need to load it into separate databases.

DATASET:
This Kaggle dataset consists of CSV files with statistics on daily trending YouTube videos spanning several months. Up to 200 trending videos are recorded daily for various regions, with each region's data stored in a separate file. The dataset includes information such as video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. It also features a category_id field, specific to each region, linked to a corresponding JSON file.
https://www.kaggle.com/datasets/datasnaek/youtube-new 
