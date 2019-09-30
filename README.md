Ansible Workstation Collection
==============================

[Ansible Galaxy Collection: Server](https://galaxy.ansible.com/crivetimihai/server):

- xrdp: xrdp with tigervnc

Tested on:
----------

- CentOS 7
- RHEL 8
- Fedora 30
- Ubuntu 18.04
- Debian 10

Example
-------

### Install the role:

```bash
ansible-galaxy collection install crivetimihai.server
```


### playbook.yml example

```yaml
- name: setup a server environment
  hosts: all
  connection: local
  become: yes
  gather_facts: yes
  roles:
    - role: crivetimihai.server.xrdp
```

# See also:

- [Ansible Virtualization Collection](https://galaxy.ansible.com/crivetimihai/server)
