# NYC Taxi and Limousine Commission Data Modeling

This repository contains the work I performed on the NYC Taxi and Limousine Commission (TLC) data. I focused on data modeling using dimensional modeling techniques to gain valuable insights and improve the understanding of taxi and limousine services in New York City.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Source](#data-source)
2. [Data Dictionary and Data Model](#data-dictionary-and-data-model)
3. [Dimensional Modeling](#dimensional-modeling)
4. [Future Improvements](#future-improvements)

## Introduction

In this project, I worked with the NYC Taxi and Limousine Commission data, which is a comprehensive dataset containing information about taxi trips, fares, and other attributes in New York City. The primary goal of this project was to create a dimensional model that would allow for easier and more efficient querying of the data to extract meaningful insights.

## Data Source

The dataset used in this project was obtained from the NYC TLC website https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page, and it covers a time period from 2009 to 2023. The dataset includes various dimensions such as date, time, location, and taxi-related attributes, enabling us to perform comprehensive analyses.

## Data Dictionary and Data Model

For detailed information about the columns and their meanings in the dataset, please refer to the `data_dictionary.pdf` file located in the `data` folder. The file is obtained from NYC TLC website.

The data model diagram visually represents the dimensional model created for this project. You can find the diagram in the file `Data-Model.png` in the main folder.

## Dimensional Modeling

Dimensional modeling is a data modeling technique used for data warehousing and business intelligence. It organizes data into easily understandable dimensions and measures, which facilitates faster and more efficient querying. The key components of the dimensional model include:

- Fact Tables: These tables contain the quantitative data (e.g., taxi trip metrics) and connect to dimension tables. <br>
- Dimension Tables: These tables hold descriptive attributes (e.g., time, location, taxi driver details) that provide context to the fact tables.

## Future Improvements

This project is a starting point for deeper analyses and business intelligence. Some potential future improvements include:

- Building interactive dashboards for exploring data visually.
- Implementing data pipelines for automatic data updates and processing.
- Incorporating external datasets to enrich the analysis.

 
