# Data-Modeling-with-Postgr

In this project, I have worked on the dataset of an startup company called "sparkify", where the company need the detail information of their customers. So, here I have extracted the data which was in an json format and converted it into and SQL data i.e tablaur format in the following manner:
1. Inorder to model the dataset for efficient manner, I used the star-schema containing one fact table and five dimention tables.
2. Created, droped and inserted the data into those tables.
3. using the ETL(Extract Transfer load ) process and extracted the dataset of json format into the tables which was created.

1.Here in this project, we are using the files namely
etl.ipunb
sql_queries.py
test.ipynb
etl.py

What data and how to run these files:
 1. sql_queries.py: Here i am going to write the postgres code of creating, droping and inserting the data for the above mentioned tables.
 2. test.ipynb: This file is used to test my all files, wheather they are giving proper output or not. Inorder to run any file use command "%run <file name>".
 3. etl.ipunb: Here we are going to generate our etl pipelines and extract the data from the data folder and transfer them to out tables and store them.
 4. etl.py: this folder contains all the flow of our process used in etl.ipunb and we can run this file in the etl.ipunb using the command "%run etl.py"