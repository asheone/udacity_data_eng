This is a repository for the Udacity's 'Data Modeling with Postgres' project made by Lukasz Aszyk.

It contains 6 files: `etl.ipynb`, `test.ipynb`, `sql_queries.py`, `create_tables.py`, `etl.py`, and `README.md`.

The first Jupyter notebook file `etl.ipynb`, contains the code prepared for further use in the `etl.py` file for the whole ETL process. 

The second `test.ipynb` file contains the validation code and checks if all the tables were created and contains the required data.

The third file, `sql_queries.py` contains all the SQL statements, for tables dropping, creation, and inserting data into tables.

The `create_tables.py` file contains the execution python code for connecting to hte database and running the SQL queries.

The `etl.py` file contains 4 functions: `process_song_file`, `process_log_file`, `process_data`, and `main`. All the functions have the descriptions provided.

For running the project, first download the packages `pip install goodtables, pprint`, open the terminal and run the `create_tables.py` first and next run the `etl.py` file. 