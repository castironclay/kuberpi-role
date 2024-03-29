Role Name
=========

This role  is used to setup an HA Kubernetes cluster with 7 Raspberry Pis.<br>
This role will end with a 5 node cluster (2 masters and 3 workers) all in the ready status with the Weave network overlay.<br>

Requirements
------------

All hosts that will be targeted by this role should be flashed with [Hypriot](https://blog.hypriot.com/downloads/) v1.10 and not the traditional Raspbian image. 

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None. This is an all-in-one role.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache