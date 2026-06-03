# \# Servidores de aplicaciones

# 

# \## Descripción

# Despliegue de aplicaciones Java con Tomcat y Python con Flask+Gunicorn,

# con Nginx como proxy inverso, sobre una máquina virtual Debian con Vagrant.

# 

# \## Cómo ejecutarlo

# 1\. Instalar Vagrant y VirtualBox

# 2\. Clonar el repositorio

# 3\. Ejecutar: vagrant up

# 4\. Añadir al fichero hosts de Windows: 192.168.57.20 apps.sistema.test

# 

# \## Servicios

# \- Tomcat en http://192.168.57.20:8080

# \- App Java en http://192.168.57.20:8080/tomcat1

# \- App Flask en http://apps.sistema.test

# 

# \## Credenciales Tomcat

# \- Usuario: alumno / 1234

# \- Usuario deploy: deploy / 1234

