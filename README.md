# Ansible
Ansible is a suite of software tools that enables infrastructure as code. It is open-source and the suite includes software provisioning, configuration management, and application deployment functionality.

## Ansible command
Test ping in server
```sh
ansible "hostname_in_inventory" -i "Inventory_Name" -m ping 
```
Do automation task
```sh
ansible-playbook -i "Inventory_Name" "Playbook_Name"
```

