# kode-kloud-Lab-Inventory
my approach to the hands on coding exercises from kodekloud.com "Lab-Inventory"

Exercise 1: We have a sample "inventory" under "/home/bob/playbooks" directory. It has 3 servers listed, add another server called "server4.company.com" in this file. 

Exercise 2: We have reset the /home/bob/playbooks/inventory inventory file, and added the aliases named "web1", "web2", and "web3" for the first three hosts respectively. Update this inventory file to add an alias called "db1" for "server4.company.com" host. 

Exercise 3: The web servers are linux based hosts and the db server is a Windows machine. Update the inventory "/home/bob/playbooks/inventory" to add a similar entry for "server4.company.com" host. Find the required details from the table below. 
    Note: For Linux based hosts, use "ansible_ssh_pass parameter and for Windows based hosts, use "ansible_password" parameter. 