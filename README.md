# Ansible auto mount disk to hosts

## Check disk before auto mount
``` 
ansible-playbook playbooks/discover_disks.yml -i inventory/hosts.ini
```
![img_1](https://github.com/datvo2k/ansible-auto-discovery-disk/blob/main/img/Screenshot%202025-09-02%20at%2017.07.16.png)
![img_2](https://github.com/datvo2k/ansible-auto-discovery-disk/blob/main/img/Screenshot%202025-09-02%20at%2017.07.39.png)


## Mount disk
``` 
ansible-playbook playbooks/add_disks.yml -i inventory/hosts.ini
```
![img_3](https://github.com/datvo2k/ansible-auto-discovery-disk/blob/main/img/Screenshot%202025-09-02%20at%2017.07.47.png)
