# Laboratory Activity 9: The Cloud Automation Engineer

## Mission Overview
In this laboratory activity, I learned how to automate simple tasks in Linux using Bash scripts and cron jobs. I created a backup script to copy important client data and learned how to schedule tasks to run automatically. This activity helped me understand how automation can save time and make server management easier.

## Objectives
- Understand the fundamental syntax of a Bash shell script, including variables and basic commands
- Use a command-line text editor (nano) to write and save executable scripts
- Modify Linux file permissions using the chmod command
- Understand task scheduling and the syntax of a Linux crontab
- Document automation code and Cron job configurations using Markdown
- Complete the final chapter of my GitHub Cloud Computing Portfolio

## Commands Executed
- `mkdir app-data`
- `echo "This is critical client data." > app-data/data.txt`
- `nano backup.sh`
- `./backup.sh`
- `chmod +x backup.sh`
- `ls -l backups/`
- `crontab -l`
- `env EDITOR=nano crontab -e`

## Skills Learned
In this activity, I learned how to create and run a Bash script to automate simple tasks. I also learned how to use `chmod +x` to make a script executable and how to check the files inside a backup folder. I became more familiar with cron jobs and how they can run tasks automatically at a scheduled time. This activity showed me that automation is useful because it reduces repetitive work and helps keep important files organized. Overall, I gained more experience using Linux commands and managing tasks on a cloud server.
