# CI/CD(Continous Integration - Continous Deployment) on Java Application

# Automating WAR file artifact deployment
Automate Ansible integration with Jenkins CI server, to run and execute playbooks for deploying custom WAR files to a web container and then performing restart for the web container.

Steps :-
- Configuring Jenkins server as Ansible provisioning machine
- Installing Ansible plugins in Jenkins CI server
- Preparing Ansible playbook to run Maven build on Jenkins CI server to Build the .war file
- Preparing Ansible playbook to execute deployment steps on the remote web container with restart of the web container post deployment. using Docker for building the image and running the container on tomcat server.
- <img width="535" alt="Screenshot 2024-03-31 at 4 34 14 PM" src="https://github.com/akshitmittal20/CICD_JavaApplicationDeployment_Ansible_Docker_Jenkins/assets/63283989/c985baef-ca0e-440e-b33f-74977bbdeeb8">



# CICD Implemented
<img width="483" alt="Screenshot 2024-03-31 at 4 32 59 PM" src="https://github.com/akshitmittal20/CICD_JavaApplicationDeployment_Ansible_Docker_Jenkins/assets/63283989/07ca593d-ab8c-4da7-b079-35aa6f824bca">
<img width="443" alt="Screenshot 2024-03-31 at 4 33 09 PM" src="https://github.com/akshitmittal20/CICD_JavaApplicationDeployment_Ansible_Docker_Jenkins/assets/63283989/9a12c867-4bc4-47a3-9155-5363b5541dca">


