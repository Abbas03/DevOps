Tasks:
1. Creating Directory with three given arguments 
      #!/bin/bash
       if [ "$#" -ne 3]
       then
        echo "Usage: ./createDirectory.sh <directory_name> <start_number> <end_number>"
        exit 1
       fi    
       dir_name=$1
       start_num=$2
       end_num=$3
       for((i=$start_num; i<=$end_num; i++))
       do
         mkdir "$dir_name$i"
       done
       echo "Directories created successfully"  

2.Create a Script to backup all your work done till now.       
      #!/bin/bash
       source_dir=$1
       target_dir=$2
       cur_Date=$(date "+%d-%m-%Y)
       backup_file=${target_dir}/${cur_Date}.zip
       echo "backup on ${cur_Date}
       tar czf $backup_file --absolute-names $source_dir
       echo "Backup complete successfully"


    4.
       Cron is a daemon or service that runs in the background of a Unix system and is responsible for executing scheduled commands or scripts. Cron runs continuously and checks a file called crontab for instructions on when and what commands to run.

       Crontab gis a command-line utility that allows users to create and manage their cron jobs. It is essentially a table that lists the scheduled commands to be run, along with the time and date information for each command.   


       
           