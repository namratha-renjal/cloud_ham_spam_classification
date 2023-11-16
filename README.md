# CA675 Assignment 1 Spam Detection System


## Spam detection system

The aim of this assignment is to design and develop a simple and rudimentary spam detection
system using the following technologies:

- Cloud Infrastructure using AWS
- Hadoop
- MapReduce
- Hive

## Task 1: Cloud Infrastructure Setup - AWS

- 1.1: Installing Hadoop and create a Hadoop cluster
- 1.2: Installing MapReduce, Pig and Hive to use the cluster created in Task 1.1

## Task 2: Dataset

- 2.1: Choosing a relevant dataset 
- 2.2: Get data from any public dataset repository
- 2.3: Load data into AWS S3 bucket

## Task 3: Clean and process the data using Hive

- 3.1: Removed NULL values from data
- 3.2: Removed HTML tags from comment data
- 3.3: Removed URLs from comment data
- 3.4: Removed special characters from comment data

## Task 4: Ham and Spam using Pig and/or Hive

- 4.1: Query processed data to differentiate ham and spam part of the dataset
- 4.2: Query spam data to find the top 10 spam accounts
- 4.3: Query ham data to find the top 10 ham accounts

## Task 5: TF-IDF using MapReduce

- 5.1: Use MapReduce to calculate the TF-IDF of the top 10 spam keywords for each top
10 spam accounts
- 5.2: Use MapReduce to calculate the TF-IDF of the top 10 ham keywords for each top
10 ham accounts