su betty switches current user to user betty
whoami prints the effective username of the current user
groups prints all the groups the current user is part of
chown changes file ownership
touch hello creates empty file hello
chmod modifies file permissions
chmod 774 adds execute permissions to owner and group owner and read to others
chmod 755 hello adds execution permission to owner, group owner and others for hello
chmod 007 hello modifies hello file permissions to none for owner and group owner and all for others
chmod 753 hello sets hello file persmissions to all for owner, read and execute for group ownwer and write and excecute for others
chmod 644 hello mirrors permissions of olleh file which has rw-r--r--
chmod 755 directory sets executable permission to directory 0x01-shell_permissions for owner, group and others
chgrp school hello sets hello file's group owner to school
