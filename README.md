https://github.com/morheus9/Role_docker/

[![GitHub release](https://img.shields.io/github/release/morheus9/StrapDown.js.svg)](https://GitHub.com/morheus9/Role_docker/releases/)
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

