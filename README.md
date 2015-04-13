Role Name
=========

Base setup for a Ubuntu box
Role Variables
--------------

```
# Setup hostname
base_host_name: dev.local
# Setup intial user
base_setup_user: linhtm
```

Example Playbook
----------------

```
- hosts: servers
  sudo: yes
  vars:
    base_host_name: dev.local
    base_setup_user: vagrant
  roles:
    - linhmtran168.base
```

License
-------

MIT

Author Information
------------------

Linh M. Tran
