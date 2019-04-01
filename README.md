# UserProvisioner
Playbook is Used for adding access to the group servers.
This Project is having 3 files 
1) main.yml -- Playbook Used for create a user and add him in the sudoers list so that he can able to access commands and add public ssh key for the password less authentication.
2) hosts.ini -- hosts file is used for list of servers that needs to be updated with users.
3) removeuser.yml -- this playbook is used for invoking access/removing users from list of servers.
