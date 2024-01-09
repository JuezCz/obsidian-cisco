
En IPv6 se emplea ND (también NPD), su función es similar a ARP en IPv4.

ND proporciona servicios de resolución de direcciones, detección de routers y redirección para IPv6 mediante ICMPv6. ICMPv6 ND utiliza cinco mensajes ICMPv6 para realizar estos servicios:

- NS: Mensajes de solicitud de vecinos.
- NA: Mensaje de anuncio de vecino
- RS: Mensaje de solicitud del router
- RA: Mensajes de anuncio del router. Mensaje de* redirección


NS, se envia utilizando direcciones mensaje multibroadcast Ethernet. Esto permite que la NIC Ethernet del dispositivo receptor determine si el mensaje de solicitud de vecino es para sí mismo sin tener que enviarlo al sistema operativo para su procesamiento.
![[Pasted image 20240109152422.png]]