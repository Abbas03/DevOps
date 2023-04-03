Task1:
     solution:
     1. cat filename.extension
     2. chnmod 777 filename.extension
     3. history
     4. rmdir foldername/directory
     5.  i.  vim fruits.txt
         ii. cat fruits.txt
     6. vim devops.txt
        cat devops.txt
        Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.
     7.head -3 devops.txt
     8.tail -3 devops.txt
     9.vim Colors.txt
       cat Colors.txt
        Red, Pink, White, Black, Blue, Orange, Purple, Grey
     10.diff fruits.txt Colors.txt

Task2:
     solution:
     1.
         * A shell script is a text file that contains a sequence of commands for a UNIX-based operating system. 
         * It is called a shell script because it combines a sequence of commands.
         

     2. 
       1. #!/bin/bash is called a "shebang" or "hashbang" line at the beginning of a shell script file. It indicates that the script should be executed by the Bash shell (or any compatible shell) located at /bin/bash on a Unix-like operating system.

       This allows shell scripts to be written in different scripting languages and executed by the appropriate interpreter.

       2.yes. we can write. #!/bin/sh should work on most Unix-based systems, since it refers to the system's default Bourne shell interpreter.

    3. #!/bin/bash

       echo " I will complete the challenges"

    4. #!/bin/bash

       echo "Enter a number"
       read num
       echo "The number is $num"

    5. #!/bin/bash
       echo "Enter the first number"
       read num1
       echo "Enter the second number"
       read num2
       if[[$num1 -gt $num2]]; then
          echo "$num1 is greater number"
       else
          echo "$num2 is greater number"
       fi              
      



