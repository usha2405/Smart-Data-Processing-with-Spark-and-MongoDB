# Smart Data Processing with Spark & MongoDB

## Project Summary

This project demonstrates an end-to-end big data analytics pipeline using **Apache Spark (PySpark)** and **MongoDB**. It focuses on scalable data exploration, processing, and querying for large datasets using distributed computing and NoSQL databases.

## Table of Contents

- [Project Summary](#project-summary)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Dataset Overview](#dataset-overview)
- [Key Components](#key-components)
- [Features](#features)
- [Results](#results)
- [Usage](#usage)
- [Contributors](#contributors)

## Tech Stack

- Python
- PySpark
- Apache Spark
- MongoDB
- Jupyter Notebooks
- Pandas (for auxiliary processing)

## Installation

1. Install Apache Spark and PySpark.
2. Set up MongoDB locally or use a cloud instance.
3. Install dependencies:
   ```bash
   pip install pyspark pymongo pandas
   ```
4. Open and run the notebooks using Jupyter or VSCode.

## Dataset Overview

The dataset contains structured data suited for big data processing (e.g., transaction records, customer details, or sales). It is loaded into both Spark and MongoDB for scalable analysis.

## Key Components

- `Pyspark_EDA.ipynb`: 
  - Data loading and cleaning with Spark DataFrames
  - Exploratory Data Analysis (EDA) using PySpark
  - Statistical summaries and trend identification
- `Mongodb.ipynb`: 
  - MongoDB connection and CRUD operations
  - Querying and indexing data
  - Aggregation pipelines for analytics

## Features

- Distributed data wrangling using PySpark
- NoSQL data modeling and aggregation with MongoDB
- EDA at scale on large datasets
- Schema inference, filtering, and transformation
- Visualization-ready statistics from processed data

## Results

- Efficient handling of large datasets with parallel processing
- Queried large volumes using MongoDB's aggregation framework
- Identified key insights using PySpark's analytical capabilities

## Usage

Run each notebook sequentially after setting up your environment. Ensure MongoDB is running if executing the MongoDB notebook.

## Contributors

- Usha Jain

