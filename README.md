###<strong>Ansible playbook to create a MySQL database and add a user to it </strong> 

***
<strong>Usage:</strong> <br />
ansible-playbook -i inventory mysql.yml
***

<strong>Explanation for each variable:</strong>

db_name ==> Database name. <br /> 
db_user ==> Database user<br />
db_password ==> Database password. <br />
db_host ==> User host variable, by default localhost. <br />
