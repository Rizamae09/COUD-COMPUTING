
# Mission Reflection

Writing a `docker-compose.yml` file makes the work easier because the containers and their settings can be placed in one file. Instead of entering many commands one by one, Docker Compose can start the whole application using a single command. This makes the deployment more organized and easier to repeat.

If there is an indentation error in a YAML file, such as using a Tab instead of Spaces, the file may not work properly. YAML uses indentation to understand the structure of the configuration. Because of this, even a small mistake can cause an error and stop Docker Compose from running the application.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` to provide the database settings needed by Nextcloud. These variables help Nextcloud know which database and credentials to use. The `MYSQL_HOST=database` also tells Nextcloud where to find the MariaDB container.

Deploying Nextcloud in just a few minutes made me realize how useful Docker Compose can be. It made the process easier because the application and database could be deployed together instead of setting them up separately.

Since Mission 1, my understanding of Cloud Computing has improved. Before, I mainly learned about basic cloud concepts, but now I have a better idea of how applications can be deployed and connected using containers. This mission also helped me understand how Infrastructure as Code and automation can make cloud deployment easier and more organized.
