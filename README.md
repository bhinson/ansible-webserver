These are simple examples of managing Apache web services
with Ansible.  This is designed for RHEL 7 servers and newer,
and supports starting/stopping the firewall for ports 80/443.

apache-enable.yml:
---------------
Install, configure, and start apache.

apache-disable.yml:
---------------
Stop and uninstall apache.

apache-stop.yml:
---------------
Stop apache (without uninstalling).
