# 📘 Student Performance Analysis using Hadoop

## 📌 Project Description

This project focuses on analyzing a student performance dataset using the Hadoop ecosystem. The dataset contains information such as Student_ID, Name, Gender, Attendance, Study Hour, Previous Grade, Extracurricular Activity, and Parental Factors. The objective is to process and analyze the data to extract meaningful insights about student behavior and performance.

## 📊 Dataset Information

* Format: CSV (Comma Separated Values)
* Each row represents a student record
* Columns include student details and performance-related attributes

## 🛠️ Technologies Used

- Hadoop (HDFS) – Data storage
- MapReduce – Data processing
- Hive – Data querying and analysis
- Python – Mapper and Reducer implementation
- Linux – Execution environment

## ⚙️ Workflow

- Upload dataset to HDFS
- Process data using MapReduce (filtering, grouping, aggregation)
- Store processed data in HDFS
- Load data into Hive tables
- Perform queries to generate insights

## 🎯 Objectives

- Analyze student performance data
- Identify patterns and trends
- Perform filtering, grouping, and aggregation
- Generate insights using Hive

## 🤖 Use of AI

AI tools were used for code generation, query writing, debugging, and documentation support.

## 🏗️ Architecture 

Dataset (CSV) → HDFS → MapReduce → HDFS (Processed Data) → Hive → Insights

## 📊 Dataset Description 

The dataset contains the following columns:

* Student_ID
* Name
* Gender
* Attendance
* Study Hour
* Previous Grade
* Extracurricular Activity
* Parental Factors

## ⚙️ Workflow Explanation

- The dataset in CSV format is uploaded to HDFS for distributed storage
- MapReduce processes the data by performing operations like filtering, grouping, and aggregation
- The processed output is stored back in HDFS
- The data is then loaded into Hive tables
- Hive queries are executed to analyze the data
- Final insights are generated from the analysis

## 📊 Output

The output of the project consists of processed student data generated after applying MapReduce and Hive queries. The results include:

- Filtered student records based on conditions (e.g., attendance, study hours)
- Grouped data based on attributes like Gender or Extracurricular Activity
- Aggregated results such as total count and averages
- Query results from Hive showing analyzed data
- Insights about student performance and behavior

## ⭐ Key Features

- Distributed Data Storage using HDFS
- Parallel Data Processing with MapReduce
- Efficient Data Analysis using Hive queries
- Supports Large Datasets (scalable system)
- Performs Filtering, Grouping, and Aggregation
- Generates Insights from student data
- Simple and Structured Workflow

## 📌 Conclusion

* This project demonstrates the use of Hadoop technologies to efficiently process and analyze student data. By using HDFS for storage, MapReduce for data processing, and Hive for querying, large datasets can be handled effectively. The project helps in identifying patterns and extracting useful insights from the data, showing the importance of Big Data tools in data analysis

## 📝 Final Note

* This project provides a practical understanding of Big Data technologies and their application in real-world data analysis. It demonstrates how Hadoop tools can be used to efficiently store, process, and analyze large datasets. The knowledge gained from this project can be applied to more advanced data analytics and real-time processing systems in the future.
