# Ansible - Proyect 3

This project is to test invetory . You must locate it in the project folder and execute the following command to run playbook over a group of servers
```
sudo ansible servers1 -a "date"
```
The inventory file have a group of servers, in this case servers1 is the name of the group one, therefore we also provide variables in the same file using name_of_group:vars