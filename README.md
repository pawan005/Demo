# ansible-demo
Ansible Demo

## Test whether all the host in the inventory file are connecting or not
```
syntax: ansible -i <filename> <server group name from inventory file> -m <command>
ansible -i inventory all -m ping 

```
