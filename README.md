install_docker
=========

Ansible role to install docker


Role Variables
--------------
docker_prerequisite_packages: packages required to be installed before installing docker.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: respiro.install_docker

License
-------

MIT / BSD
 