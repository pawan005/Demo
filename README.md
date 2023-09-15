# ansible-demo
Ansible Demo

## Test whether all the host in the inventory file are connecting or not
```
syntax: ansible -i <filename> <server group name from inventory file> -m <command>
ansible -i inventory all -m ping 

```


ansible-playbook -i inventory2 install-apache.yaml -u ansible --ask-become-pass

ansible-playbook -i inventory2 install-apache-redhat.yaml --ask-become-pass


### Add user to sudoers list. In case of CentOS or RedHat use following command to add user to Wheel group. Wheel group has sudo persmission
usermod -aG wheel ansible

 git clone https://github.com/bharatbalothia/ansible-demo.git



Put following in ~/.ansible.cfg

[defaults]
host_key_checking = False
