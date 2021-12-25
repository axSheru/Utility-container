# Instrucciones.

Ejecutar:

* docker build -t mynpm .
* docker run -it -v [PATH ABSOLUTO AL PROYECTO]:/app mynpm init

Ejemplo:

* docker run -it -v "C:\Users\alex0\Documents\Udemy\Docker and Kubernets\utility-container:/app" mynpm init