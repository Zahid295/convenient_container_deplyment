This Repository is made to deploy Apache HTTP server on ubuntu by using ansible. Apache server will run a static website. The playbook makes the setup procedure for Apache simpler.

### Deploying the Apache Docker Container

####Task1
In this step, all the necessary steps were taken to create a GitHub repository name “Convenient container deployment” to store the files such as web page, readme and ansible template. 

####Task 2: Building Ansible Playbook
The deployment procedure was automated with the help of Ansible playbook called create-project.yml file. In this playbook the code is written to deploy Apache docker container to run a web page. For this project, two oracle virtual machines are built with ubuntu image such that one is used as control node and another as managed node. On control node, ansible software and other necessary packages are installed to start the process of automation of deploying Apache docker container on managed node