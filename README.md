#README.md

Este proyecto es para la automatización de instalación de la plataforma Atlassian en modo Server.

- Uso de Ansible para instalaci{on de Oracle Java JDK 8 
- Uso de Ansible para la creación de Usuario.
- Uso de Ansible para la creación de Base de Datos PostgreSQL.


Ejemplo: 

ansible-playbook installjava oraclejdk8.yml



Inventario Atlassian
----


[webservers]
jira.cybersyn.com
confluence.cybersyn.com
bitbucket.cybersyn.com
bamboo.cybersyn.com

[database]
postgres.cybersyn.com
