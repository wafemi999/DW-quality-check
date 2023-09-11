# DW-quality-check
A testing framework for datawarehouses to check  and verfy data quality


## Method:
using python (frameworks, libraries, and adapters) to verify data quality in a datawarehouse (postgresQL):

* Set-up-database with: bash setup_staging_area.sh
* Populate with tables: DimCustomer, DimMonth, FactBilling. using  (star-schema)
* Install  python adapter  for Postgresql: python3 -m pip install psycopg2
* confirm db connect with: python3 dbconnect.py
* view all tests to be carried out  in:  mytests.py
* create script to generate data quality report: generate-data-quality-report.py

  

## ToDo 
* Checking for  Null values
* Checking Duplicate values
* Check Min Max
* Checking Invalid values
* Generating a report on data quality of the fact and dimension tables

## Output:

![data quality report](output-test.jpeg)

