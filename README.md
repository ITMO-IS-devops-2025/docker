Docker
=========

Installs docker on Ubuntu. Role created within educational process and for educational purposes.

Requirements
------------

- Target machine is Ubuntu.

Role Variables
--------------

- docker_prerequired_packages: list of apt packages to be installed before Docker installation

- docker_gpg_apt_key: url to obtain docker GPG apt key

- docker_apt_repository: source string for docker apt repository

- docker_installing_packages: list of apt docker packages to be installed

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - docker

License
-------

MIT

Author Information
------------------

Roman Soloviev
