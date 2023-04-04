1.Create a sample file and to give three categories permission:

touch manosudo 
ls -ltr | grep mano

sudo chown root filename

sudo chgrp ubuntu filename
 
sudo chmod 777 filename

ls -ltr | grep mano

2.write about file permission:

 1.File permissions are used to control access to files and directories. 
 Every file and directory on a Linux system has a set of permissions that determine who can read, write, or execute them.
 2.File permissions are divided into three categories: read, write, and execute. 
 3.Each of these categories has three levels of access: owner, group, and others.
 4.The permissions are represented by a series of letters or numbers, such as "rwxr-xr--". 
  i.first character --->such as "-" (for file)/"d" (for directory). 
  ii.The next three characters ---> owner's permissions
  iii.The next three character ---> group's permissions
  iv.The last three character ---> all other users
 5.r --->read
   w --->write
   x --->execute
 6.We can change the permission to files/directories.
  'chmod' command is used to change permission to file/directories in linux
   syntax:sudo chmod [permissions][file/directory]
   sudo chmod 777 mano
   The numbers represent the permissions as follows:

    4 = read
    2 = write
    1 = execute 

   so.777 means
    7=4(read)+2(write)+1(execute) ---> access to owner
    7=4(read)+2(write)+1(execute) ---> access to group
    7=4(read)+2(write)+1(execute) ---> access to others.

3.ACL(Access Control List) -which is a set of permissions to a file or directories.
  Its is provide more fine-grained control over file permissions than traditional Unix file permissions.

  The getfacl and setfacl commands are used to view and modify ACLs on files and directories.  
  1.getfacl(get file access control list) ---> display the acls of a file or directory
    syntax: getfacl [file/directory] 
  2.setfacl(set file access control list) ---> modify the acls of a file or directory
    syntax: setfacl -m u:mano:rwx [file/directory]