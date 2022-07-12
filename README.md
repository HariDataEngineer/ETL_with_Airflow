# ETL_with_Airflow
Build a simple ETL pipeline with the best open source orchestration tool Airflow from scrath

# Airflow :
* Airflow is the orchestration tool for bulding pipeline workflow as code
* Airflow uses DAG architecture, for dividing the complete workflow as individual tasks and run them based the dependencies between the tasks

# Airflow DAG Builing Blocks
* Library Imports - Import all your required python libraries and operators to implement tasks, for example, DAG and datetime modules
* Defining DAG arguements - Here define the default arguements of your DAG like owner, start_date, retries and contact details
* Define the DAG - Create the DAG instance with name and schedule arguements, define the DAG
* Define the Tasks - Write your individual tasks using Airflow Operators
* Task Pipeline - Write the dependencies between tasks, define the order in which tasks has to run

# This Project : 
* Here we will build an ETL pipeline using Bash operator of Airflow with by defining DAG 
* The job of pipeline is to extract data from users table and transform it into a CSV file and then load the file(in CSV format) into Postgres sql table
