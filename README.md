# Ansible plabyook for install LAMP on CentOS6-7

An ansible playbook for install Linux Apache Mysql PHP (plus Redis) on CentOS6-7

## How to run
-  create hosts file with your target server ip
```
192.168.56.102
192.168.56.103
192.168.56.104
```

- Change your ssh user in playbook.yml
```yaml
   user: vagrant
```

- Run ansible-playbook command
```sh
$  ansible-playbook -i hosts playbook.yml -k
```
