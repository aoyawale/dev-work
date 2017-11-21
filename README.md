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
  - name: venv1
    path: /root/venv1
    packages:
      - ansible
      - requests
      - json
  - name: venv2
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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
