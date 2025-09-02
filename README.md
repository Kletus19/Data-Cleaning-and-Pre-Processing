# Data-Cleaning-and-Pre-Processing

## Project Overview

This project is based on data cleaning and processing of a sample employee data; this will be achieved using power query. The steps involved connecting to the file, extraction, transforming and load in power query for cleaning, this will ensure the file is free of duplicates, missing and null values and additionally free of inconsistent formats and structures	

## Data Sources

Employee data in ".xlsx " format for anaylsing employee company records

## Tools

- microsoft excel power query[download here](https://www.kaggle.com/datasets/alistairking/electricity-prices?resource=download)

## Data Cleaning / processing 

in this phase, the following steps where conducted
- filtered for 500 rows
- removed unwanted rows and columns
- checked for nulls, space and epmty data. trimmed and replaced with unkowns
- converted month column to text type and replaced the month number with month name
- merged year and month name to one column as year, the went to data type ( locationale ) , selected date to american time standard and finally had a good year format
- finaly checked to make sure all rows of of correct data type

## results and findings
- data was cleaned for spaces,nulls , dupicates and missing values
- Power query renders data cleaning easy as it can connect to all data sources. extract, transform and load any data set which is not usually achived in excel work book as it can only read an excel file.
additionally power query gives you a more adavanced option called ( data automation) as when new data for the present file is found, it can be pasted into this file. through the connection of this file to power query, all cleaning steps that where previously done on it will be reapplied on the new updated data set through the refresh command

## recommendations

- data cleaning in power query is more easy and straight forward and its automated and can work well for someone who is not technical enough to have the knowledge of how to geneate excel formulas

## Limitations

- power query usually automatically loads for 1000 rows, if you have more than a 1000 rows. be sure all others are accounted for.

## references

- microsoft data analysis course by chandoo
  
