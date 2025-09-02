# Ansible auto mount disk to hosts

## Check disk before auto mount
``` 
ansible-playbook playbooks/discover_disks.yml -i inventory/hosts.ini
```
![img_1](img/Screenshot 2025-09-02 at 17.07.16.png)
![img_2](img/Screenshot 2025-09-02 at 17.07.39.png)


## Mount disk
``` 
ansible-playbook playbooks/add_disks.yml -i inventory/hosts.ini
```
![img_3](img/Screenshot 2025-09-02 at 17.07.47.png)
