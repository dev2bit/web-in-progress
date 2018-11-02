# Proyecto web en curso
Recomendaciones para un proyecto web en curso

## General

- [ ] Compbrobar que se disponen de todos los accesos: FTP, admin, paneles de gestión de servidores, base de datos...
- [ ] Realizar auditoría de software y de sistemas: revisar errores, recapitular módulos y versiones, acotar rendimiento, buscar malware...
- [ ] Realizar una copia de seguridad de los sistemas: código de la aplicación, base de datos, configuración de servicios...
- [ ] Dependiendo los sistemas, las necesidades del cliente y los ajustes a realizar se deberá valorar si poner el sistema en mantenimineto

## Migraciones

- [ ] Estimar el rendimiento de la aplicación en el nuevo hardware
- [ ] Elegir un hosting que cubra los requisistos técnicos de la aplicación
- [ ] Crear un dominio local que apunte a la nueva dirección
- [ ] Migrar los ficheros de código aplicación
- [ ] Migrar los ficheros de datos de usuario
- [ ] Migrar la base de datos
- [ ] Migrar las configuraciones de sistemas: virtualhosts, php.ini...
- [ ] Migrar otros datos relacionados: dominios, cuentas de email
- [ ] Comprobar que la transferencia de datos no presenta errores mediante checksum
- [ ] Comprobar permisos del sistema de directorios
- [ ] Comprobar la configuración de la aplicación: conexión de base de datos, definición de URLs...
- [ ] Configurar certificados de seguridad si procede
- [ ] Comprobar tanto en el frontend, como en el backend, que todas las conexiones de red se hagan a los servidores correctos
