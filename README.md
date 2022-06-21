# intoduction 

This playbook Contains Ansible configuration to install Apache web server, Nginx on Three (3) VM's.

Used Roles feature to Create two users to access the hosts via SSH without password.

Used Another Role to Install and Confgiure Nginx on Ubuntu Systems.

The Nginx acts a load balancer by using "balancer" role.

The Nginx VM serves a PHP page. Any request sent to Nginx VM will be forwarded to Other TWO VM's.

