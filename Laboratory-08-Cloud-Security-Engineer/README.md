# Laboratory Activity 8: The Cloud Security Engineer

## Mission Overview

In this activity, I learned how to secure a Linux server using the UFW firewall. I deployed an Nginx web application and configured the firewall to block incoming traffic by default while allowing SSH and port 8080. This helped me understand how firewall rules protect a server from unwanted connections.

## Objectives

* Understand the concept of the Attack Surface and the Principle of Least Privilege (PoLP)
* Perform a basic security audit of active network ports on a Linux server
* Configure the Uncomplicated Firewall (UFW) with a Default Deny policy
* Implement granular port management to selectively allow SSH and HTTP traffic
* Document firewall rules and security best practices using Markdown
* Continue expanding my professional GitHub Cloud Computing Portfolio

## Commands Executed

* `sudo docker run -d -p 8080:80 --name secure-web-app nginx`
* `curl http://localhost:8080`
* `sudo ufw allow ssh`
* `sudo ufw default deny incoming`
* `sudo ufw default allow outgoing`
* `sudo ufw enable`
* `sudo ufw status verbose`
* `sudo ufw allow 8080/tcp`
* `sudo ufw status numbered`

## Skills Learned

Through this activity, I learned how to deploy a web application and protect a Linux server using a firewall. I also learned how to allow specific ports while blocking unwanted incoming traffic. This activity helped me understand the importance of checking open ports and applying security rules to reduce the risk of attacks. I can use these skills in future cloud computing activities.
