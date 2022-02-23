certbot Role
=========

A brief description of the role goes here.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.certbot-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-certbot/)


Requirements
------------

None

Role Variables
--------------

Refer to default/main.yml file.

```yaml
certbot_configure: true
certbot_sites:
  - site1.domain.tld
  - site2.domain.tld

```

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - neoloc.certbot

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
