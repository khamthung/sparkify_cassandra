# Sparkify with Cassandra
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Datasets

There is one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:
```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```

## Overview
The Jupyter notebook demonstrate "Data modeling with Apache Cassandra" and "ETL pipeline using Python". Modeling data by creating tables in Apache Cassandra to run queries. The ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

### Part I : ETL Pipeline
Iterate through each event file in `event_data` folder to process and create a `event_data_new.csv` file in Python
Make necessary edits to Part II of the notebook template to including Apache Cassandra `CREATE` and `INSERT` statements to load processed records into relevant tables of the data model.

### Part II :Modeling NoSQL database with Apache Cassandra
1. Design each tables based on each queries to answer each question. 
2. `CREATE KEYSPACE` and `SET KEYSPACE` statements.
3. Develop `CREATE TABLE` statement for each of the tables to address each question.
4. Load the data with `INSERT` statement for each of the tables.
5. Test select statements with the correct `WHERE` clause.




