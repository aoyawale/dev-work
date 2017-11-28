Role Name
=========

Install development rpms, pip and gem packages.

Requirements
------------


Role Variables
--------------
```
dev_work:
   rpms:
      - python-pip
      - vim-common
      - ruby
      - python3
  ruby_gems:
      - chef
      - rbenv
  virtualenvs:
  - venv1:
      path: /root/venv1
      packages:
        - ansible
        - requests
        - json
  - venv2
      path: /home/mike/venv2
      packages:
         - fabric
         - json
```


Example Playbook
----------------


License
-------

BSD

Author Information
------------------

