# Airflow

<b>Prerequisites: </b><br>
1)Docker <br>
2)Visual Studio <br>

<br><br>
docker-compose.yaml file contains the necessary container required for the airflow project

<br><br>
<b>About the project</b><br>
Generate a new user each time the API is called, process the user's details, and store them in a PostgreSQL table.
 <br>
The DAG has 5 tasks: <br>
i)  create_table: Create a Postgres table if not exists with appropriate fields <br>
ii) is_api_available: Checks if api is available or not <br>
iii)extract_user: Extract user details <br>
iv) process_usr: process that user details <br>
v)  store_user: stores the user details into Postgres table <br>
