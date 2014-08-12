Role Name
=========

Role will setup hostname and timezone and installs standard tools.

Tools:

- htop
- strace
- make
- gcc
- lsof
- vim
- curl
- git
- mc
- sysstat
- iotop
- dstat
- iptraf
- screen

Role Variables
--------------

    common_timezone: 'Europe/Kiev'
    common_hostname: 'ubuntu-server'


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webbylab.common, common_hostname: 'myserver', common_timezone: 'Europe/Kiev' }

License
-------

MIT

Author Information
------------------

WebbyLab (http://webbylab.com)