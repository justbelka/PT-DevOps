Debian 11 Config Role
=========

This role was created by Alex Belokrylov for base configuration of Debian servers. The role includes performing basic actions after installing the system, as well as installing packages from the list and changing the base hostname.

Role Variables
--------------

debian11_config_role_hostname - New system hostname
debian11_config_role_timezone - New system timezone
debian11_config_role_packages - New packages are need to be installed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - role: debian11_config_role

Author Information
------------------

email: bel.am.2004@gmail.com / justbelka2004@yandex.ru
telegram: @iambelka
