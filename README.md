docker-compose
=========

install docker-compose (tested in CoreOS)

Requirements
------------

none

Role Variables
--------------

Default variables are:

```
docker_compose_user: core
docker_compose_compose_file_root: /home/core/compose
docker_compose_environment_file_root: /etc/sysconfig/compose.d
docker_compose_version: 1.21.2
docker_compose_filename: docker-compose
docker_compose_location: /opt/bin
docker_compose_location_mode: 0755
docker_compose_file_mode: a+x
```

Dependencies
------------

none

Example Playbook
----------------

```
- hosts: servers
  roles:
    - { role: docker-compose }
```

License
-------

MIT

Author Information
------------------

[Sho DOUHASHI](https://github.com/douhashi)
