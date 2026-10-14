# Backup Script Guide

## The Script (backup.sh)

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p $BACKUP_DIR

# Compress the source directory into a tarball (.tar.gz)
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"
```

## What did chmod +x do?

The `chmod +x backup.sh` command gives the file permission to run as a program. Without this permission, Linux may show a permission denied error when I try to execute the script. After adding the permission, I can run it using `./backup.sh`.

## Cron Expression

```bash
0 2 * * * /home/ccastillo/backup.sh
```

| Field | Value | Meaning |
|---|---|---|
| Minute | 0 | The task runs at the start of the hour. |
| Hour | 2 | The task runs at 2:00 AM. |
| Day of Month | * | The task runs every day of the month. |
| Month | * | The task runs every month. |
| Day of Week | * | The task runs every day of the week. |

This cron job schedules the backup script to run automatically every night at 2:00 AM. The script path must match the actual location of `backup.sh` on the server.
