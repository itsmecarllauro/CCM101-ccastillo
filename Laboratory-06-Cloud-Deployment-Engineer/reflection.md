# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because the configuration can be written once and used to deploy the whole application. Instead of typing many commands separately, Docker Compose can create and start the containers using one command. I think this is useful because it saves time and can also reduce mistakes.

If I make an indentation error in a YAML file, the configuration may not work correctly. YAML depends on proper spacing and indentation. For example, using a Tab instead of spaces can cause an error when Docker Compose tries to read the file. This showed me that even small formatting mistakes can affect the whole deployment.

We used environment variables such as `MYSQL_PASSWORD` because they provide the settings needed by the containers. In this activity, the environment variables tell Nextcloud which database, username, password, and database host to use. This makes it possible for the application and database to communicate with each other.

I felt that deploying Nextcloud in only a few minutes was interesting because I could see how powerful cloud and container technologies can be. Before this activity, I thought deploying a complete application would require many complicated steps. Docker Compose made the process more organized because the services were defined in one configuration file.

Since Mission 1, my understanding of Cloud Computing has improved. I learned that cloud computing is not only about storing files online. It also involves containers, infrastructure, networking, databases, and automated deployment. Each mission helped me understand another part of how cloud systems work. This activity helped me see how these concepts can be combined to create a working cloud application.
