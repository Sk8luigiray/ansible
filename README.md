# Ansible
## Instalacion y puesta en marcha



## Playbooks disponibles
- main-pb.yml: Para hacer la config inicial de una maquina o contenedor LXC, instalar paquetes adicionales como s3cmd o fail2ban, e incluso restaurar copias de seguridad de algunos servicios.
- launch-backup.yml: Para ejecutar de forma manual el script launch-host-backup.sh que se encuentra en todas las maquinas con backup disponible.
- update-cicd-services.yml: Para actualizar las imagenes Docker de las aplicaciones de CI/CD disponibles en nuestra infraestructura.

## Fichero hosts

Tras la configuracion inicial de Ansible, se usa el fichero hosts.yml que se encuentra en este mismo repo. 
