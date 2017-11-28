Role Name
=========

Install development rpms, pip and gem packages.

Requirements
------------


Role Variables
--------------
group_vars

```
dev_work:
   rpms:
     - python-pip
     - vim-common
     - ruby
     - python3
   pip:
     - virtualenv
  ruby_gems:
      - chef
      - rbenv
  virtualenvs:
  - venv1:
      path: /root/venv1
      packages:
        - ansible
        - requests
  - venv2
      path: /home/mike/venv2
      packages:
         - fabric
```


Example Playbook
----------------


License
-------

BSD

Author Information
------------------

