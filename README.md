# ansible-jenkins

Ansible Playbook for provisioning a Jenkins CI server behind an Nginx proxy.

Tested on Ubuntu 16.04 x64.

### Usage

```
ansible-playbook -i myserver.example.com, jenkins.yml
```

### Why is Docker installed?

This playbook includes installation of docker-engine and docker-compose as I personally use Docker to run unit tests for my apps.  If you don't use Docker then it's safe to remove them from the playbook.
