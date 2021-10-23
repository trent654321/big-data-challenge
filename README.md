# big-data-challenge
Created by Trent McNabb for Carleton University Business Analytics and Data Visualization BootCamp
Contains a folder "level-1" with watches_reviews.ipynb and wireless_reviews.ipynb
The code takes two files with data on Amazon reviews.
'https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Watches_v1_00.tsv.gz'
'https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Wireless_v1_00.tsv.gz'
The data types get changed to match the datatypes in the given schema.sql file and dataframes that match the schema are created. Nulls and duplicates are dropped from primary key columns. THe data is then uploaded to an instane in RDS.