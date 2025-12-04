# Trabajo 32: DatagramSocket y DatagramPacket

Para este trabajo tuvimos que utilizar DatagrmaSocket y DatagramPacket para poder enviar paquetes, en este caso son los mensajes que se envían entre servidor y cliente.

Después de saber que son estas funciones, hay que realizar una aplicación donde el cliente envía una lista al servidor y este tiene que revisar cual es la palabra más larga y enviarsela al cliente.

## Servidor:
En el servidor podemos encontrar el DatagramSocket y el primer DatagramPacket, el primero se utilizar para declarar el puerto y el segundo para esperar la conexión del cliente.

Después de que se haya conectado el cliente, tendremos que crear otra cantidad de bytes (buffer2) y otro DatagramPacket que servirán para los mensajes que envie el cliente. 

Por último, creamos la String que se enviará al cliente con la palabra más larga que haya escrito.

<img width="612" height="888" alt="Captura desde 2025-12-04 09-51-33" src="https://github.com/user-attachments/assets/ff49be06-47ea-42ae-bd10-e0080a4c0b31" />




