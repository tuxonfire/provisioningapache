# provisioningapache
Installing apache in a single play

# deploy to multiple environments with extra_vars in Ansible Automation Platform survey config
This playbook will be executed according to the environment choosed:
1. webservers 
2. vagrant
3. production

extra_vars survey in Job Template
hosts: "{{ playbook_target }}"
 
