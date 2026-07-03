## Purpose:

The purpose of creating the database for Sparkify is to track user song plays/activity, what specific song is being played, and when. The goal is to help Sparkify understand and analyze user data to improve playlists, recommend songs/artists, and other business decisions based on the data.

## Running Scripts:

To run the python scripts, first run create_tables.py provided in the first cell located on the test.py file. Running create_tables.py creates the tables and database. Next, run the etl.py file to read the song and log data files, and to insert the data into the database/tables. The scripts must be ran in order to avoid errors and for accuracy.

## Files:

**create_tables.py** - Drops and creates the tables for the database
**etl.py** - Extracts, Transforms, Loads the data
**sql_queries.py** - Provides all the SQL queries
**etl.ipynb** - Used to write and check the ETL pipeline

## DB Design and ETL pipline:

The database design used is a star schema with one fact table and four dimension tables. The design simplifes queries and improves performance. The structure allows joins to be efficient and makes the data easier to analyze. The ETL pipeline allows the JSON song and log files to be extracted to be transformed and loaded into the database. The SQL queries helped to to keep the extracted data clean, organized, and ready for the analysis.

## Note

This project was completed as part of my WGU Data Analytics program. The project provided an ETL framework, which I completed by implementing the SQL schema, writing SQL queries, and integrating the required ETL functionality to load and transform the data.

The sample dataset used for this project are not included in this repository. To run the project, must obtain the original datasets from the course material or replace them with compatible data.