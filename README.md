Role Name
=========

Install Jenkins.
Pointe browser to:

  http://my-host-ip:8080
  http://127.0.0.1:8080

Insert admin password locate in file /var/lib/jenkins/secrets/initialAdminPassword
Create first user.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - jenkins

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
