La capa 2, se subdivide en dos subcapas.

**LLC (Logical Link Control): IEEE 802.2**
	-Comunica el software de red en capas superiores y el hardware en las capas inferiores. 
	-Identifica en la trama que protocolo de capa 3 se utiliza para la trama. 
	-Añade información de control a la trama.

**MAC (Media Access Control)**
	-Implementa los protocolos 802.3, 802.11, 802,15 para    conexiones cableadas e inalámbricas.
	-Encapsula los datagramas y se encarga del  acceso al medio.
	-Proporciona direccionamiento origen y destino.
	-Encabezado para detección de errores


![[Pasted image 20231123155727.png]]

La subcapa MAC también proporciona control de acceso a medios, lo que permite que varios dispositivos se comuniquen a través de un medio compartido (semidúplex). Las comunicaciones dúplex completo no requieren control de acceso.
