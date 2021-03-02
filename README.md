# Network Automation
Implementation of simple webservice using Ansible
------------------------------------------
In this Assignment, Implementation of simple webservice using ansible playbook is performed.The service is really simple,  basic service is an Nginx web server, that only serves one simple PHP page. That page renders the hostname, IP, and port of the server running it.

Task:
 
Write an ansible-playbook, site.yaml, that deploys the HAproxy, and Nginx on appropriate existing hosts, i.e. the playbook does not need to launch any Virtual Machines. Once the hosts have been configured, the playbook is assumed to run -outside- the site, but -via- the Bastion host. Hence, you need to have an SSH config file that allows your host to use the Bastion host as a jump host, using an SSH key. Furthermore, the Bastion host also needs to have SSH access to all of the site-local hosts, using SSH keys, to avoid typing passwords all the time. The playbook should also do a rudimentary function test of the deployed application. That test is to send three requests to the public IP associated with HAproxy, and verify that all three hosts A, B, and C answers.


