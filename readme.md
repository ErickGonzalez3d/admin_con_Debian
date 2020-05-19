Introducción al curso Debian GNU/Linux
En este curso usaremos la  consola y administraremos los equipos desde la terminal 
los comandos funcionan para casi todas las distribuciones en especial las que estan basadas en debian como centOS o ubuntu 
 
# administración de usuarios y permisos en Debian GNU/Linux

### crear modificar y borrar usuarios en terminal 

Abrimos una sesión y una terminal 
la administración de usuarios la hacemos con el usuario root 
hay dos archivos importantes en la administracion de usuarios /etc/passwd y /etc/shadow 
passwd almacena información de los usuarios que estan registrados en el sistema operativo 
si los vemos con cat nos muestra una lista de usuarios comenzando por el usuario root y una lista de otros usuarios como sys, bin, daemon,  y demas usuarios son de uso del sistema que no tenemos que usarlos  al final de la lista estan los usuarios hemos creados, 
se define el usuario
usuario:x:1000:1000:maquina,,,:/home/usuario:bin/bash --> los valores se separan por ":" 

usuario = indica el nombre del usuario administrador 
x = contraseña hace referencia al archivo shadow 
1000 = user ID  todos los usuarios creados manualmente tienen un 


### crear mmodificar usuarios en GUI
### crear, modificar y borrar 
### permisos de usuario 
### permisos de grupo


# Gestor de paquetes debian 

### dpkg
### apt 
### aptitude
### tasksel 
### synaptic


# Boot, secuencia INIT y Runlevels en debian GNU/Linux 

### Boot y Runlevels 
### programa o comando `chkconfig`


# Particiones del sistema linux 

### Analizando la configuración actual 
### provisionado de espacio en disco duro 

# memoria SWAPen Debian 

### analizando la configuración personal 
### provisionando SWAP desde una particíon 
### provisionando SWAP desde un archivo en una particíon 


# Logical Volume Manager LVM 

### configuración actual 
### instalando y explicando el modelo LVM
### creando un volumen logico 
### renombrado y expansión de volumenes logicos 

# consola o terminal bash 

### Bases 
### Scripts 

# crontab / anacrontab 
### configuración actual 
### programando ejecución de scripts 

# Adaptador de red 

### Herramientas de red basicas 
### conffiguracion del adptador de red en terminal 
### configuración de red virtual 


