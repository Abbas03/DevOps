Day 5 Task: Advanced Linux Shell Scripting for DevOps Engineers with User management

All directories within seconds using a simple command.

 mkdir day{1..90}

Tasks
You have to do the same using Shell Script i.e using either Loops or command with start day and end day variables using arguments -
So Write a bash script createDirectories.sh that when the script is executed with three given arguments (one is directory name and second is start number of directories and third is the end number of directories ) it creates specified number of directories with a dynamic directory name.

Example 1: When the script is executed as

./createDirectories.sh day 1 90

then it creates 90 directories as day1 day2 day3 .... day90

Example 2: When the script is executed as

./createDirectories.sh Movie 20 50 then it creates directories as Movie20 Movie21 Movie23 ...Movie50

Notes: You may need to use loops or commands (or both), based on your preference.

Create a Script to backup all your work done till now.
Backups are an important part of DevOps Engineers day to Day activities.


Read About Cron and Crontab, to automate the backup Script
Cron is the system's main scheduler for running jobs or tasks unattended. 
A command called crontab allows the user to submit, edit or delete entries to cron. A crontab file is a user file that holds the scheduling information.
