Role Name
=========

Role setup http proxy variables on host

Requirements
------------


Role Variables
--------------

Available variables are listed below, along with default values:

* use_proxy: false
* proxy: 
* no_proxy: 127.0.0.1,localhost

Dependencies
------------


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: dbs_proxyconf, tags ["proxyconf"]  }

License
-------

BSD

Author Information
------------------
it's me
