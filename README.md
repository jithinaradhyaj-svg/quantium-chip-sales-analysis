# Quantium Chip Sales Analysis

## Project Overview

This project analyses customer purchasing behaviour for the chip category using retail transaction data. The goal of the analysis is to help the Category Manager understand which customer segments drive chip sales and what factors influence purchasing behaviour.

## Business Problem

A supermarket category manager wants to identify the key customer segments that purchase chips and understand their purchasing patterns. The insights from this analysis will support strategic decisions related to promotions, product placement and category growth.

## Dataset

The analysis uses two datasets:

* **Transaction Data** – contains chip purchases including product names, quantities and sales values.
* **Customer Data** – contains information about customer life stage and spending behaviour.

After cleaning the datasets, they were merged using the customer loyalty card number.

## Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## Analysis Performed

The following analysis steps were performed:

* Data cleaning and outlier removal
* Feature engineering (extracting brand names and pack sizes)
* Customer segmentation analysis
* Sales analysis by brand
* Sales analysis by pack size
* Customer purchasing behaviour analysis

## Key Insights

* Certain customer segments generate significantly higher chip sales.
* Medium pack sizes (around 170g–175g) are the most popular.
* Premium brands contribute a large share of chip category revenue.

## Business Recommendations

* Target high-value customer segments with promotions.
* Increase shelf space for popular chip brands.
* Promote high-demand pack sizes to maximise sales.

## Visualisations

Example charts from the analysis:

![Brand Sales](visuals/brand_sales.png)

![Pack Size Sales](visuals/pack_size_sales.png)

![Customer Segment Sales](visuals/segment_sales.png)
