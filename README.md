# Home_Sales
Repository for Module 22 Challenge

## Overview
For this challenge, we used SparkSQL to query key metrics regarding home sales data.  As part of our query process, we created temporary views, partitioned data, cached and uncached a temporary table, and verifed that the temporary table had been uncached.  We used Google Colab to create the file and execute the queries, partitioning, and caching.

## Summary
We selected one of the queries, which returned the view rating for the average price of a home, where home prices are greater than or equal to $350,000, to be run three ways.  The results were as follows:

* Run time using SparkSQL and a temporary view of the table:  .39 seconds
* Run time using SparkSQL and cached data:  .31 seconds
* Run time using SparkSQL and partitions created using Parquet:  .36 seconds


