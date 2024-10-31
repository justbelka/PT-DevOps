PostgreSQL 16 Config Role
=========

This role was created by Alex Belokrylov for base configuration of PostgreSQL. The role includes performing basic actions after installing the PostgreSQL package, as well as changing default parameters.

Role Variables
--------------

postgres16_config_role_port             - New port
postgres16_config_role_listen_addresses - New value for listen_addresses
postgres16_config_role_max_wal_senders  - New value for max_wal_senders
postgres16_config_role_hot_standby      - New value for hot_standby

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - role: postgres16_config_role

Author Information
------------------

email: bel.am.2004@gmail.com / justbelka2004@yandex.ru
telegram: @iambelka
