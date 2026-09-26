## Apache Pig – E-Commerce Product Review Analysis

## Objective

* Load product review data from HDFS using Apache Pig.
* Filter out invalid ratings below 1.0.
* Remove records with null rating values.
* Group valid reviews by product category.
* Calculate the average rating for each product category.
* Analyze product review ratings using Pig Latin dataflow operations.

## Problem Statement

An e-commerce company wants to prune invalid product reviews and find the average rating score per product category using procedural dataflow scripts.

## Technologies Used

* Apache Pig
* Pig Latin
* Hadoop HDFS
* MapReduce
* Linux


## Pig Operations Used

* `LOAD` – Loads the review dataset.
* `FILTER` – Removes invalid and null ratings.
* `GROUP` – Groups reviews by product category.
* `AVG` – Calculates the average rating for each category.

## Expected Output

The final output contains the average rating score for each product category.

Example:

```text
Home,2.5
Books,3.75
Clothing,4.5
Electronics,3.75
```

## Conclusion

This project demonstrates how Apache Pig can be used to process and analyze large-scale e-commerce review data stored in HDFS using a simple procedural dataflow approach.

