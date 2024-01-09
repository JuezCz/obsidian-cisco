** Descripción general de ARP**
ARP (Address Resolution Protocolo): Se encarga de resolver que dirección MAC pertenece a una dirección IP dentro de una red local.

Para poder enviar un paquete en una misma red el host debe conocer la dirección MAC de destino. Si no la conoce se enviara un mensaje ARP a todos los dispositivos para conocer la MAC de cada uno de ellos y asignarla con sus direcciones IP.


ARP proporciona dos funciones básicas:

- Resolución de direcciones IPv4 a direcciones MAC
- Mantener una tabla de asignaciones de direcciones IPv4 a MAC


Cuando se envía un paquete a la capa de enlace de datos para encapsularlo en una trama de Ethernet, el dispositivo consulta una tabla en su memoria para encontrar la dirección MAC que está asignada a la dirección IPv4. Esta tabla se almacena temporalmente en la memoria RAM y se denomina tabla ARP o caché ARP.

- Si la dirección IPv4 de destino del paquete está en la misma red que la dirección IPv4 de origen, el dispositivo busca la dirección IPv4 de destino en la tabla ARP.
- Si la dirección IPv4 de destino está en una red diferente que la dirección IPv4 de origen, el dispositivo busca la dirección IPv4 del gateway predeterminado.

El dispositivo emisor busca en su tabla ARP la dirección IPv4 de destino y la dirección MAC correspondiente.


>**IMPORTANTE**
>Solo el dispositivo con la dirección IPv4 de destino asociada con la solicitud ARP responderá con una respuesta ARP

- **Dirección MAC de destino** – Es la dirección MAC del remitente de la solicitud de ARP.
- **Dirección MAC de origen** – Esta es la dirección MAC del remitente de la respuesta ARP.
- **Tipo** - Los mensajes ARP tienen un campo de tipo de 0x806. Esto informa a la NIC receptora que la porción de datos de la trama se debe enviar al proceso ARP.


Si ningún dispositivo responde a la solicitud de ARP, el paquete se descarta porque no se puede crear una trama.


**IPv6 utiliza un proceso similar a ARP para IPv4, conocido como ICMPv6 Neighbour Discovery (ND)**

