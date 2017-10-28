Dump Variables
=========

A simple role that will dump all the host's variables to a file.

Requirements
------------

None.

Role Variables
--------------

- **dump_vars_format** The format to write the variables to. Either **yml**, which is the default or **json**.

Dependencies
------------

None

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - { role: dump-vars, dump_vars_format: "json" }

- hosts: all
  roles:
    - dump-vars
```

License
-------

BSD
