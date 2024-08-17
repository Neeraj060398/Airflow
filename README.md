# Airflow

<h3><b>Prerequisites: </b></h3><br>
1. Docker <br>
2. Visual Studio <br>

<br>
The <b>'docker-compose.yaml'</b> file contains the necessary containers required for the Airflow project.

<br><br>
<h3><b>About the project</b></h3><br>
The project is designed to generate a new user each time the API is called, process the user's details, and store them in a PostgreSQL table.

<br><br>
<h3><b>Airflow DAG Overview</b></h3>
<br><br>
The Airflow DAG consists of 5 tasks:
<br>
1. <b>create_table:</b> Creates a PostgreSQL table if it does not already exist, with the appropriate fields. <br>
2. <b>is_api_available:</b> Checks if the API is available. <br>
3. <b>extract_user:</b> Extracts user details from the API. <br>
4. <b>process_user:</b> Processes the extracted user details. <br>
5. <b>store_user:</b> Stores the processed user details into the PostgreSQL table. <br>
