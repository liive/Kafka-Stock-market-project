# Stock Market Real Time Data Engineering Kafka Project


In this project we will execute End-to-End Data Engineering project on Real-Time Stock Market using Kafka


### Technologies which will be used:
* **Python** - Programming language
* **AWS (Amazon Web Services):**
  * **S3** - Simple Storage Service 
  * **Athena** - to query data in S3 files using ANSI SQL.
  * **Glue Crawler** - to create metadata that allows GLUE and ATHENA to view S3 information as database with tables. This way we can see the information that S3 has database composed of several tables.
  * **Glue Catalog** - glue crawlers are scheduled or on demand jobs that can query any given data store to extract scheme information  and store the metadata in the AWS Glue Data Catalog.
  * **EC2 instance** - is a virtual server in Amazon’s Elastic Compute Cloud (EC2)
* **Apache Kafka** - is an open source distributed event streaming platform. 

### Architecture
![paveikslas](https://user-images.githubusercontent.com/17298647/209360434-b6ec4e27-a5c6-42bc-94cc-45063c9d7260.png)


**Dataset used:**
https://github.com/liive/Kafka-Stock-market-project/blob/main/indexProcessed.csv
