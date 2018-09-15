###### Task:

Create a project based on Vagrant tool  https://www.vagrantup.com/ 
Write a configuration based on example https://www.vagrantup.com/docs/provisioning/ansible.html 

System should be based one of the Linux's distribution.
Provisioning made by using Ansible https://www.ansible.com/ , should install Jenkins serwer https://jenkins.io/ 
Create (by Ansible) Bash script which form every 5 min new Job (example task) in Jenkins serwer by using Jenkins CLI.
Script should be activated as a serwis or added to Crone.

Please, place your code on  https://github.com/ 

Using Docker containers for Jenkins serwers and "Job" script wil be an extra advenage.

###### Notes:
Tested on
vagrant 2.0.2
ansible 2.6.4
Full provisioning is done via 
`$ vagrant up`
after provisioning Jenkins is available on http://127.0.0.1:8080 
>Create (by Ansible) Bash script which form every 5 min new Job (example task) in Jenkins serwer by using Jenkins CLI.
>Script should be activated as a serwis or added to Crone.
Script added to cron of VM, job is just a shell showing hostname and date.
Requirement to form every 5 min new job was not clear, maybe the task should say - build job (it will change the jenkins-cli command to build)
