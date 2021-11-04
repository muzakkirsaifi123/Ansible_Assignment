# Ansible


To deploy the webservers execute the command:

`ansible-playbook  master.yml`


If you wanna execute specific task then you can use the tags which i have define in every tasks like this 

`ansible-playbook  master.yml --tags <tage_name>`

for skipping any task use this command 

`ansible-playbook  master.yml --skip-tags <tage_name>`