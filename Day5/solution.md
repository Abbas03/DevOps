Tasks:
    1. #!/bin/bash
       n=90
       for((i=1; i<=$n; i++));
       do
       mkdir day{$i}
       done

    2. #!/bin/bash
       m=50
       for((i=20; i<=$m; i++))
       do
       mkdir movie{$i}
       done 

    3. #!/bin/bash
       source_dir="/home/onworks/DevOps/*"
       target_dir="/home/onworks/myBackUp"
       cur_Date=$(date +"%d-%m-%Y)
       mkdir $target/cur_date
       cp -r $source_dir $target_dir/$date

    4.
       Cron is a daemon or service that runs in the background of a Unix system and is responsible for executing scheduled commands or scripts. Cron runs continuously and checks a file called crontab for instructions on when and what commands to run.

       Crontab gis a command-line utility that allows users to create and manage their cron jobs. It is essentially a table that lists the scheduled commands to be run, along with the time and date information for each command.   


       
           