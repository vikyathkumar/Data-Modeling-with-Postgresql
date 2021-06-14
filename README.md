# Data-Modeling-with-Postgr
In this project, I have worked on the dataset of an startup company called "sparkify", where the company need the detail information of their customers. So, here I have extracted the data which was in an json format and converted it into and SQL data i.e tablaur format in the following manner:
1. Inorder to model the dataset in efficient manner, I used the star-schema containing one fact table and five dimention tables as 
mentioned:

FACT TABLE:
1.songplays - records in log data associated with song plays i.e. records with page NextSong
Schema = songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent
 
DIMENTION TABLE:(usage and their schema)
1.users - users in the app
Schema = user_id, first_name, last_name, gender, level 
2.songs - songs in music database
Schema = song_id, title, artist_id, year, duration
3.artists - artists in music database
Schema = artist_id, name, location, latitude, longitude
4.time - timestamps of records in songplays broken down into specific units
Schema = start_time, hour, day, week, month, year, weekday

2. created a python file named sql_queries.py (contains all your sql queries, and is imported into the last three files above)
3. created a python file named create_tables.py (drops and creates your tables. You run this file to reset your tables before each time you run your ETL scripts) 
4. created a python notebook named test.ipynb(displays the first few rows of each table to let you check the database)
5. created a python notebook named etl.ipynb(reads and processes a single file from song_data and log_data and loads the data into your tables. This notebook contains detailed instructions on the ETL process for each of the tables.)
6. created a python file named etl.py(reads and processes files from song_data and log_data and loads them into your tables. You can fill this out based on your work in the ETL notebook).

In this flow, I have created my project which extracts the data from the sparkify dataset which is in json format and converts them into an tabular format as in designed schema:

NOTE: In order to run any files use command %run <file name> in the jupiter notebook. 