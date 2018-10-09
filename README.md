# ansible-playbook

Dockerfile inspired by a [rule of tech article](http://ruleoftech.com/2017/dockerizing-all-the-things-running-ansible-inside-docker-container) which enables users to run Ansible playbooks without installing Ansible and it's dependencies on the local machine.

Changes from the article's version are Ansible version, and the inclusion of the dopy pip module to enable actions to be taken against the DigitalOcean API.

Docker images are available from [Docker hub](https://hub.docker.com/r/rgee0/ansible-playbook/tags/)
