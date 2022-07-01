### Requirments
- Ubuntu 20.04

### Install ansible

- ```sudo apt-add-repository ppa:ansible/ansible```
- ```sudo apt-get update```
- ```sudo apt-get install ansible```

### Install project (comment or uncomment what necessary)
- ```ansible-playbook run.yml```

### Delete project (stop processes, uninstal docker container, remove folder)
- ```ansible-playbook clean.yml```
