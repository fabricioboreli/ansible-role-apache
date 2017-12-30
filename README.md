Apache 2.x
==========
Ansible Role that install [Apache HTTPD](https://httpd.apache.org/ "HTTP Server Project").  

Requirements
------------
Debian 8 or 9  
CentOS 7  

Role Variables
--------------
None.

Dependencies
------------

None.

Example Playbook
----------------
```yaml
---
- name: Install Apache2 HTTPD
  hosts: webserver01
  become: true
  gather_facts: true

  roles:
    - role: ansible-role-apache
```

License
-------

MIT

Author Information
------------------

Fabricio Boreli  
fabricioboreli at openmailbox dot org
