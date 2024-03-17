This Repository is made to deploy Apache HTTP server on ubuntu by using ansible. Apache server will run a static website. The playbook makes the setup procedure for Apache simpler.

### Deploying the Apache Docker Container

#### Task1: Creating GitHub repository and web page
In this step, all the necessary steps were taken to create a GitHub repository name “Convenient container deployment” to store the files such as web page, readme and ansible template. 

#### Task2: Building Ansible Playbook
The deployment procedure was automated with the help of Ansible playbook called create-project.yml file. In this playbook the code is written to deploy Apache docker container to run a web page. For this project, two oracle virtual machines are built with ubuntu image such that one is used as control node and another as managed node. On control node, ansible software and other necessary packages are installed to start the process of automation of deploying Apache docker container on managed node

#### Task3: Configure Network Communication for Apache Docker Container
Ansible modules are used to configure Docker container subnet and other network settings to make Apache service accessible. For this purpose, code is written in ansible playbook called create-project.yml. Code is written in ansible playbook to create docker network and the then to network settings are done such as setting the IP address and volumes.

#### Conclusion
This assessment project shows how to deploy web apps using Ansible and Docker in an efficient manner. We were able to save time and lower the risk of human mistake by automating the deployment procedure with the help of these tools.
It shows that a project might be easily managed and tracked by using a GitHub repository for version control. The deployment procedure was greatly aided by the Ansible playbook. It involved setting up the Docker environment and launching the Docker container and also configuring the network settings for the Apache server.

The virtual machine with IP address 172.168.10.2 was successfully used to launch the Docker container that was running an Apache server. Docker's usefulness for web hosting was demonstrated by the way the container was set up to serve a static webpage. 

The significance of network settings for Docker deployments was also emphasized. Traffic from the host system was successfully permitted on the container network, and the Docker container was set up to operate on the 172.168.10.0/30 subnet.



