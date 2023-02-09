su betty-switches the current user to the user betty
whoami-prints the effective username of the current user.
groups-prints all the groups the current user is part of.
sudo chown betty hello-changes the owner of the file hello to the user betty.

touch hello-creates an empty file called hello.
chmod 744-adds execute permission to the owner of the file
chmod 754-adds execute permission to the owner and the group owner, and read permission to other users, to the file 
chmod 777-adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007- 

    Owner: no permission at all
    Group: no permission at all
    Other users: all the permissions
chmod -R +X -execute permission to all subdirectories of the current directory for the owner, the group owner and all other user

chmod -m751 my_dir-creates a directory called my_dir with permissions 751 in the working directory.

chgrp school hello-Write a script that changes the group owner to school for the file hello

        -script that adds execution permission to the owner, the group owner and the other users, to the file  
