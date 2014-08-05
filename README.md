ansible-role-tor-basic
=====

This role installs and configures [tor](https://www.torproject.org/) in a similar way to [Tails](https://git-tails.immerda.ch/tails/plain/config/chroot_local-includes/etc/tor/torrc). 
This role has only been tested in Debian.

Requirements
------------

This role requires Ansible 1.6 or higher.


Role Variables
--------------

All these variables are defined in vars/main.yml and will be used by default.

    ## set to true if the host where the role is running is configured to block
    ## all outbound traffic except tor
    usetor: true

Dependencies
------------


Example Playbook
----------


```
- hosts: localhost

  roles:

    - { role: ansible-role-tor-basic
      }
      }
```

License
-------

GPLv3

Author Information
------------------

Lee Woboo

