### Deploying Ansible script on `Ubuntu 20`

> Update `ansible/inventories/hosts` and `ansible/playbooks/redis/vars/config.yml` files with server IP
> `cd ansible`
> `ansible-playbook playbooks/redis/up.yml -v`

### Useful commands

> redis-cli info replication
> tail -f /var/log/redis/redis-sentinel.log
> netstat -tulpn | grep -i redis