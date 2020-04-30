# Description
ansible hands-on

# Usage
```$xslt
$ docker-compose up -d
$ docker-compose exec controller /bin/bash
$ cd /ansible
$ ansible-playbook -i inventories/docker/hosts nginx.yaml
```

access to `http:127.0.0.1:8080` from host machine

