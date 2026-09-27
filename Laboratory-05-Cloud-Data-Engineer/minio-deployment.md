# MinIO Deployment

## Docker Command
The MinIO container was deployed using the following Docker command:

```bash
sudo docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
-e "MINIO_BROWSER=on" \
-e "MINIO_CONSOLE_PORT_NUMBER=9001" \
illuin/bitnami-minio:2025.7.23-debian-12-r3
```

The container started successfully and is running with the name `minio-server`.

## Ports
Port 9000 is used for the MinIO API.
Port 9001 is used for the MinIO web console. The web console can be accessed through:

```text
http://localhost:9001
```

## Environment Variables
The `-e` flags are used to set environment variables inside the MinIO container.

```text
-e "MINIO_ROOT_USER=cloudadmin"
```
Sets the MinIO root username to `cloudadmin`.

```text
-e "MINIO_ROOT_PASSWORD=CloudNova2026!"
```
Sets the MinIO root password.

```text
-e "MINIO_BROWSER=on"
```
Enables the MinIO browser or web interface.

```text
-e "MINIO_CONSOLE_PORT_NUMBER=9001"
```
Sets the MinIO console to use port `9001`.

## Bucket
The required MinIO bucket is:

```text
client-photos
```

The `client-photos` bucket is used to store client photo objects in MinIO.

## Verification
The container was checked using:

```bash
sudo docker ps
```

The output showed:

```text
minio-server
```

with ports `9000` and `9001` mapped from the Ubuntu server.
The deployment was successful because the container status showed **Up**.
