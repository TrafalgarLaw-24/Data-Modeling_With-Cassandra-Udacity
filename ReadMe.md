# Sparkify Cassandra
This project consists of the following concepts:
- Data modeling with Cassandra
- ETL pipeline using Python

## Project Summary

The objective of this project is to create a NoSQL analytics database in Apache Cassandra for a music streaming service called Sparkify which is fictional. Sparkify's analytics team seeks to understand how users are playing songs on the company's music app. The analysts need an easy way to query and analyze the songplay data, which is currently stored in raw csv files on a local directory.

I have implemented an ETL pipeline in python to pre-process the data using pandas. The database tables are modeled on the queries according to the principle of one table per query. I selected the primary and clustering keys for each table in order to ensure a unique identifier for each row.  

## Project structure
1. **event_data** where all needed data reside.
2. **Project_1B_ Project_Template.ipynb** The code.
3. **event_datafile_new.csv** a smaller event data csv file that will be used to insert data into the Apache Cassandra tables.
4. **images** a screenshot of what the denormalized data should appear like in the event_datafile_new.csv.
5. **README.md** current file, provides discussion on my project.

## How to Use

Launch **Project_1B_ Project_Template.ipynb** to run validation and example queries.

------------------------
