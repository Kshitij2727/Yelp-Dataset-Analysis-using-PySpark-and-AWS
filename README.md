# Yelp-Dataset-Analysis-using-PySpark-and-AWS
This repo contains project for Yelp dataset analysis using PySpark and AWS

-----------------
Business Overview
-----------------
Azure Databricks is a data analytics tool tailored for the Microsoft Azure cloud services platform. In massive data pipelines, raw and structured data is imported into Azure in batches via Azure Data Factory or streamed near real-time via Apache Kafka, Event Hub, or IoT Hub. This data is stored in a data lake for long-term sustained storage, either in Azure Blob Storage or Azure Data Lake Storage. Azure Databricks is utilized to read data from different data sources and transform it into breakthrough insights using Spark as part of the analytics workflow.

Yelp is a community review site and an American multinational firm based in San Francisco, California. It publishes crowd-sourced reviews of local businesses as well as the online reservation service Yelp Reservations. Yelp has made a portion of their data available in order to launch a new activity called the Yelp Dataset Challenge, which allows anyone to do research or analysis to find what insights are buried in their data. Due to the bulk of the data, this project only selects a subset of Yelp data in a zip file named 'dataset.zip,' which comprises three JSON files, including 'business.json', which provides business data such as location data, attributes, and categories.

--------
Approach
--------

-   Read yelp datasets from AWS S3.

-   Convert from JSON to parquet format for better performance.

-   Total records in each dataset.

-   repartition() vs coalesce()

-   Find the top users based on their total number of reviews.

-   Analyse the top 10 categories by a number of reviews.

-   Analyse top businesses which have over 1000 reviews.

-   Analyse Business Data: Number of restaurants per state.

-   Analyze the top 3 restaurants in each state.

-   List the top restaurants in the state 'NV' by the number of reviews.

-   Find year wise total number of tips and order in descending order of total tips. 

-   Broadcast Join: restaurants as per review ratings.


----------
Tech Stack
----------

➔ Language: Python3

➔ MPP Engine : Spark

➔ Services: AWS S3, EMR , Notebooks , IAM - User, Roles, Policies
