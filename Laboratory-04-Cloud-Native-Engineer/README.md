	# Laboratory Activity 4: The Cloud-Native Engineer

## Mission Overview
In this activity, I learned the difference between Virtual Machines and Containers. I also practiced using Docker in the KillerCoda cloud environment and learned how to run and manage an Nginx container.

## Objectives
- Differentiate between traditional Virtual Machines (VMs) and Containers
- Access a Docker-enabled cloud environment using KillerCoda
- Execute fundamental Docker CLI commands
- Pull, run, manage, and terminate a containerized application (Nginx)
- Create professional technical documentation of container operations using Markdown
- Continue developing a well-organized GitHub Cloud Computing Portfolio

## Docker Commands Executed

### Checkpoint 3 - Verify Docker
- `docker --version`
- `docker info`

### Checkpoint 4 - Deploy Container
- `sudo docker pull nginx`
- `sudo docker run -d -p 8080:80 nginx`
- `curl http://localhost:8080`

### Checkpoint 5 - Container Lifecycle
- `sudo docker ps`
- `sudo docker stop 9a01d04fbb92`
- `sudo docker ps -a`
- `sudo docker rm 9a01d04fbb92`

## Skills Learned
I learned how to use basic Docker commands to manage containers. I also learned how to download and run Nginx using Docker. This activity helped me understand how containers work and how they can be used to run applications.

## Challenges Encountered
One challenge I encountered was understanding the different Docker commands and their uses. I also needed to understand how to start, stop, and remove containers. By practicing the commands in KillerCoda, I was able to understand how Docker works better.
