# Week 1 Assignment - Data Validation
[Tensorflow Data Validation (TFDV)](https://cloud.google.com/solutions/machine-learning/analyzing-and-validating-data-at-scale-for-ml-using-tfx) is an open-source library that helps to understand, validate, and monitor production machine learning (ML) data at scale. Common use-cases include comparing training, evaluation and serving datasets, as well as checking for training/serving skew. You have seen the core functionalities of this package in the previous ungraded lab and you will get to practice them in this week's assignment.

In this lab, you will use TFDV in order to:
* Generate and visualize statistics from a dataframe
* Infer a dataset schema
* Calculate, visualize and fix anomalies 

## Requirements
tensorflow==2.6.0
tensorflow_data_validation==1.3.0