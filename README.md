# sql-challenge
# Jason Hanlin
# 3/26/2023

For this Module 9 Challenge, I am a data engineer for Pewlett Hackard tasked with doing a research project for employees who were employed during a two decade period from the 80s and 90s. I received the six CSV employee data files from the Boot Camp repository.  

After analyzing these six database files and using the notes from Dr. A's class, I created a schema design in Quick DBD (https://app.quickdatabasediagrams.com/#/d/iKvK4U).  This was helpful to visualize the relationships among the table data that was provided.  See the schema models in the schema_models folder from the repository.  

I attempted to export the schema as PostgreSQL code but the syntax wasn't too similar to what was familiar from class.  So I manually created the code in pgAdmin 4 to create the table framework.  The code is complete with data types, primary keys (including composite keys), and foreign keys. The code ran without issue and the provided data was successfully imported into the tables.  The schema is provided in file "EmployeeSQL-TableSchema.sql" from the repository.  

A separate sql file was created to accomplish the data analysis using queries.  The queries are provided in the file "EmployeeSQL-Queries.sql" from the repository.  

The results were reviewed for correctness and consistency.  


