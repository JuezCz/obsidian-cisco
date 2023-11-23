Las capsulas de nivel 2 se llaman tramas y siguen este esquema.


PDU enlace de datos (trama)
**ENCABEZADO :  DATOS  :  COLA**

La capa 2 (enlace) es la única que añade información al final de su PDU. Hay que tener en cuenta que los campos que contiene en encabezado y la cola de la trama variaran según el protocolo utilizado.

![[Pasted image 20231123171508.png]]

**Inicio y Final de trama**:  Identifican donde empieza y termina una trama.
**Direccionamiento**: Nodos de origen y destino en los medios.
**Tipo**: Identifica el protocolo de la capa 3 empleado.
**Control**: Control de flujo.
**Datos**: El contenido de la trama (Datagrama, segmento, datos).
**Detección de errores**: Se incluyen justo después de los datos, forman parte del final de la trama.


**Direccionamiento**
La dirección MAC identifica un dispositivo en una red local. Cuando cambias el dispositivo de una red a otra este, seguirá teniendo la misma dirección física (MAC).
Como la dirección física va incluida en el encabezado de la trama, el proceso para aceptar o rechazar una trama es muy rápido.

El direccionamiento físico solo se utiliza para la entrega de los paquetes  localmente ( en una misma red). 
Cuando un host envía un paquete a un host remoto, un router intermedio debe aceptar la trama, desencapsularla y mirar a que dirección lógica (IP) va dirigido el paquete.
Entonces la vuelve a encapsular modificando la dirección MAC origen y destino por la suya y la siguiente en el medio.

Tanto en LAN, WAN como en WLAN se emplea el protocolo TCP/IP en la capa 3. sin embargo los protocolos de la capa 2 varían según el tipo de medio al que se necesita acceder.


Los protocolos de la capa de enlace de datos incluyen:

- Ethernet
- 802.11 inalámbrico
- Protocolo punto a punto (PPP)
- Control de enlace de datos de alto nivel (HDLC, High-Level Data Link Control)
- Frame Relay