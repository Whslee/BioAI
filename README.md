# BioAI
Application and Practice in Neural Networks

## Title
Developing cancer classification models using genomic variant information fromcancer patients

## Introduction
To expand the field of artificial intelligence, we aim to develop AI algorithms that can efficiently analyze and interpret various complex bio-data by processing and analyzing them, to increase the utilization of bio-data, and to explore how AI technology can contribute to solving real-world problems through classification in complex bio-data.

## Description of the Dataset
### 1. Train Dataset
Number of Entries (Rows): 6201 rows
Number of Features (Columns): 4386 columns (from ID to ZYX)
Data Types: All columns are of object data type (4386 object type columns)
Memory Usage: Approximately 207.5 MB
Feature List:
ID: ID column
SUBCLASS: Likely the target variable
4384 other features (e.g., A2M, AAAS, AADAT, AARS1, etc.)
  
### 2. Test Dataset
Number of Entries (Rows): 2546 rows
Number of Features (Columns): 4385 columns (from ID to ZYX, without SUBCLASS)
Data Types: All columns are of object data type (4385 object type columns)
Memory Usage: Approximately 85.2 MB
Feature List:
ID: ID column
4384 other features (e.g., A2M, AAAS, AADAT, AARS1, etc.)

The Train Dataset includes the SUBCLASS column, which is the target variable.
The Test Dataset does not include the SUBCLASS column, meaning it's likely used for prediction.

