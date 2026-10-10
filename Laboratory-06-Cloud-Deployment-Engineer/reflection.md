# Checkpoint 7 - Mission Reflection

During this laboratory, I learned how to deploy a cloud storage system using Docker Compose. This activity helped me understand how different containers work together to run an application.

**1. How does writing a docker-compose.yml file make a cloud engineer's job easier?**

Writing a `docker-compose.yml` file makes the job easier because all the container settings are saved in one file. Instead of typing many commands one by one, I can use a single command to start the application and its database. It also makes the setup easier to repeat and manage.

**2. What happens if you make an indentation error in a YAML file?**

If I make an indentation error, Docker Compose may not be able to read the configuration correctly. It can show an error and prevent the application from starting. I learned that YAML uses spaces for indentation, so I must avoid using Tabs and make sure the spacing is correct.

**3. Why did we use environment variables like MYSQL_PASSWORD?**

We used environment variables to provide important settings to the containers, such as database passwords and connection details. They make the configuration easier to change without editing the application itself. However, I also learned that passwords should be protected and not shared publicly.

**4. How did it feel to deploy Nextcloud in just a few minutes?**

I felt happy and proud because I was able to deploy a cloud storage application in a short time. At first, the configuration looked confusing, especially the YAML indentation and database settings. After understanding the process, I realized that Docker Compose makes deployment much faster and more convenient.

**5. How has my understanding of Cloud Computing evolved since Mission 1?**

Since Mission 1, my understanding of cloud computing has improved. Before, I mainly thought of cloud computing as storing files and accessing services through the internet. Now, I understand that it also involves containers, application services, databases, networking, and configuration. I learned that these components can work together to provide a useful cloud service. This laboratory helped me gain more confidence in using Docker and understanding how cloud applications are deployed.
