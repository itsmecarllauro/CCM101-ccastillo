# Laboratory Activity 7: The Cloud Operations Engineer

## Mission Overview
In this laboratory activity, I learned how to monitor system resources, deploy a web container, and check its performance using Docker. I also learned how to generate web traffic and analyze application logs to identify errors.

## Objectives
- Utilize native Linux command-line tools to monitor host CPU, Memory, and Disk capacity
- Deploy a web container and track its real-time performance using Docker metrics
- Generate web traffic and extract application access logs for analysis
- Translate raw performance data into a readable technical report using Markdown
- Continue expanding a professional GitHub Cloud Computing Portfolio

## Monitoring Commands Executed

### Checkpoint 2: Host System Baseline
- `free -h`
- `df -h`
- `top`

### Checkpoint 3: Deploy and Generate Traffic
- `sudo docker run -d -p 8080:80 --name client-website nginx`
- `curl http://localhost:8080`
- `curl http://localhost:8080/hidden-admin-page`

### Checkpoint 4: Application Logging
- `sudo docker logs client-website`

### Checkpoint 5: Real-Time Container Metrics
- `sudo docker stats`

## Skills Learned
I learned how to monitor CPU, memory, and disk usage using Linux commands. I also learned how to deploy a Docker container, check its performance, and analyze access logs to understand web errors. This activity helped me improve my skills in cloud monitoring and troubleshooting.

