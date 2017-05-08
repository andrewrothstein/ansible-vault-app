andrewrothstein.vault-app
=========================

Role for installing Hashicorp's Vault related applications.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: andrewrothstein.vault-app
      vault_app: vault-ssh-helper
	  vault_app_ver: '0.1.2'
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
