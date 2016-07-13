# Ansible ondrej/php repository role

[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-apt-blue.svg)](https://galaxy.ansible.com/benjamin-smith/ondrej-php-repo/)

Installs the [ondrej/php](https://launchpad.net/~ondrej/+archive/ubuntu/php) repo on Ubuntu systems.

### Requirements

This role does not depend on any other Ansible roles.

### Usage

Simply adding this role to a playbook should be sufficient.

    - hosts: servers
      roles:
         - { role: benjamin-smith.ansible-ondrej-php-repo }

From there, you can use something like [geerlingguy.php](https://galaxy.ansible.com/geerlingguy/php/) to install the PHP version you wish (see the `php_packages` variable to customize `php5.5`, `php5.6`, or `php7.0`).

###License

MIT
