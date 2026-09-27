# Reflection

**1. Why is object storage better suited for storing millions of photos compared to a traditional block storage hard drive?**
I think object storage is better for millions of photos because it is made for storing large amounts of unstructured data. A traditional block storage drive has limited space and usually needs more setup when the storage needs to grow. Object storage can scale much more easily, so it can handle a large number of photos without needing to treat them like files on one hard drive.

**2. How did using Docker make it easier to deploy the MinIO storage server?**
Docker made the deployment much easier for me because I only needed one main command to start MinIO. Docker automatically downloaded the required image and started the container. I did not have to manually install and configure many files. Seeing MinIO running after the command made me realize how useful containers are for quickly setting up services.

**3. What is a "bucket" in the context of cloud storage?**
A bucket is like a container where objects or files are stored. In this activity, I used the bucket name `client-photos`. I can think of it as a folder for organizing photos, although it works differently from a normal folder on a computer. Files can be uploaded and managed inside the bucket.

**4. How do you think large enterprise companies ensure their object storage data is not lost if the physical server crashes?**
I think companies use redundancy, replication, and backups to protect their data. They can keep multiple copies of the same data on different servers or locations. This means that if one physical server crashes, another copy can still be available. This helps reduce the chance of permanently losing important files.

**5. How is your confidence in navigating the Linux command line growing?**
My confidence with Linux is improving compared to my first lab. I have learned how to create users, use Git, navigate folders, run Docker commands, and troubleshoot errors. I still make mistakes sometimes, like the Docker permission error, but I now understand the errors better and know that I can troubleshoot them instead of getting stuck.
