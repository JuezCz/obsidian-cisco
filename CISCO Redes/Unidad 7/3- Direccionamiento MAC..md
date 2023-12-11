La dirección MAC identifica los dispositivos de forma UNICA en una misma red.

Una dirección MAC esta formada por:
**48 bits** repartidos en **6 Bytes** representados en **12 valores hexadecimales**.

![[Pasted image 20231127104507.png]]

Los tres primeros bytes identifican al fabricante de la NIC (OUI). Los tres bytes restantes identifican al equipo.



**Dirección MAC unicast**
Es la dirección MAC única utilizada en una trama enviada de un dispositivo a otro.


La asignación de una dirección MAC con una dirección IP se realiza mediante el protocolo ARP (Address Resolution Protocol).


**Dirección MAC broadcast**
Esta dirección MAC se emplea para enviar una trama a todos los dispositivos de una red. Esta trama irá con la dirección MAC FF-FF-FF-FF-FF-FF. Es DECIR, LOS 48 bits a 1.

Si en los datos encapsulados hay una dirección IPv4, todos los dispositivos de esa red recibirán el mensaje.


Como ejemplo de mensajes IPv4 que emplean direcciones broadcast tenemos DHCP.


**Dirección MAC multicast**
Este tipo de mensaje envía paquetes a un grupo determinado de la red (no a todos).






