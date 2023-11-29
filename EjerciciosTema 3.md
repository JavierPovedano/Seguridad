#Ejercicio 1


#Ejercicio 2
Windows:
  -Nos vamos al Administrador de tareas -> herramientas -> Directivas de seguridad local
  <img width="481" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/b0714af7-6d1b-4c84-83d6-80671e197a98">

  -Nos iremos a Directivas de cuenta -> Directivas de contraseña -> y aqui tendremos todas la directivas que podemos modificar
  <img width="393" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/391f743e-38c2-4577-903f-eaf665b144b1">

  -Principalmente activaremos la directiva "La contraseña de cumplir los requisitos de complejidad" la cual nos exige que tenga Mayúsculas (de la A a la Z), Minúsculas (de la a a la z),
   Dígitos de base 10 (del 0 al 9)
  <img width="587" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/2d20989c-b956-47ed-ba5b-9918723766c5">

Linux:
  - Para cambiar la directiva tendremo que instalar un paquete con "sudo apt install libpam-cracklib"
  - Editamos el fichero "/etc/pam.d/common-password" y añadirmos la linea "password requisite pam_cracklib.so OPCIONES " las opciones pueden ser:
    -retry: Número de intentos antes de que el sistema devuelva un error.
    -minlen: Longitud mínima de contraseña.
    -difok: Cambios de caracteres que debe tener la nueva contraseña en comparación con la vieja.
    -ucredit: Caracteres en mayúscula que debe tener.
    -lcredit: Caracteres en minúscula que debe tener.
    -dcredit: El número de dígitos que debe tener la nueva contraseña.
    -ocredit: El número de dígitos que debe tener la contraseña. 
  <img width="405" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/9e930706-8f53-4ade-8559-ac06f369e5e3">

#Ejercicio 3

#Ejercicio 4

#Ejercicio 5

  -Iniciamos la maquina kali -> Vamos a las aplicaciones -> Password attacks -> john
  
  <img width="294" alt="Captura de pantalla 2023-11-27 123017" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/778f92e2-698c-4308-9116-d4a45a689e53">

  - Iniciomos con sudo y ponemos el comando "unshadow /etc/passwd /etc/shadow > /home/kali/Desktop/contra.out" y veremos que se a creado el archivo
  - 
    <img width="302" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/c555f1f1-becd-494f-9934-f89d328ef0b1">

  - Ponemos el comando "john --format=crypt contra.out" para sacar los usuarios y contraseñas
  - 
  <img width="467" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/d72b5d57-8ca3-4d7c-af95-3b2841008b7e">

  -Mostraremos el resultado con "john --show contra.out"
  
  <img width="197" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/9c17c9e4-9c87-44b4-9ed6-650246d28733">

#Ejercicio 6

Listado:

  -DEEP FREEZE
  
  -REBOOT RESTORE RX
  
  -TOOLWIZ TIME FREEZE
  
  -SMARTSHIELD
  
  -Clean Slate de Fortres Grand
  
  -SafeShield de Filestream
  
  -Rextore de Crucial Solutions
  
  -Shadow Defender de SD

DEEP FREEZE

-Instalación:

  -Nos descargamos el instalador -> Lo ejecutamos -> Pulsamos siguiente en cada pestaña -> Aceptamos las politicas -> Marcamos la opcion de usar prueba 
  
  <img width="389" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/3a92acbb-5a50-4b5d-b769-8b0d13a3cc1e">

  -Nos aparecera una pestaña para cambiar la contraseña 

  <img width="209" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/f88bf704-1fdc-42c5-8987-3cb9133d646a">

  -Para abrir la pestaña de DEEP FREEZE tendremos que pulsar "SHIFT, CTROL, ALT y F6" -> Nos iremos a la pestaña de "Control de reinicio" -> Marcaremos la opcion "Reiniciar Congelada" ->
  Pulsamos el boton "Aplicar y reiniciar" 

  <img width="303" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/e9829880-0b0d-443c-ba86-98e69d017e6f">

  -Comprobamos si funciona creando una carpeta y reiniciando 

  <img width="539" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/849f01c7-a325-47af-9112-714b1149d4f4">

  -Vemos que no esta

  <img width="656" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/4565e5dc-2f83-4fbb-8aa9-b763ed5081d3">


  -Nos descargamos el instalador -> Lo ejecutamos -> Pulsamos siguiente en cada pestaña -> Marcamos la opción de reiniciar y fanalizamos  

  <img width="248" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/31a8275f-0494-4356-8ddc-4ec48a9de25d">

  <img width="247" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/d078878f-aac0-4cc8-a842-0bbc5eec58cc">

  -Comprobamos si funciona creando una carpeta y reiniciando

  <img width="284" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/41fc6d52-543a-4ba3-a056-873f762a2bb6">

  -Vemos que no esta

  -<img width="482" alt="image" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/77aeb8c6-08ca-4b2f-a300-781859956c89">


