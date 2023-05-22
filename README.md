Role Name
=========

vector-role

Requirements
------------

None

Role Variables
--------------

- vector_version - версия vector, которая будет установлена
- vector_config_dir - директория с конфигурацией vector

Dependencies
------------

None

Example Playbook
----------------

```text
---
- name: vector
  hosts: vector
  roles:
    - vector
```

License
-------

BSD

Author Information
------------------
 None
