Ansible-pyenv
=========

Pyenv installer/configuror

Requirements
------------

host
shell
git

Role Variables
--------------

```
    python_versions:
      - 2.7.9

    python_global:
      - 2.7.10
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: hosts
      roles:
         - { role: speed-of-light.ansible-pyenv }

License
-------

MIT

Author Information
------------------

I'm speed-of-light
