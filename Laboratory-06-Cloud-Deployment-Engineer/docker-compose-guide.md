# Checkpoint 6 - Technical Documentation

## 1. What Does the `services:` Block Do?

The `services:` block defines the containers that will run in our application. In our project, we have two services: `database`, which uses MariaDB to store data, and `app`, which runs Nextcloud. These services work together to make the cloud storage system function properly.

## 2. How Does Nextcloud Find the Database Container?

Nextcloud finds the database container through the `MYSQL_HOST` environment variable. In our Compose file, we set `MYSQL_HOST=database`. The word `database` matches the name of our database service. Docker Compose provides network communication between the services, allowing Nextcloud to connect to MariaDB using this service name instead of an IP address.

## 3. Difference Between `docker run` and `docker-compose up -d`

The `docker run` command is used to create and start a container by specifying its settings directly in the terminal. It is useful for running individual containers, but managing multiple connected containers can require several commands.

On the other hand, `docker-compose up -d` reads the `docker-compose.yml` file and starts all the services defined in it. The `-d` option means detached mode, so the containers run in the background. This makes deployment easier because the configuration is saved in one file and can be reused whenever needed.

## Conclusion

Docker Compose makes deploying multi-container applications easier, more organized, and more consistent. It allows engineers to manage the Nextcloud application and MariaDB database together using a single configuration file.
