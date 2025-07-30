3 Exercises and a final IMDB API Project




Containerised the Flask API

- Created a Dockerfile and ensured the API runs inside the container.

Set up Docker Compose for Flask + MySQL

- Defined multi containers with networking, environment variables, and persistent volumes.

Fixed Environment and DB Connection

- Updated config.py to use sakila_db and ENV=DEV.

Initialised the Sakila Database with Schema and Data

- Added SQL scripts for and fixed the execution order.

Verified the API Endpoints with Sakila DB Data

- After some testing on Postman / Successfully got list of actors in Postman.