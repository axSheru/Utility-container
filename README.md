# Acerca de.

Este proyecto nos permite correr comandos de node en el contenedor y ver los resultados en nuestra máquina local.

# Instrucciones.

Ejecutar:

* docker build -t mynpm .
* docker run -it -v [PATH ABSOLUTO AL PROYECTO]:/app mynpm [COMANDO]

Ejemplo:

* docker run -it -v "C:\Users\alex0\Documents\Udemy\Docker and Kubernets\utility-container:/app" mynpm init