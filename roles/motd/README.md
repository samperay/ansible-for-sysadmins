Role Name
=========

This would be used for configuring system info while you log into the host

Requirements
------------

Ensure you have installed package 'motd'

Role Variables
--------------

Defined system owner(system_owner) and environment (env) fot roles in the playbook

Dependencies
------------

There are no dependencies on this role

Example Playbook
----------------

Create a playbook, and use the role as below
  ```
    --- 
    hosts: servers
    become: yes

    roles:
      - motd
  ```

ansible-playbook -i <inventoryfile> <yourplaybook>  

License
-------

Free

Author Information
------------------

You can drop me an email if anything more is required on this role, you are free to fork and update your code and feel free to get PR
