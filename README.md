# HDInsight Labs

The following labs are currently available, before attempting any of the labs be sure you have followed the instructions in Lab Setup. When you are done with the labs, be sure to follow the instructions under Cleanup to delete your lab environment and avoid uneeded costs.

## Setup
### [Lab Setup](Setup/Environment-Setup.md): 
Follow the steps in this section to setup your environment to complete the labs.

## Labs
### [Lab 1 - Batch & ETL Processing of Big Data with Spark SQL](Labs/Lab01/Lab01.md): 
AdventureWorks is an e-commerce retailer who is looking to improve how they manage the data assets produced by their platform. As a starting point they would like collect their data in a manner that enables easier exploration and prepares the data for downstream analytics processes that can yield new insights. Adventurworks has asked you to process and prepare their flat file data into a tabular format that offers better query perfomrance and can be queried using SQL.

In the lab you will learn how to use Spark SQL (and PySpark) to batch process a 10GB text file dataset, quickly explore its content, identify issues with the data, clean and format the data and load it into Hive tables to support downstream analytics.

### [Lab 3 - Data Science using Spark](Labs/Lab03/Lab03.md):
AdventureWorks would like to add a snazzy product recommendations feature to their website and email marketing campaigns that, for every user in their system, can recommend the top 10 products they might be interested in purchasing. Adventureworks has provided you with the tables for users, products and weblogs that contains all of the data you need.

In this lab, you will train a recommendation model using Spark's built-in collaborative filtering alogrithm - Alternating Least Squares (ALS). Then you will use the model to pre-compute the user to product recommendation for every user and save this in a table. Then you will query from this table to quickly get the 10 product recommendations for a given user.

### [Lab 4 - Streaming Pattern: Processing events from Kafka using Spark and MLlib](Labs/Lab04/Lab04.md):
AdventureWorks has asked for the ability to extend their product recommendations feature, integrating the trained Alternating Least Squares (ALS) recommendation model to make predictions against streaming weblog data from Kafka.

In this lab, you will upload and run a Java .jar application to add sample weblog data into a Kafka topic, and use the same application to view the data added. You will then create a simple Kafka producer using Spark to add a few more records to the topic. Next, you will use Spark Structured Streaming to query the data, and run the streamed data against the ALS recommendation model, getting product recommendations for a given user.


### [Lab 7 - Extending the cluster with HDInsight Applications](Labs/Lab07/Lab07.md):
AdventureWorks is interested in using HDInsight applications for extending the capabilities their cluster. They are interested in two applications, H2O Sparkling Water and Apache Solr. H2O will provide machine learning and predictive analytics, while Solr will provide enterprise search capabilities.

They have provided you with the tables for users, products, and weblogs that contain all the data you need. You will build and train a deep learning model using H2O Sparkling Water, combining the capabilities of Spark with H2O. Then, you will use Solr to add search capabilities to the AdventureWorks cluster.

In this lab you will learn how to extend an existing HDInsight cluster by installing both third-party and custom applications.

## Cleanup
### [Lab Cleanup](Setup/Environment-Cleanup.md): 
When you are done with the labs be sure to follow these instructions to cleanup your Azure subscription and avoid unnecessary costs.

