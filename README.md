Role Name : prometheus-role
---------

This role helps you in setting up monitoring system for your Linux(Ubuntu) systems.Strictly not recommended for Production.

Example Playbook
----------------

    - hosts: servers
      roles:
         - prometheus-role

Default ports:
--------------
Prometheus: 9090
grafana: 3000
node_exporter: 9100


Author Information
------------------

Ravikiran Rapelli
