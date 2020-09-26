# Mysql

```
ansible-playbook -i hosts.yaml mysql.yaml -e "mysql_root_password=<password>"
```

# PDNS

```
ansible-playbook -i hosts.yaml pdns.yaml -e "mysql_root_password=<password> powerdns_password=<password>"
```