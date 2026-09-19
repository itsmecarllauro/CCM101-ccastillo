# Reflection

In this activity, I learned how Docker containers work and how they are different from Virtual Machines. A Docker container starts in just a few seconds, while a Virtual Machine usually takes longer because it needs to boot a complete operating system. Setting up a VM also requires more resources, such as RAM and storage. With Docker, I can quickly download and run an application like Nginx without installing a full operating system.

Port mapping, such as `-p 8080:80`, is important because it allows users to access the web server inside the container. Port 8080 is the port on my computer, while port 80 is the port used by Nginx inside the container. This connection allows me to open the web server through `http://localhost:8080`. Without port mapping, I may not be able to access the web server directly from my computer.

When I use the `docker rm` command, the container is deleted. Any data stored inside the container that is not saved separately may be lost. This taught me that important data should be stored using volumes or other storage solutions instead of depending only on the container.

I think containerization helps developers and IT operations teams work together more easily. Developers can package applications with their needed dependencies, while IT teams can deploy them in a consistent environment. This can make testing and deployment faster and reduce problems caused by different setups.

My GitHub portfolio is slowly improving as I add my laboratory activities and reflections. I am learning how to organize my files and document the commands I use. I believe this portfolio will help me show my skills and progress in cloud computing. It also gives me a record of what I have learned and what I still need to improve.
