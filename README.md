# asir-active-directory-security-lab
Proyecto Intermodular ASIR: despliegue y securización de una infraestructura empresarial virtualizada con Active Directory y Wazuh.


Despliegue y securización de una infraestructura empresarial con Active Directory y Wazuh

Descripción del proyecto

Proyecto Intermodular del Ciclo Formativo de Grado Superior en Administración de Sistemas Informáticos en Red (ASIR), correspondiente al curso 2026-2027.

El proyecto consiste en desplegar una infraestructura informática virtualizada para una pequeña empresa, centralizando la administración de usuarios, equipos y recursos compartidos mediante Active Directory e incorporando Wazuh para la monitorización de eventos de seguridad.

Objetivos

- Implementar un dominio empresarial con Active Directory y DNS.
- Configurar dos controladores de dominio y verificar su replicación.
- Gestionar usuarios, grupos, permisos y políticas de seguridad mediante GPO.
- Desplegar un servidor de archivos con permisos SMB y NTFS.
- Centralizar la monitorización de eventos de seguridad mediante Wazuh.
- Documentar el proceso de implementación y verificar su funcionamiento mediante pruebas.

Arquitectura prevista

La infraestructura se desplegará en VMware Workstation y estará compuesta por:

Sistema	Función
DC01	Controlador de dominio principal y DNS
DC02	Segundo controlador de dominio y DNS
FILE01	Servidor de archivos
CLIENT01	Equipo cliente Windows 11
WAZUH01	Servidor de monitorización basado en Ubuntu Server

Las máquinas virtuales estarán conectadas a una red privada de laboratorio.

Tecnologías

- VMware Workstation
- Windows Server
- Active Directory Domain Services
- DNS
- Group Policy Objects (GPO)
- SMB y NTFS
- Windows 11
- Ubuntu Server
- Wazuh
- Git y GitHub
- Notion

Documentación

La documentación técnica se organizará en el directorio docs/ e incluirá la descripción del proyecto, la arquitectura, el despliegue, las configuraciones, las pruebas y las incidencias encontradas.

Estado del proyecto

Fase actual: planificación y preparación del entorno.

Las funcionalidades se implementarán progresivamente y se validarán mediante pruebas documentadas.

Autoría

Proyecto académico desarrollado en el marco del CFGS de Administración de Sistemas Informáticos en Red (ASIR), curso 2026-2027.
