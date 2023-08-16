# kode-kloud-Lab-Inventory
my approach to the hands on coding exercises from kodekloud.com "Lab-Inventory"

Exercise 1: We have a sample "inventory" under "/home/bob/playbooks" directory. It has 3 servers listed, add another server called "server4.company.com" in this file. 

Exercise 2: We have reset the /home/bob/playbooks/inventory inventory file, and added the aliases named "web1", "web2", and "web3" for the first three hosts respectively. Update this inventory file to add an alias called "db1" for "server4.company.com" host. 

Exercise 3: The web servers are linux based hosts and the db server is a Windows machine. Update the inventory "/home/bob/playbooks/inventory" to add a similar entry for "server4.company.com" host. Find the required details from the table below. 
    Note: For Linux based hosts, use "ansible_ssh_pass parameter and for Windows based hosts, use "ansible_password" parameter. 

Exercise 4: We have updated the "/home/bob/playbooks/inventory" file and added a group called "web_servers" for web servers. Similarly, addd a group called "db_servers" for database servers. 

Exercise 5: Let us now create a group of groups. Create a new group called "all_servers" and add the previously created groups "web_servers" and "db_servers".

Exercise 6: Update the "/home/bob/playbooks/inventory file to represent the data given in the below table in Ansible Inventory Format.
------------------------------------------------------------ 
| Server Alias | Server Name | OS | User | Password         |
------------------------------------------------------------
| sql_db1 | sql01.xyz.com | Linux | root | Lin$Pass         |
------------------------------------------------------------
| sql_db2 | sql02.xyz.com | Linux | root | Lin$Pass         |
------------------------------------------------------------
| web_node1 | web01.xyz.com | Win | administrator | Win$Pass|
------------------------------------------------------------
| web_node2 | web02.xyz.com | Win | administrator | Win$Pass|
------------------------------------------------------------
| web_node3 | web03.xyz.com | Win | administrator | Win$Pass|
------------------------------------------------------------