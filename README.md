# ansible
## ansible installation
Install Ansible in Amazon linux machine.

create 3 amazon linux machines(1 master, 2 host machines).

install python in all machines(amazon linux machine has default python).

install ansible on master machine only(amazon-linux-extras install ansible2).

generate key (ssh-keygen) key stored in /root/.ssh/id_rsa.pub.

copy and paste the key in host machine authorised keys (.ssh/authorised_keys).

copy public or private ips of hostmachines in /etc/ansible/hosts .

## Install and Configure postgrsql in host machine using ansible
commands 
```
git clone 
cd ansible
ansible-playbook postgresql.yml
```


## reference for postgresql 
https://computingforgeeks.com/how-to-manage-postgresql-database-with-ansible/

## reference link for ansible vault
https://www.linuxtechi.com/use-ansible-vault-secure-sensitive-data/

## encrypt specific string using vault
```
ansible-vault encrypt_string 'Passw0rd' --name 'db_password'
```

![image](https://user-images.githubusercontent.com/99127429/154667698-f9ee06c4-59e5-4ebf-8f1a-6254a2694410.png)

















## link for writing readme file
https://markdown-it.github.io/
