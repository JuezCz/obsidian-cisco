
- **Dirección física (la dirección MAC)** – Se utiliza para comunicaciones NIC a NIC en la misma red Ethernet.

- **Dirección lógica (la dirección IP)** – Se utiliza para enviar el paquete desde el dispositivo de origen al dispositivo de destino. La dirección IP de destino puede estar en la misma red IP que la de origen o en una red remota.



En una red local

![[Pasted image 20240109142330.png]]

La trama Ethernet de capa 2 contiene lo siguiente:
- **Dirección MAC de destino**: esta es la dirección MAC simplificada de PC2, 55-55.
- **Dirección MAC de origen**: es la dirección MAC simplificada de la NIC Ethernet en PC1, aa-aa-aa

El paquete IP de capa 3 contiene lo siguiente:
- **Dirección IPv4 de origen**: esta es la dirección IPv4 de PC1, 192.168.10.10.
- **Dirección IPv4 de destino**: esta es la dirección IPv4 de PC2, 192.168.10.11.



