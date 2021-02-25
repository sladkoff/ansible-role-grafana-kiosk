ansible-role-grafana-kiosk
=========

Installs [grafana-kiosk](https://github.com/grafana/grafana-kiosk) on a Raspberry Pi.

Requirements
------------

Requires a ssh-enabled Raspberry Pi.

Role Variables
--------------

| variable | description | default | 
| --- | --- | --- |
| grafana_kiosk_user| grafana-kiosk will be installed and launched from this user's `home`. You might have to create the user first. | pi |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

[sladkoff](https://github.com/sladkoff)