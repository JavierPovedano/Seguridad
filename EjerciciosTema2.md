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

Nos iremos a "Programar una copia de seguridad" --> Pulsaresmo en siguiente --> Dejaremos la opción seleccionado para que nos cree una copia completa del sistema

<img width="334" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/e7c4d6dd-7625-4a0d-9459-8330884d7512">

Indicaremos que la copia se realize una vez al dia y le indicamos la hora

<img width="513" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/cbfaa4a3-44b6-4d6a-80af-0a6cab90e1cf">

Indicamos el destino de la copia, elegerimos en un disco dedicado a copias de seguridad

<img width="339" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/0ca25b31-dbed-4d7c-bdf4-794a087709d8">

Seleccionaremos nuestro disco pulsando en "Mostrar todos los discos disponibles", seleccionaremos el vasmos a usar y lo marcaremos 

<img width="584" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/25781dad-1de0-43f2-938d-76cf6d9d3df6">

Pulsaremos en finalizar y ya se creara la programación de la copia de seguridad

<img width="337" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/9d2a9e5e-a874-4987-96ed-b51ed37019a9">
<img width="337" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/19b8a6cb-607f-4778-ba9f-8301a67883e8">

Para crear una copia de seguridad directamente tendremos que pulsar en "Hacer copia de seguridad" --> Indicaremos la opción de "Opciones diferentes" para configurar una copia de seguridad distinta a otra creada 

<img width="338" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/27a5a8b4-e1ab-42de-9fea-9420434a5b37">

Indicaremos la opción personalizada 

<img width="337" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/ba77d2ed-5b1a-4ca8-871e-38b75b6145ab">

Pulsaremos en "Agregar elementos" --> Inidcaremo sobre que directorios queremos hacer la copia

<img width="610" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/bbe34ac0-f60f-4592-b6c5-058964afee69">

Indicamos que la copia se haga en el propio equipo 

<img width="332" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/d86179e6-c1a1-44d3-9b40-3755e2cda292">

Indicamos donde queremos hacer la copia 

<img width="334" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/c4fa83e6-9a00-4ee8-83fd-7b999365b53d">

Confirmamos que esta bien configurado y pulsamos en "Copia de Seguridad"

<img width="334" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/81d5852c-bd85-40bf-a1b3-41c4167dc9eb">

Ya estaria creada

<img width="335" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/1583c8ef-9629-42d3-8546-5db8d67fa63e">

Para recuperar el estado de la maquina tendremos que darle a "Recuperar" --> Inidcaremos donde esta la copia de seguridad 

<img width="370" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/49b3a808-1e4c-48e2-a2c0-bfd5e5b5d130">

Tendremos que elegir que copia usaremos mediante un sistema de fecha y hora

<img width="368" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/3502e6c4-b304-46fe-9d1b-5f2eab4245c3">

Indicamos el tipo de recuperación, que será "Estado del sistema"

<img width="368" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/5d161c23-f569-404e-8f50-7525f2871693">

Inidacaremos donde queremos que se restaure, que será en "Ubicación Original"

<img width="371" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/25261f97-b3b2-48ef-97dd-35535cc261af">

Pulsaremos en recuperar --> Nos informara de que se reiniciara el equipo al recuperar 

<img width="370" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/9fa1c4fe-3294-4659-a719-98d073626320">

# Ej20

Tendremos que tener tres discos connectados uno para el /boot y los otros dos para hacer el raid

<img width="728" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/5b523ee7-8f72-4f33-9854-675fe0aecf6f">

Iniciaremos la maquina --> La configuaremos a nuestro gusto hasta llegar a esta pantalla en la que tendremos que indicar la opción "Custom Storage layaut"

<img width="402" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/402a5379-4d9b-4739-b508-b63c7a8ba8a1">

Nos vamos al disco con menor capacidad y le indimacamos la opción "Usue as boot device"

<img width="400" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/18c13f42-2b41-47dc-a5c9-83d34ba5b7c9">

Pulsamos en la opción "Create software Raid" --> indicamos los dos discos que usaremos y pulsaremos en hecho

<img width="401" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/2b01dda7-c001-4c40-a0de-b395af716191">

Nos aparecera el raid en el que tendremos que crear dos particiones una swap y la raiz

<img width="358" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/f1197cc9-038f-4cb5-9b13-895f6e17af0e">

Pulsamos en "hecho" --> Aceptamos la ventana que nos aparece --> Introducimos el usuario y el servidor que queremos crear --> Pulsamos en "Hecho" en el resto de pantallas

<img width="401" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/890fc0da-1395-4708-97dd-5f5ecfc5145a">



