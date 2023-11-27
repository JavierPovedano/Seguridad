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

JOHN
  -Iniciamos la maquina kali -> Vamos a las aplicaciones -> Password attacks -> john
  <img width="294" alt="Captura de pantalla 2023-11-27 123017" src="https://github.com/JavierPovedano/Seguridad/assets/117440210/778f92e2-698c-4308-9116-d4a45a689e53">

  - Iniciomos con sudo y ponemos el comando "john /etc/shadow"
