# Specify Relationships Example Database

This is a Docker project that launches a Specify 7 instance running LOCALLY with sample data for reviewing and testing how ***Collection Object Relationships*** and ***Preparation Relationships*** can be set up.

The setup provides a complete Specify system including Specify 7, database, asset server, report runner and webserver on a single host. 
Since all services are included it requires minimal configuration. 
A seed database is provided in the form of a Specify SQL backup file and it is automatically loaded into the database container.


## Disclaimer
1. Personally identifiable data has been scrubbed from this database.
2. This project and its sample data are for testing and reviewing purposes only and for demonstrating how the database was configured.

## Running

Starting and stopping the Specify 7 via Docker Compose is accomplished
by executing commands from within the project directory.

Run `docker-compose up -d` to bring up Specify 7. Stop by running
`docker-compose stop`.


### Testing Credentials
Once the Docker containers are running, you can launch Specify in a web browser and log in.

**Specify:** *http://localhost/*

**username:** *test*

**password:** *testtest*
