La capa de red (capa 3 modelo OSI) se encarga de que dos dispositivos finales puedan encontrarse.

Los protocolos que utiliza para el direccionamiento o enrutamiento son IPv4 e IPv6.

La capa 3 se encarga de estos 4 puntos.

+ **Direccionamiento de dispositivos finales**
+  **Encapsula** las PDU en datagramas añadiendo a las PDU de nivel superior encabezados IP origen y destino. El encapsulado se realiza en origen.
+ **Enrutamiento**: Proporciona servicios para dirigir los paquetes a un host de otra red. El router selecciona la mejor ruta. 
+ **Des encapsulación**: Cuando la capa 3 recibe un datagrama, la desencapsula para leer el encabezado IP. SI la IP destino coincide con la suya se elimina el encabezado IP del datagrama. Una vez hecho esto  se pasa la PDU a la capa 4 (transporte).



