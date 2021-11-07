# Project Description
Build and ETL (Extract, Transform, Load) pipeline using python that extracts RAW data from json files and inserts it into 
a postgressdb using SQL.
As part of the project, data modeling principles were applied to define the dim and fact tables creating a STAR schema

## Schema Design
Have created 4 dim tables: songs, artists, users, time
And 1 fact table: songplays.

AS learned on the lessons, the fact table contains the data to analyse and the dim tables contains the data on a 
'analizable' format.

## How to Run
1. Run `python create_tables.py` to recreate the used tables.
2. Run `python etl.py` to parse data from the json files and insert the modeled data into the tables.