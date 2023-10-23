# Ej 1

regedit
Descripción:
Es el editor del registro de Windows, una herramienta gráfica que le permite ver y supervisar el registro del sistema operativo de Windows y editarlo si es necesario

http de descarga:
Ya viene con Windows

http de tutorial/manual de uso:
https://www.softzone.es/windows/como-se-hace/regedit/


Cobian Backup
Descripción:
Cobian Backup es un programa multitarea que podemos usar para crear y restaurar copias de seguridad de nuestros archivos y directorios

http de descarga:
https://www.cobiansoft.com/download.php?id=1

http de tutorial/manual de uso:
https://computerhoy.com/paso-a-paso/software/como-hacer-backup-cobian-backup-3322

Backup4all
Descripción:
es un programa de copia de seguridad para Windows que protege tus datos de la pérdida parcial o total. Automatiza el proceso de copia de seguridad, 
lo que te ahorra tiempo, comprime los datos para ahorrar espacio de almacenamiento y cifra las copias de seguridad para protegerlas del uso no autorizado

http de descarga:
https://www.backup4all.com/

http de tutorial/manual de uso:
https://seguridadcallosa2013.blogspot.com/2013/05/tutorial-del-programa-backup4all.html

Amanda Open Source 
Descripción:
es una solución de respaldo que permite al administrador de TI configurar un único servidor de respaldo maestro para respaldar múltiples hosts a través de la red
en unidades de cinta/cambiadores o discos o medios ópticos. Amanda utiliza utilidades y formatos nativos (por ejemplo, dump y/o GNU tar) y puede realizar copias
de seguridad de una gran cantidad de servidores y estaciones de trabajo que ejecutan múltiples versiones de Linux o Unix.

http de descarga:
https://www.amanda.org/download.php

http de tutorial/manual de uso:
https://www.sergio-gonzalez.com/personales/ingenieria_informatica/sistemas_informaticos/documentacion/amanda/amanda.html

Afbackup Open Source 
Descripción:
es un sistema de copia de seguridad cliente-servidor que permite a muchas estaciones de trabajo realizar copias de seguridad en un servidor central (simultáneamente o en serie. 
Se utiliza para mantener archivos en un servidor de respaldo o en un archivo. Los archivos se pueden crear, extraer o enumerar su contenido.

http de descarga:
https://www.fbackup.com/download.html

http de tutorial/manual de uso:
https://www.hostinet.com/formacion/backups/como-crear-copias-de-seguridad-con-fbackup/

Burt Open Source 
Descripción:
Es un sitema de copias de seguridad de redes creado en la universidad de Wisconsin. Está diseñado para hacer copias de seguridad de grandes redes heterogeneas

http de descarga:
https://pages.cs.wisc.edu/~jmelski/burt/download.html

http de tutorial/manual de uso:
https://pages.cs.wisc.edu/~jmelski/burt/docs.html

BRU Comercial
Descripción:
La cual proporciona servicios de respaldo y recuperación de datos tipo cliente/servidor a través de  cualquier tamaño de red.
http de descarga:
https://www.tolisgroup.com/requestdownloads.html

http de tutorial/manual de uso:
https://www.tolisgroup.com/assets/argest_backup_user_guide.pdf:

Arkeia Comercial 
Descripción:
Es un software de copia de seguridad y almacenamiento en red network para Windows, Macintosh, Linux, AIX, BSD y HP-UX

http de descarga:
https://support.wdc.com/arkeia/software.aspx

http de tutorial/manual de uso:
http://www.linuxfocus.org/Castellano/May2000/article149.shtml

Mondo Open Source 
Descripción:
Realiza una copia de seguridad de su servidor o estación de trabajo GNU/Linux en cinta, CD-R, CD-RW, DVD-R[W], DVD+R[W],
NFS o partición de disco duro. En caso de una pérdida catastrófica de datos, podrá restaurar todos sus datos [o tantos como desee], 
desde cero si es necesario

http de descarga:
http://www.mondorescue.org/downloads.shtml

http de tutorial/manual de uso:
http://www.mondorescue.org/docs.shtml

Cron
Descripción:
Es un demonio (que es como se conoce a un proceso en segundo plano) que se ejecuta desde el mismo instante en el que arranca el sistema operativo.
Cron se encargará de comprobar si existe alguna tarea (job) para ser ejecutada, de acuerdo a la hora configurada en el propio sistema operativo

http de descarga:
apt install cron

http de tutorial/manual de uso:
https://www.redeszone.net/tutoriales/servidores/cron-crontab-linux-programar-tareas/

FACES
Descripción:
Es un sistema de reconocimiento facial que te permitirá proteger el acceso a tu usuario de Windows mediante un sistema de reconocimiento facial

http de descarga:
https://face.softonic.com/?ex=RAMP-1462.1

http de tutorial/manual de uso:
https://administracionelectronica.gob.es/PAe/FACE/manualproveedores

rsync
Descripción:
Transfiere y sincroniza archivos o directorios de manera eficiente entre una máquina local, un servidor remoto o cualquiera de estos

http de descarga:
sudo apt install rsync

http de tutorial/manual de uso:
https://www.hostinger.es/tutoriales/rsync-linux

duplicity
Descripción:
Es un programa de copias de seguridad en red

http de descarga:
sudo apt install duplicity

http de tutorial/manual de uso:
https://wiki.archlinux.org/title/Duplicity_(Espa%C3%B1ol)


Symantec Ghost
Descripción:
Es un programa para la clonación de discos

http de descarga:
https://norton-ghost.uptodown.com/windows

http de tutorial/manual de uso:
https://www.ubackup.com/es/articulos/como-se-usa-norton-ghost.html

Acronis True Image
Descripción:
Es un programa que sirve para la clonación de equipos informáticos tanto del disco duro al completo (imágenes de disco) como de una o varias particiones

http de descarga:
https://www.acronis.com/es-es/products/true-image/

http de tutorial/manual de uso:
https://www.ubackup.com/es/clonar/guia-de-clonar-hdd-a-ssd-con-acronis-true-image.html

# Ej3

Instalamos la caracteristica de Copias de Seguridad de Windows Server, para ello tendremos que irnos al Administrador del servidor --> Pulsar en Agregar roles y caraceteristicas -->
Pulsaremos siguiente hasta llegar al apartado caracteristicas --> Marcaremos Copias de Seguridad de Windows Server --> Pulsaremos en siguiente e Instalaremos 

![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/3abbe7a6-836b-46a4-b3d8-6d96784d0908)

Nos iremos al administrador del servidor --> Herramientas --> Copias de seguridad de windows y no iremso a la pestaña de copias de seguridad local

<img width="641" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/21d31282-6b0c-439c-b6ec-1a94577826fa">





