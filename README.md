# Ansible & Ansible Tower

Projects in order to install Apache + Tomcat + MariaDb + Activiti Deployment using Ansible Tower

Add the projects on Ansible tower using git URL : https://github.com/smolino/Ansible.git
Create a new Job template using the new project.

Run Playbooks in the following order:

Apache 
MariaDb
Tomcat
acitivi

Change on the Inventory server selected the group according to the file configuration. ("web" in my case).

Just deploy all instances
