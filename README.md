[![Latest Stable Version](https://img.shields.io/packagist/v/phplicengine/bitly?label=version)]([https://github.com/morheus9/Role_docker](https://github.com/morheus9/Role_docker))

Docker
=========

Installs Docker from docker repo and added users to docker group.

Role Variables
--------------
Defaults:
```
add_prune_job_to_cron: false
delete_prune_job_from_cron: false  
```
Example Playbook
----------------
```
- name: Install docker
  hosts: staging_servers
  become: true
  roles:
    - role: docker
```
Author Information
------------------

nodegopher@gmail.com
Nagornov Vyacheslav

