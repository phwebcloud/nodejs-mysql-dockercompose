
## Local deployment instruction


Install docker + docker compose

## Ubuntu/Debian

https://docs.docker.com/engine/install/ubuntu/

## CentOS/RedHat

https://docs.docker.com/engine/install/centos/


## Docker Compose

https://docs.docker.com/compose/install/


## Testing...

- After installing docker and docker compose, run the comand above inside the root directory:

   `docker-compose up --build -d`

- Check created containers:

   `docker ps`

- Access the application using the Server IP on browser, or just localhost(in case you installed locally).
- To check the inserts on the database, run:

   `docker exec mysql mysql -pdeliverymuch -e 'SELECT * FROM preferences.preferences';`
