# PostgreSQL

Docker compose file will create a container running PostgreSQL and load a sample database named "DVD Rental". <a href="https://www.postgresqltutorial.com/postgresql-getting-started/postgresql-sample-database/" target="_blank">Click here for more information about the data</a>

Execute
```
docker compose up -d
```
Then you can connect to the database using your preferred PostgreSQL client.

Warning: do not use this is in production, database credentials are exposed in YAML file.