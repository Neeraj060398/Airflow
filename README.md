# Airflow

<b>Prerequisites: </b><br>
1)Docker <br>
2)Visual Studio <br>

<br>
The <b>'docker-compose.yaml'</b> file contains the necessary containers required for the Airflow project.

<br><br>
<b>About the project</b><br>
Generate a new user each time the API is called, process the user's details, and store them in a PostgreSQL table.
 <br><br>
The Airflow DAG has 5 tasks: <br>
i)  create_table: Create a Postgres table if not exists with appropriate fields <br>
ii) is_api_available: Checks if api is available or not <br>
iii)extract_user: Extract user details <br>
iv) process_usr: process that user details <br>
v)  store_user: stores the user details into Postgres table <br>
