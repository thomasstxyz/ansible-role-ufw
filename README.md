ufw
=========

Install ufw firewall, deny all incoming except ssh.

<!-- Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required. -->

Role Variables
--------------

The variable `ufw_ports_allow` contains the list of ports, which are allowed (default: 22).

<!-- Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles. -->

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    hosts: servers

    vars:
    - ufw_ports_allow:
      - 22
      - 80
      - 443

    roles:
    - ufw

License
-------

MIT

Author Information
------------------

This role was created in 2021 by [Thomas Stadler]{https://thomasst.xyz}.
